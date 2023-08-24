**Para ejecutar el servidor**
mvn clean package && mvn exec:java -Dexec.mainClass="org.example.Main"

Los servicios son /movies y el default es la página con el formulario
Para extenderlo se podrían añadir nuevas rutas con if y nuevos controladores. Si se necesitan nuevos tipos de request se pueden agregar a la clase Request.
