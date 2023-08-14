# ComandosMySQL
Para iniciar sesion en MySQL
mysql -u  [user] -p



# El lenguaje SQL consta de varios comandos, los cuales son:

• DDL (Data Definition Language): Este comando es utilizado para definir y modificar la estructura de la base de
datos. Incluye comandos como CREATE, ALTER y DROP para crear, modificar y eliminar tablas,
índices, vistas, etc.


• DML (Data Manipulation Language): Este comando es utilizado para manipular los datos almacenados en la
base de datos. Incluye comandos como INSERT, UPDATE y DELETE para agregar, actualizar y
eliminar registros.


• DQL (Data Query Language): Este comando es utilizado para realizar consultas y recuperar información de la
base de datos. El comando más común es SELECT, que permite especificar los criterios de
búsqueda y los campos a recuperar.


• DCL (Data Control Language): Este comando es utilizado para controlar los privilegios de acceso a la base de
datos. Incluye comandos como GRANT y REVOKE para otorgar y revocar permisos.


# Comandos de DDL
en SQL se utilizan para definir, modificar y eliminar la
estructura de la base de datos. Estos comandos permiten crear tablas, definir restricciones, modificar
la estructura de las tablas existentes y eliminar objetos de la base de datos.

*COMANDOS*

- SHOW DATABASE : Este comando permite pedirle al sistema que te muestre los nombres de todas las carpetas o contenedores donde se almacenan los datos.

- CREATE DATABASE : Es como crear una carpeta nueva para guardar archivos, pero en el mundo de las bases de datos. Se le Puede dar un nombre único a esta nueva "carpeta" para luego guardar y administrar tus datos de manera separada de otras bases de datos existentes.

- DROP DATABASE: Se usa para eliminar completamente una base de datos y toda la información que contiene. Es como borrar una carpeta y todos los archivos que hay dentro de ella. Este comando es útil cuando ya no necesitas esa base de datos o cuando deseas eliminar datos que ya no son relevantes o están ocupando espacio innecesario. 

- USE: Es como decirle al sistema que quieres trabajar dentro de una carpeta en particular, en lugar de estar en la carpeta principal.

- CREATE TABLE : Permite crear una tabla en la base de datos seleccionada con el comando USE.
    
    *EJEMPLO*
    CREATE TABLE nombre_tabla(
        column1 datatype,
        column2 datatype,
        column3 datatype,
        ....
    );

- SHOW TABLES: Este comando se utliza para visualizar las tablas que se encuentran creadas en la base de datos. Es como ver la lista de páginas en un libro

- DESCRIBE nombre_tabla: Este comando se utiliza para visualizar la estructura de una tabla creada en la base de datos. Te muestra detalles sobre los nombres de las columnas, los tipos de datos que pueden contener y otras características importantes de la estructura de la tabla.

- ALTER TABLE: Permite modificar la estructura de una tabla existente en la base de datos.

- ADD: Se utiliza para poner algo nuevo en algún lugar donde ya existen cosas. Es como si añadieras una nueva columna en una hoja de cálculo para guardar más detalles.
    
    *EJEMPLO*
    ALTER TABLE nombre_tabla
    ADD nombre_columna datatype;

    Teniendo en cuenta el ejercicio anterior note que hicieron falta crear dos columnas una el email y
    otra la fecha de nacimiento. En este caso utilizaremos alter table para realizar la creación de estas
    columnas faltantes.

    *ALTER TABLE nombre_tabla ADD nombre_tabla_faltante varchar (100)*


- DROP COLUMN: Comando para eliminar columnas 

    *EJEMPLO*
    ALTER TABLE nombre_tabla
    DROP COLUMN: nombre_columna;

- RENAME COLUMN: Comando para renombrar una columna

    *EJEMPLO*
    ALTER TABLE nombre_tabla
    RENAME COLUMN: antiguo_nombre to nuevo_nombre;

- MODIFY COLUMN: Comando para modificar el tipo de dato

    *EJEMPLO*
    ALTER TABLE nombre_tabla
    MODIFY COLUMN nombre_columna datatype;




 








#
