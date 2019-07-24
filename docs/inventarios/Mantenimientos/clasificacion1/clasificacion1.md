##1 Información General

El módulo Clasificación 1 permite la gestión de sublínea en los cuales el usuario puede crear o modificar información de una determinada sublínea.

###1.1 Condiciones

En el módulo de mantenimientos para **INVENTARIOS** se ha implementado la siguiente lógica:

!!! danger
    1. La Clasificación1 tiene 2 niveles los mismos que se visualizarán en un listado en árbol.
    2. Para poder gestionar una sublínea debemos dar doble clic en una Clasificación de nivel 1 para visualizar sus niveles inferiores. 
    <center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/Clasificacion1Niveles.png "Ingreso Modulo Clasificaion1")</center>

!!! note
    Si no tienes disponible el menú **Clasificación1** debes solicitar el respectivo acceso al departamento de TI.

##2 Módulo

Para acceder al módulo de Clasificación1 se debe ingresar al software ENIGMA y dar clic sobre el menú principal Inventario, posterior en Mantenimiento y finalmente en Clasificación1 como lo indica la imagen.

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/ingresoclasificacion1.png "Ingreso Modulo Clasificaion1")</center>

###2.1 Clasificacion1.
La ventana de Clasificación se visualizará de la siguiente manera:

<center>![Módulo Mantenimiento Caracteristica](\inventarios\Mantenimientos\clasificacion1\resources\generalclasificacion1.png "generalclasificacion1")</center>

1. Listado de Clasificación1 en nivel 1 y 2.
2. Información de la clasificación seleccionada, en esta sección se encuentra:
Código, Nombre, nivel, reporta (Clasificación nivel 1 a la que pertenece), 
Jefe de Línea, Controlador de buffer y Característica.
3. Botones de acción si necesitamos crear modificar o eliminar una característica se lo podrá hacer desde estos      botones.
4. Cuadro de búsqueda se puede ingresar referencias del nombre o código, presionar buscar para ejecutar la búsqueda o vaciar para limpiar el cuadro de búsqueda.

!!! danger
    Es obligatorio ingresar una Característica en cada sublínea nivel 2. 

###2.2 Crear una Clasifición1
####2.2.1 Selección de Clasificación 1 nivel 1.
Para crear una clasificación1(Sublinea), se debe tener en cuenta que podemos crear únicamente Clasificaciones nivel 2, para ello vamos a ubicarnos en el listado de clasificaciones y seleccionar la clasificacion1 nivel 1.

!!! danger
    Para crear una clasificación1 es muy importante seleccionar una característica nivel 1 ya que si seleccionamos un nivel 2 no nos va permitir crear. 
    <center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/Clasificacion1Niveles.png "Ingreso Modulo Clasificaion1")</center>

####2.2.2 Botón Nuevo.
Una vez ya seleccionada la clasificación presionamos el botón Nuevo.

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/crear_clasificacion1_boton_nuevo.png "Ingreso Modulo Clasificaion1")</center>

1. Presionar botón nuevo.
2. Datos de la clasificación nueva que vamos a crear, campos como código, nivel, reporta se crean automáticamente al momento de presionar nuevo, lo que se debe ingresar es: 
Nombre: es el nombre de la característica con la que se va a crear.
Jefe Línea: es la persona a la que le se asignará como jefe de línea de esta Clasificación.
Controlador de Buffer: es la persona a la que le se asignará como Controlador de Buffer de esta Clasificación.
3. Características que identifican a la clasificación, en esta sección podemos agregar características existentes.

####2.2.3 Ingreso de Información.

La información se debe llenar de la siguiente manera.

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/crear_clasificacion1_ingreso_informacion.png "Ingreso Modulo Clasificaion1")</center>

1. Ingresamos el nombre de la clasificación.
2. Seleccionamos un jefe de línea.
3. Seleccionamos un controlador de Buffer.
4. Desplegar el listado de personas para poder asignar un controlador de buffer o Jefe de línea. 
5. Buscar una persona determinada, una vez desplegado el listado digitamos indicios de los apellidos de la persona que buscamos, una vez filtrado seleccionados.

#####2.2.3.1 Agregar Características

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/Agregar_caracteristica.png "Ingreso Modulo Clasificaion1")</center>

1. Lista de Características que se pueden agregar a la Clasificación
2. Lista de Todas las características que se pueden agregar a una clasificación. Seleccionamos una dando clic sobre la característica que deseamos.
3. Botón para agregar. Presionamos cuando ya tengamos una característica seleccionada.
4. Listado de Características agregadas a la clasificación. 

#####2.2.3.2 Remover Características

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/remover_caracteristicas.png "Ingreso Modulo Clasificaion1")</center>

1. Seleccionar con el check la característica que se desea remover.
2. Remueve la característica.
3. Listado se actualizado de características.

!!! danger
    Es importante seleccionar una característica con el check para poder removerla. 

#####2.2.3.3 Agregar términos

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/agregar_terminos.png "Ingreso Modulo Clasificaion1")</center>

1. Digitamos el termino de búsqueda que queremos agregar.
2. Botón para agregar el término.
3. Listado de todos los términos agregados.

#####2.2.3.4 Remover términos

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/remover_terminos.png "Ingreso Modulo Clasificaion1")</center>

1. Seleccionar el término que desea remover.
2. botón para remover.
3. Lista actualizada de términos.

####2.2.4 Guardar.
Una vez llenado toda la información de la clasificacion1 procedemos a guardarla de la siguiente manera:

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/guardar_clasificacion1.png "Ingreso Modulo Clasificaion1")</center>

1. Presionamos en el botón guardar.
2. Se visualizará un mensaje de que se guardó exitosamente. La lista en árbol se actualizará, procedemos a buscar la clasificación que creamos.
3. Datos de la clasificación creada

!!! danger
    Solo se procederá a guardar si se tiene llenados todos los campos en caso de no tenerlos se visualizará un mensaje con la información que falte.
     <center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/error_falta_informacion.png "Ingreso Modulo Clasificaion1")</center>

###2.3Modificar una clasificación.

####2.3.1 Selección de Clasificación.

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/modificar_clasificacion_seleccion.png "Ingreso Modulo Clasificaion1")</center>

1. Seleccionamos una clasificacion que seamos modificar.
2. Informacion actual de la clasificacion.

####2.3.2 Modificación de Información.
<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/agregar_informacion_modificar.png "Ingreso Modulo Clasificaion1")</center>

1. Realizamos las modificacion que necesitamos, se puede realizar cambios de nombre de clasificacion, jefe de linea y controlador de buffer.  
2. Agregar y remover Caracteristicas.
2. Agregar y remover Terminos.


####2.3.3 Guardar.
Una vez llenado toda la información de la clasificacion1 procedemos a guardarla de la siguiente manera:

<center>![Ingreso Modulo Clasificaion1](/inventarios/Mantenimientos/clasificacion1/resources/guardar_modificar_clasificacion1.png "Ingreso Modulo Clasificaion1")</center>

1. Presionamos en el botón guardar.
2. Se visualizará un mensaje de que se guardó exitosamente. La lista en árbol se actualizará, procedemos a buscar la clasificación que modificamos.
3. Datos de la clasificación modificada.

