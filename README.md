# CRUD-SpringBoot
Este es CRUD realizado en en Java con SpringBoot EL backend esta realizado completamente por mi, utilice el SBD Admin 2 para el frontend, solo el html y css, utilice funciones en javascript estas las realice yo. 
Dependencias utilizadas 
*Java 11
*Thymeleaf 
*Spring Web 
*JDBC *h2DataBase
*SpringData JPA (Hibernate)
*My SQL conector 
*Lombock 
*Argon2 
Si desea ejecutar el el proyecto debe hacer en una version de java 11 en adelante, y para la base de datos es necesario la conexion a traves de PHP my admmin con XAMMP. 
Tambien utilice la dependencia de Argon2 para encriptar las contraseñas de usuario. Debe crear una base de datos llamada "bd_crud",
y crear una tabla con el nombre "usuarios", esta debe tener los campos de "nombre, apellido, telefono, email, contraseña y por su puesto el id",
como se deja en claro debes darle un tamaño de 255 a la contraseña para que funcione corrctamente el hash con Argon2.
