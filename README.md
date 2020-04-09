# subidas de archivos
rest-service-0.0.1-SNAPSHOT es un microservicio con un controlador, hecho en spring-boot, que se puede ejecutar desde consola, y consultarse desde el browser.

### Para ejecutarlo, (spring-boot ya levanta un servidor Tomcat)
```java -jar rest-service-0.0.1-SNAPSHOT.jar```
### Para consultarlo desde el navegador
http://localhost:8080/greeting?name=antonio   o sin el parametro name.   http://localhost:8080/greeting 
### Crear *.java a partir de *.class se usa un decompilador, como fernflower usado por idea.
```java -cp "rutaDecompilador.jar" rutaMetodoMaindentroDecompilador.jar -dgs=true rutaJarAdecompilar rutaDestino```
Ejemplo:
```java -cp "C:\lib\decompilar.jar" com.paqueteUno.ClaseMain -dgs=true . C:\```
