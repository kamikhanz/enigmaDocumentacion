##1. Información General
**MOTORALMOR** mantiene convenios con transportistas a nivel nacional, dichas alianzas brindan beneficios para las partes interesadas. Uno de estos beneficios es la automatizacion de guias y control de las mismas para mayor seguridad de la mercaderia que sera entregada a nuestro cliente.

Los sistemas automaticos de los transportistas aliados necesitan obtener el destino de mercaderia exacto tal y como ellos lo conocen a dicho destino en su sistema, para eso, **ENIGMA** brinda un mantenimiento de **transporte por destino** en el cual los usuarios podran asignar una parroquia (_segun catalogo de la INEC_) con la ubicacion tal y como la conoce el sistema del transporte aliado.

**Ejemplo:** (_SISTEMA LAAR_)

| PROVINCIA | CATALOGO INEC                                       | SISTEMA LAAR |
| --------- | --------------------------------------------------- | ------------ |
| GUAYAS    | ALFREDO BAQUERIZO MORENO (JUJAN), CABECERA CANTONAL | TRES POSTES  |

##2. Formulario

En el modulo de **transporte por destino** brinda un mantenimiento para cotejar la infomacion del _Catalogo del INEC_ con la que poseen nuestros transportistas.

<center>![Mantenimiento de transporte por destino](/bodega/transporte_destino/resources.png "Transporte por destino - pantalla principal")</center>

##3.1. Catalogo INEC

En la **FIG.1** se muestra el catalogo tal y como dicta la INEC, con la estructura en 3 niveles: _provincia, canton, parroquia_, este arbol de ubicaciones cuenta con un cuadro de busqueda, el cual se encuentra sobre la **FIG.1**.

##3.2. Datos por transporte

En la **FIG.2** consta de tres listas de opciones; la primera opcion permite elegir el transporte, es necesario destacar que en este listado unicamente se mostrara los transportes con los cuales **MOTORALMOR** posea convenios vijentes. En la segunda opcion se enlista las provincias en las cuales el transporte elejido (_primera opcion_) tenga cobertura.
En la tercera y ultima lista, del mismo modo se mostraran las parroquias pertenecientes a la provincia (_segunda opcion_), al transporte elegido (_tercera opcion_) y, que ademas, el transporte brinde cobertura.

##3.3. Ubicacion final INEC

En la **FIG.3** se mostrara la ubicacion final perteneciente al _Catalogo del INEC_ que previamente hayamos elegido (_FIG.1_).

##3.4. Botones de accion

La **FIG.4** indica las acciones que podemos realizar en este mantenimiento. _Eliminar, guardar y ayuda_.

##3.5. Lista de relaciones

En tanto, la **FIG.5** hace referencia a la lista de relaciones ya asignadas. En este listado se puede observar el _transporte, provincia y canton_ de la ciudad que hayamos elegido en la **FIG.1**.

!!! info
El archivo PDF del reporte (punto #4) se exporta en la carpeta documentos del usuario actual en el directorio "reportes_enigma" con el nombre "experiencia_moxal.pdf"

###3.1.1. Proceso de calculo de cromos
El módulo realiza los siguientes pasos para los cromos

<center>![Módulo principal EXPERIENCIA MOXAL](/comercial/resources/detalle_experiencia_moxal.png "Módulo principal EXPERIENCIA MOXAL")</center>
