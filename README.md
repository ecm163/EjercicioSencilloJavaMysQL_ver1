# EjercicioSencilloJavaMysQL_ver1

Ejercicio sencillo para practicar acceso a base de datos mediante Java e instrucciones MySQL, así como interfaces gráficos. 
En ésta versión se usa radio-buttons (además de tex fields, labbels, buttons... que ya se usaron en la versión anterior). 
Hecho por ecm163.

El programa en Java está desarrollado con NetBeans.

La base de datos -llamada sistema- es de tipo localhost.
Para realizarla usé mediante XAMPP el phpmyadmin (la dirección http://localhost/phpmyadmin/ en un navegador, y aparte el 
XAMPP Control Panel abierto con el Apache y MySQL iniciados).

El puerto es en mi caso el habitual, el 3306.

La base de datos que yo cree se llama 'sistema', y dentro de ella cree una tabla (con la que trabaja el programa) llamada 'usuario'.
La tabla usuario tiene 5 columnas: Id, Nombre, Apellidos, Edad, Correo.

Para acceder a la base de datos y su tabla yo tengo de nombre de usuario simplemente 'root' y no puse contraseña.

Si desea probarlo con otro puerto (si no es el habitual 3306 para MySQL) y con otro nombre de base de datos, tabla, usuario o contraseña,
tendrá que ir al paquete del programa 'modelo', luego a su clase 'Modelo', y ahí en el método 'Conexion()' hacer las modificaciones 
pertinentes.

Un saludo.
