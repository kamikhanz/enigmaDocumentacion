

##1.0 Información General
La experiencia MOXAL es un evento comercial, realizado de manera anual por **MOTORALMOR** donde el objetivo es fomentar al cliente a que llene el album entregado, para el año 2019 se ha propuesto los siguientes objetivos:


|Tipo de Cromo|Cantidad de Cromos|Valor|
|---|---|---|
|Normales|300|Cada cliente tiene su propio valor por cromo|
|Especial Moxal|1|$5000|
|Especial Trazano|1|$5000|
|Especial Duro|1|$5000|
|Especial Kenda|1|$5000|
|Especial Pirelli|1|$5000|
|Especial Trazano|1|$5000|

Por cada 50 cromos normales el cliente se hace acreedor a un cupo para la **EXPERIENCIA MOXAL**, si el cliente obtiene los 6 cromos especiales se hace acreedor a un cupo adicional para la **EXPERIENCIA MOXAL**

##1.1 Condiciones

En el modulo de control de cromos para la **EXPERIENCIA MOXAL** se ha implementado la siguiente lógica:

!!! danger
    1. Se considera solo facturas emitidas desde el 01 de Abril 2019 hasta el 31 de Diciembre 2019 y que esten canceladas en su totalidad. 
    2. De las facturas se considera solo el subtotal neto ( Sin productos gratis y descuentos adicionales ). Genera un DEBITO
    3. Se resta las notas de credito por valor que hayan sido vinculadas a las facturas emitidas y canceladas a partir del 01 de Abril 2019. Genera un CREDITO
    4. Se resta las notas de credito por devolucion que hayan sido realizadas a las facturas emitidas y canceladas a partir del 01 de Abril 2019. Genera un CREDITO
    5. Cuando se realiza la generacion de cromos el módulo realiza el siguiente calculo: (DEBITOS-CREDITOS)/VALOR DEL CROMO. En caso de que el saldo(DEBITOS-CREDITOS) sea menor al valor del cromo se genera un saldo para las proximas transacciones y no genera cromos. 
    6. El canje de cromo genera una transaccion del tipo CREDITO

!!! info
    Si los clientes ingresados en la **EXPERIENCIA MOXAL** tienen vinculados estos tambien se incluirán en el cálculo (facturas y notas de crédito).

Todas estas transacciones (DEBITOS, CREDITOS y SALDOS) son visibles y se pueden visualizar en un reporte historico por cliente desde el módulo de **EXPERIENCIA MOXAL**.
##1.2 Ingreso al Modulo
Para acceder al modulo de control de cromos se debe ingresar al software ENIGMA y dar click sobre el menu principal **EXPERIENCIA MOXAL**, posterior a la ventana de carga se muestra el módulo.

!!! note
    Si no tienes disponible el menu **EXPERIENCIA MOXAL** debes solicitar el respectivo acceso al departamento de TI.

##1.3 Módulo
<center>![Módulo principal EXPERIENCIA MOXAL](/comercial/resources/modulo_experiencia_moxal_numeros.png "Módulo principal EXPERIENCIA MOXAL")</center>

1. Ultima fecha de generación de cromos.
2. Calcula los nuevos cromos para entrega **en caso de existir**
3. Abre una ventana auxiliar para realizar la entrega de cromos y detalla el histórico de entregas del cliente seleccionado.
4. Genera un reporte en PDF detallado del cliente con todas sus transacciones facturas, notas de credito y canje de cromos.
5. Exporta la tabla dinámica actual a formato excel
6. Muestra la fecha en que el cliente generó cromos por ultima vez.
7. Detalla los ultimos cromos generados del cliente.
8. Apellidos y nombres del cliente ingresado a experiencia MOXAL
9. Indica que si los cromos generados ya fueron despachados. La fila se mostrará de color verde indicando que falta confirmar la entrega.

!!! info
    El archivo PDF del reporte (punto #4) se exporta en la carpeta documentos del usuario actual en el directorio "reportes_enigma" con el nombre "experiencia_moxal.pdf"

###1.3.1 Proceso de calculo de cromos
El módulo realiza los siguientes pasos para los cromos

1. Busca las facturas canceladas en su totalidad del cliente o sus vinculados y considera el **subtotal de la factura- pronto pago - ajustes - productos gratis** 
2. Se procede a buscar las notas de credito por valor que afecten a las facturas del PASO #1 se considera **subtotal de la nota de credito**
3. Se busca las notas de credito por devolucion de las facturas del PASO #1 se considera **subtotal de la nota de credito**
4. Finalmente se genera los cromos en base al saldo y el valor individual del cromo **(facturas - notas de credito - cromos entregados)**

###1.3.2 Detalle de entrega de cromos
Se debe seleccionr el cliente deseado y posterior pulsar sobre el boton detalle el sistema despliega la siguiente ventana:
<center>![Módulo principal EXPERIENCIA MOXAL](/comercial/resources/detalle_experiencia_moxal.png "Módulo principal EXPERIENCIA MOXAL")</center>

1. Ultima fecha de generacion de cromos.
2. El boton permite marcar como cromos despachados al registro seleccionado.
3. Genera el reporte detallado de todas las transacciones del cliente seleccionado.
4. Exporta la tabla con la informacion de cromos generados a EXCEL.
5. Muestra la fecha cuando se confirmó el envio de cromos en caso de no existir la fecha se mostrará como 1/1/0001
6. Fecha de cuando se generó los cromos mediante el boton actualizar de la ventana anterior.
7. Detalle de cantidad y secuencias de los cromos.
8. Nombre del cliente.
9. Indica si ya se confirmó el envio de cromos.

###1.3.3 Reporte detallado por cliente
Este reporte puede ser generado desde el modulo principal se debe seleccionar el cliente desado y dar click sobre el boton REPORTE, el sistema generará un archivo PDF con todo el historico de transacciones del cliente.

