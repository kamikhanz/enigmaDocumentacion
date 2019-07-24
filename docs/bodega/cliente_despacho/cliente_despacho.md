
##1 Información General

El departamento de bodega es el encargado de realizar los envíos a las
diferentes ciudades que los clientes solicitan. Todas las facturas
emitidas se realizan con la dirección que el cliente esta registrado en
el SRI, la dirección de envíos no es la misma con la del SRI.

### 1.1 Condiciones.

En el módulo de Direcciones para **BODEGA** se ha implementado la
siguiente lógica:

!!!Danger
    1.  Cada cliente tiene 1 o n direcciones a la que se le puede realizar
        los envíos. Para ello el personal designado del departamento de
        bodega deberá agregar nuevas direcciones o en caso de ser corregidas
        realizar las correcciones correspondientes.
    2.  Las direcciones tienen que ser registradas **OBLIGATORIAMENTE** con
        parroquia, en caso de no tenerla el sistema no permitirá guardar los
        cambios de ese cliente.
    3.  Después de agregar todas las direcciones es **OBLIGACION** del
        personal designado **PREDETERMINAR** una dirección, en caso de no
        hacerlo se tomará la Dirección de Facturación.
    4.  Los números telefónicos están validados para que el usuario ingrese
        sin 0, 9 dígitos en caso de ser Celular, Fax, WhatsApp, 8 dígitos en
        caso de ser Casa u Oficina.
    5.  El sistema automáticamente agrega +593 en los números telefónicos.
    6.  Debe existir un **TRANSPORTE PREDETERMINADO** al igual que las
        direcciones es obligación del personal designado predeterminar un
        transporte de envió.

- Códigos Provinciales para números teléfonos de tipo Casa u Oficina

|Código de Pais|Codigo de provincia|Provincia|
|---|---|---|
|+593|2|Pichincha, Santo Domingo de los Tsáchilas.|
|+593|3|Bolívar, Chimborazo, Cotopaxi, Pastaza, Tungurahua.|
|+593|4|Guayas, Santa Elena.|
|+593|5|Galápagos, Los Ríos, Manabí.|
|+593|6|Esmeraldas, Imbabura, Carchi, Napo, Orellana, Sucumbíos.|
|+593|7|Azuay, Cañar, El Oro, Loja, Morona Santiago2 y Zamora Chinchipe.|

##2 Módulo.

Para acceder al módulo de Cliente Despacho se debe ingresar al software
ENIGMA y dar clic sobre el menú principal, Bodega, y finalmente en
Cliente Despacho como lo indica la imagen.

<center>![](/bodega/cliente_despacho/resources/ingreso_modulo.png)</center>

### 2.1 Ventana Inicial.

La ventana de Cliente despacho se visualizará de la siguiente manera:

<center>![](/bodega/cliente_despacho/resources/general.png)</center>

1.  Listado de Clientes Activos.
2.  Datos generales del cliente seleccionado: Código, Nombre, Vendedor,
    Zona.
3.  Cuadro de búsqueda se puede ingresar referencias del nombre o
    apellido del cliente, presionar buscar para ejecutar la búsqueda o
    vaciar para limpiar el cuadro de búsqueda.
4.  Direcciones, teléfonos y transportes del cliente

### 2.2 Agregar o Modificar Dirección, número de Teléfono y Transporte.

#### 2.2.1 Selección Cliente.

<center>![](/bodega/cliente_despacho/resources/seleccion.png)</center>

1.  Seleccionamos el cliente al que deseamos agregar o modificar
    direcciones y teléfonos.
2.  Bara de Dirección y teléfono, si queremos ver direcciones damos un
    clic y se visualiza las direcciones, de igual manera con los números
    telefónicos.
3.  Listado de direcciones del cliente seleccionado
4.  Listado de números telefónicos del cliente seleccionado
5.  listado de transportes aquí se podrá visualizar el transporte
    predeterminado marcado con un check

!!!Nota
    Por cada cliente seleccionado automáticamente se actualiza los listados de teléfonos y direcciones.

#### 2.2.2 Cambio de Direcciones.

La información se debe llenar de la siguiente manera.

<center>![](/bodega/cliente_despacho/resources/descripcion_direccion.png)</center>

1.  Seleccionar dirección que se desea modificar.
2.  Información de la dirección seleccionada. Aquí se realizarán los
    cambios necesarios.
3.  Botón para guardar los cambios realizados.
4.  Botón para crear una nueva dirección.
5.  Parroquia Seleccionada, para ingresar la parroquia se debe dar clic
    sobre el recuadro. Se abrirá una ventana para realizar la selección.
6.  Ventana de parroquia. Tenemos un listado en el cual se va ir
    desplegando según su selección, la categorización esta Provincia,
    Cantón y parroquia
7.  Botón para predeterminar la dirección, se debe seleccionar una
    dirección y dar clic en este botón así se predeterminará la
    dirección.

!!!Danger
    Es obligatorio seleccionar una parroquia, en caso de seleccionar una provincia o cantón en recuadro de parroquia se pondrá en blanco lo cual no dejará guardar la dirección.

!!!Nota
    -   Si se guarda correctamente se visualizará el siguiente mensaje, caso
    contrario nos indicará el posible error.

<center>![](/bodega/cliente_despacho/resources/guardar_ok.png)</center>

-   Una vez guardado para verificar seleccionado.

!!!Nota
    Para agregar una nueva dirección el proceso es el mismo, solo presionamos el botón nuevo (Punto 4) y a continuación se llenará las descripciones de direcciones, la parroquia y marcar si la dirección es o no predeterminado.

#### 2.2.3 Cambio de Teléfono.

La información se debe llenar de la siguiente manera.

<center>![](/bodega/cliente_despacho/resources/modificar_telefono.png)</center>

1.  Seleccionar el teléfono que se desea modificar.
2.  Información del teléfono seleccionada. Aquí se realizarán los
    cambios necesarios de \# de teléfono, Tipo de teléfono.
3.  Botón para guardar un teléfono nuevo o modificado.
4.  Botón para crear un nuevo teléfono.
5.  Listado de tipos de teléfono, se debe seleccionar un tipo

!!!Danger
    -   Ingresar números telefónicos sin el 0.
    -   Para teléfonos de casa u oficina agregar el código provincial.

!!!Note
    -   Si se guarda correctamente se visualizará el siguiente mensaje, caso contrario nos indicará el posible error.
        <center>![](/bodega/cliente_despacho/resources/guardar_ok.png)</center>
    -   Una vez guardado verificar los cambios.

#### 2.2.3 Predeterminar un transporte.
-   Se listan todos los transportes por los cuales la empresa realiza
    envíos.

<center>![](/bodega/cliente_despacho/resources/predeterminar_transporte.png)</center>

1.  Seleccionar el transporte al cual vamos a predeterminar.
2.  Boton para predeterminar el transporte. Damos clic y nos marcara
    como predeterminado el transpote seleccionado.
