
##1 Información General

Cuando se Genera una factura para proceder a realizar el envío Bodega
relocaliza la selección del destino en base a un listado de direcciones
en base a las direcciones que se cargan en el módulo de Cliente
Despacho.

### 1.1 Condiciones

En el módulo de Factura Despacho para **BODEGA** se ha implementado la
siguiente lógica:

!!!Danger
    - En base a una fecha seleccionada por el usuario se genera un listado
     de todas las facturas realizadas ese día con datos principales como:
     Numero de Factura, Nombre del Cliente, Dirección de envío,
     Transporte de envío, Provincia, Cantón, Parroquia de destino.

##2 Módulo

Para acceder al módulo de Cliente Despacho se debe ingresar al software
ENIGMA y dar clic sobre el menú principal, Bodega, y en Factura Despacho
como lo indica la imagen.

<center>![](/bodega/factura_despacho/resources/ingreso_modulo.png)</center>

### 2.1 Ventana Inicial.

La ventana de Cliente despacho se visualizará de la siguiente manera:

<center>![](/bodega/factura_despacho/resources/general.png)</center>

1.  Información principal del cliente.
2.  Listado de todas las facturas emitidas en la fecha seleccionada.
3.  Dirección de envío.
4.  Transporte por el cual se va a realizar el envío.
5.  Botón para guardar los cambios realizados en dirección y transporte.
6.  Fecha por la cual se filtran todas las facturas realizadas en ese
    día.

!!!Nota
    En caso de no tener registrada una dirección, se la debe agregar desde
    el módulo de cliente despacho.

### 2.2 Cambiar dirección y transporte de envío.
#### 2.2.1 Selección de la factura.

-   Se debe seleccionar una fecha por la cual se van a filtrar las
    facturas.
-   Una vez seleccionado se listarán todas las facturas de ese día.

<center>![](/bodega/factura_despacho/resources/fecha.png)</center>

<center>![](/bodega/factura_despacho/resources/listado_facturas.png)</center>

1.  Fecha de las facturas
2.  Listado de facturas
3.  Factura seleccionada

#### 2.2.2 Cambio de Dirección.

En dirección se tiene todas las direcciones cargados en el módulo de
Cliente Despacho

<center>![](/bodega/factura_despacho/resources/listado_direcciones.png)</center>

-   Seleccionar direccionar una dirección del listado

#### 2.2.3 Cambio de Transporte.

Se lista todos los transportes con la que la empresa realiza envíos.

<center>![](/bodega/factura_despacho/resources/listado_transporte.png)</center>

#### 2.2.4 Guardar.

<center>![](/bodega/factura_despacho/resources/guardar.png)</center>

!!!Danger
    - Cuando ya se tenga seleccionado la dirección y el transporte
    presionamos en el botón guardar y se visualizara el siguiente
    mensaje.

    <center>![](/bodega/factura_despacho/resources/guardar_ok.png)</center>



