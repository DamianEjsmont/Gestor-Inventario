# Gestor-Inventario

//instalar la libreria:
 mysql-connector-java-5.1.48-bin.jar
 
 //paso a seguir para lograr el funcionamiento del programa:
 
//importante editar la siguiente linea dentro archivo Conexion.java para lograr la conexión sin problemas:

con=DriverManager.getConnection("jdbc:mysql://localhost:3306/inventario","su usuario o root","su contraseña");

//la Base de datos se debe llamar "inventario", al igual que en el archivo conexión. 
