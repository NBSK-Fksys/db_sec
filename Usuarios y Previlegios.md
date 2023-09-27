# **Oracle:**

SYSDBA: Este es el rol más alto en Oracle y tiene acceso completo a todas las funciones y datos del sistema, incluyendo la capacidad de crear, modificar y eliminar cualquier objeto en la base de datos.

DBA: El rol de DBA (Database Administrator) tiene privilegios administrativos en la base de datos, pero no tiene todos los privilegios de SYSDBA. Puede realizar tareas de administración como crear tablas, gestionar usuarios y realizar copias de seguridad.

CONNECT: Este rol permite a los usuarios conectarse a la base de datos y ejecutar consultas. No tiene muchos privilegios adicionales más allá de la capacidad de conectarse.

RESOURCE: Este rol proporciona algunos privilegios adicionales para crear objetos en la base de datos, como tablas y procedimientos almacenados.

SELECT ANY TABLE: Permite a los usuarios seleccionar datos de cualquier tabla en la base de datos, independientemente de si son propietarios de la tabla.

INSERT, UPDATE, DELETE: Estos son privilegios que permiten a los usuarios realizar operaciones específicas en las tablas, como insertar, actualizar o eliminar registros.

# **SQL Server:**

sysadmin: Similar al rol SYSDBA de Oracle, los miembros de este rol tienen control total sobre la instancia de SQL Server y pueden realizar cualquier acción en ella.

db_owner: Los usuarios con este rol tienen control total sobre una base de datos específica, incluyendo la capacidad de crear, modificar y eliminar objetos en esa base de datos.

db_datareader y db_datawriter: Estos roles permiten a los usuarios leer y escribir datos en una base de datos específica, respectivamente.

db_executor: Permite a los usuarios ejecutar procedimientos almacenados y funciones en una base de datos.

public: Todos los usuarios son miembros de este rol de forma predeterminada y tienen ciertos permisos básicos.

# **MySQL:**

SUPER: Este rol es similar al de SYSDBA en Oracle y sysadmin en SQL Server. Los usuarios con este rol tienen control total sobre el servidor MySQL.

CREATE, ALTER, DROP: Estos roles permiten a los usuarios crear, modificar y eliminar bases de datos y tablas.

SELECT, INSERT, UPDATE, DELETE: Estos roles otorgan permisos para realizar operaciones de lectura, inserción, actualización y eliminación en tablas específicas.

GRANT OPTION: Permite a los usuarios otorgar permisos a otros usuarios.

EXECUTE: Permite a los usuarios ejecutar procedimientos almacenados y funciones.