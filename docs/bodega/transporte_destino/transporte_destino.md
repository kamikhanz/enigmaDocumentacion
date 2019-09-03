##1. Información General
**MOTORALMOR** mantiene convenios con transportistas a nivel nacional, dichas alianzas brindan beneficios para las partes interesadas. Uno de estos beneficios es la automatización de guías y control de las mismas para mayor seguridad de la mercadería que será entregada a nuestro cliente.

Los sistemas automáticos de los transportistas aliados necesitan obtener el destino de mercadería exacto tal y como ellos lo conocen a dicho destino en su sistema, para eso, **ENIGMA** brinda un mantenimiento de **transporte por destino** en el cual los usuarios podrán asignar una parroquia (_según catálogo del INEC_) con la ubicación tal y como la conoce el sistema del transporte aliado.

**Ejemplo:** (_SISTEMA LAAR_)

| PROVINCIA | CATALOGO INEC                                       | SISTEMA LAAR |
| --------- | --------------------------------------------------- | ------------ |
| GUAYAS    | ALFREDO BAQUERIZO MORENO (JUJAN), CABECERA CANTONAL | TRES POSTES  |

##2. Formulario

En el módulo de **transporte por destino** brinda un mantenimiento para cotejar la información del _Catalogo del INEC_ con la que poseen nuestros transportistas.

<center>![Mantenimiento de transporte por destino](/bodega/transporte_destino/resources/transporte_destino.png "Transporte por destino - pantalla principal")</center>

##3.1. Catalogo INEC

En la **FIG.1** se muestra el catálogo tal y como dicta el INEC, con la estructura en 3 niveles: _provincia, cantón, parroquia_, este árbol de ubicaciones cuenta con un cuadro de búsqueda, el cual se encuentra sobre la **FIG.1**.

##3.2. Datos por transporte

En la **FIG.2** consta de tres listas de opciones; la primera opción permite elegir el transporte, es necesario destacar que en este listado únicamente se mostrara los transportes con los cuales **MOTORALMOR** posea convenios vigentes. En la segunda opción se enlista las provincias en las cuales el transporte elegido (_primera opción_) tenga cobertura.
En la tercera y última lista, del mismo modo se mostraran las parroquias pertenecientes a la provincia (_segunda opción_), al transporte elegido (_tercera opción_) y, que además, el transporte brinde cobertura.

##3.3. Ubicación final INEC

En la **FIG.3** se mostrará la ubicación final perteneciente al _Catalogo del INEC_ que previamente hayamos elegido (_FIG.1_).

##3.4. Botones de acción

La **FIG.4** indica las acciones que podemos realizar en este mantenimiento. _Eliminar, guardar y ayuda_.

##3.5. Lista de relaciones

En tanto, la **FIG.5** hace referencia a la lista de relaciones ya asignadas. En este listado se puede observar el _transporte, provincia y cantón_ de la ciudad que hayamos elegido en la **FIG.1**.

#4. Mantenimiento

Para crear una relación entre una Parroquia (INEC) y Destino (Transporte), es necesario seleccionar una parroquia del Catalogo del INEC, para verificar que hayamos seleccionado una parroquia, el recuadro de la FIG.3 deberá reflejar el nombre de la parroquia seleccionada. Seguido tenemos que seleccionar un transporte del listado de transportes FIG.2, después una provincia y finalmente un destino. Una vez elegidos los campos a relacionar, procedemos a **Guardar**.

Para eliminar relaciones, seleccionamos una Parroquia (INEC) y seleccionamos la opción **Eliminar**.

!!! info
    Al seleccionar la opción **Eliminar**, estamos eliminando únicamente la relación que existía entre una Parroquia (INEC) y Destino (Transporte).
