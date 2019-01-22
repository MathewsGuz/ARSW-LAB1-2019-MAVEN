# ARSW-LAB1-2019-MAVEN

Create a new maven project using the command mvn archetype:generate -B -DgroupId=edu.eci -DartifactId=file-spy, take screenshots.

![](lab1arsw.PNG)

What do means the -B option in the command?

 -B,--batch-mode , Ejecutar en modo no interactivo (por lotes) (desactiva el color de salida)

What do means the -D option in the command?

 -D,--define <arg> , Definir una propiedad del sistema.

What do means the groupId, artifactId properties in the command?

 - groupId: Identifica de forma única su proyecto.
 - artifactId: Es el nombre del JAR sin versión,que se despliega en un repositorio de Maven.
 
Describe the content of the directory that has been created.

 - Posee una carpeta Src donde encontraremos el código java principal , la cual es una clase llamada App y al mismo nivel de Src está la carpet Test


What do means the word SNAPSHOT in the version value?

<version>1.0-SNAPSHOT</version>
 - Es un tipo de versión la cual hace referencia a un trabajo en progreso



What is the purpose of the packing tag into the POM file?

 - indica de qué forma el proyecto será empaquetado, de no especificarse se asume que será con de la forma Jar.


What is the purpose of the dependencies and dependency tags into the POM file?

 - Son utilizadas para que el Proyecto pueda hacer uso de estas sin tener la necesidad de descargar más librerías en un jar.

What is the functionality of this class?

 - La clase fly spy al crearse un archivo con extensión csv en una carpeta específica que se está vigilando, anuncia el nombre del archivo que fue creado.

The three principal Maven lifecycles are clean, defaultand site. Describe each one.

 - default: maneja la implementación del proyecto.
 - clean: se encarga de la limpieza del proyecto
 - El ciclo de vida del site maneja la creación de la documentación del sitio de su proyecto.

Using the terminal execute the command mvn compile. Take the output screenshot. What is this command using for? What are transitive dependencies?

- compila el código fuente del proyecto

 ![](mvncompile.PNG)

Using the terminal execute the command mvn package. Take the output screenshot. What is this command using for?

- toma el código compilado y lo guarda en su formato, como un JAR.

![](mvnpackage.PNG)

Using the terminal execute the command mvn install. Take the output screenshot. What is this command using for?

 - instala el paquete en el repositorio local, para usarlo como una dependencia en otros proyectos a nivel local.
 
 ![](mvninstall.PNG)
 
Generate a new maven project in other folder using the maven command line tools, this project should has as groupId "edu.eci" and as artifactId "another-maven-project". Take the output screenshot.

![](another-mvn-pro2.PNG)
