

Lanzamiento de GitHub Estado de construcción codecov Insignia de Codacy JitPack Desbordamiento de pila Licencia BSD Gorjeo Contribuya a contribuir al código abierto

Queremos inspirar al mundo a crear. Usar habilidades tecnológicas y construir algo realmente ... Impresionante. Hermosa. Servicial. Impactante. Ahora puede producir código ligero y concentrarse en liberar todo su potencial. Jodd es un conjunto de micro-frameworks Java de código abierto y fáciles de usar para desarrolladores. Está diseñado para simplificar las cosas, pero no más.

Sitio web oficial (sitio y documentación): https://jodd.org
Micro-frameworks Jodd (descripción general de 30 minutos): https://joddframework.org
Habla con Jodd a través de gitter o slack .
Jodd = herramientas + ioc + mvc + db + aop + tx + json + html <1.7 Mb
⚡ Jodd
Jodd es un conjunto de micro-frameworks y herramientas y utilidades amigables para desarrolladores.

Usa lo que te gusta.

Bibliotecas geniales :

jodd-json - Analizador y serializador JSON.
jodd-lagarto- Analizador HTML con etiqueta Jerryy CSSellyy Form.
jodd-http - pequeño cliente HTTP.
jodd-mail - para un envío de correo electrónico más sencillo.
Micro-marcos :

jodd-madvoc - elegante marco MVC.
jodd-petite - contenedor DI pragmático.
jodd-proxetta- proxies dinámicos y Paramo.
jodd-db - capa fina de base de datos y mapeador de objetos.
jodd-jtx - gestión de transacciones.
Herramientas menos utilizadas :

jodd-decora - decorador de páginas.
jodd-htmlstapler - manejador de recursos de páginas estáticas.
jodd-vtor - marco de validación.
Paquete de pila completa :

jodd-joy- Marco de aplicación súper fácil, construido con micro-marcos de Jodd .
Utilidades :

jodd-core - contiene muchas utilidades diarias.
jodd-bean- nuestros infames BeanUtilinspectores de tipo y convertidores.
jodd-props- es el súper reemplazo de Java Properties.
jodd-servlet - con muchas utilidades de servlet, incluida una bonita biblioteca de etiquetas.
Leer más en nuestra documentación oficial .

: octocat: Construyendo Jodd desde la fuente
Jodd está construido con Gradle en JDK8, dirigido a Java 1.8. No tiene que instalar nada, los únicos requisitos previos son Git y Java JDK.

Ver fuentes
Simplemente clone el repositorio de Jodd Git:

git clone https://github.com/oblac/jodd.git jodd
Compila y prueba, construye frascos
Puede construir el proyecto Jodd con:

gradlew build
Esto creará todos los frascos y ejecutará todas las pruebas unitarias. Para omitir las pruebas (para una compilación más rápida), ejecute:

gradlew build -x test
Cree una versión completa con informes
Para generar una versión completa , incluida la ejecución de pruebas de integración y la generación de varios informes, necesita Docker v1.12 +.

docker-compose -f etc/docker-compose.yml up
gradlew clean release
Las pruebas de integración requieren cierta infraestructura (como bases de datos), por lo que se utiliza Docker.

Instale Jodd en su Maven local
gradlew install
💝 Contribuir
¡Siéntete libre de contribuir ! Sigue estos pasos:

Solo primera vez:

tenedor del Jodd repo ( upstream) a su cuenta de GitHub ( origin)
clonar origincomo su localrepositorio
instalar el complemento ZenHub para realizar un seguimiento de las tareas
Cada dos veces:

actualizar ambos originy localrepositorios deupstream
crear una nueva rama para una función o corrección de errores
cometer a menudo :)
Una vez que haya terminado el trabajo, introduzca cambios locales en su origin
envíanos una solicitud de extracción (PR)
Lo recogeremos desde allí :)

🚀
