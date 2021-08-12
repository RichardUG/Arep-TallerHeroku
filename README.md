# Taller Heroku

>Taller de repaso de Heroku, que a la vez nos enseña el uso del framework ```Spark web```, ademas nos brinda un repaso del manejo de repositorios remotos, tanto en git como en heroku y nos explica el despliegue de heroku desde linea de comandos a través de ```Heroku CLI```

### Pre-requisitos

> Para  elaborar este proyecto requeimos de dos tecnologias:
> * [Maven](https://es.wikipedia.org/wiki/Maven): Herramienta la cual permite realizar la construción de proyectos, realizarles pruebas y otras funciones.
> * [Git](https://es.wikipedia.org/wiki/Git): Software de control de versionamiento centralizado.
> * [Heroku](https://es.wikipedia.org/wiki/Heroku): Heroku es una plataforma como servicio (PaaS) de computación en la Nube que soporta distintos lenguajes de programación.

Para asegurar que el usuario cumple con todos los prerrequisitos para poder ejecutar el programa, es necesario disponer de un Shell o Símbolo del Sistema para ejecutar los siguientes comandos para comprobar que todos los programas están instalados correctamente, para así compilar y ejecutar tanto las pruebas como el programa correctamente.

```
mvn -version
git --version
java -version
```


### Ejecución del proyecto desde linea de comandos
> ### Instalación
>
> Clonamos este repositario desde ```cmd```, con el siguiente comando
>
> ```
> git clone https://github.com/RichardUG/Arep-TallerHeroku
> ```
>
> Si nos encontramos en un dispositivo ```linux``` nos dirigimos al archivo ```procfile``` y reemplazamos el contenido por el siguiente texto
> ```
> web: java $JAVA_OPTS -cp 'target/classes:target/dependency/*' edu.escuelaing.arep.designprimer.SparkWebApp
> ```
> 
> Si nos encontramos en un dispositivo ```windows``` nos dirigimos al archivo procfile y reemplazamos el contenido por el siguiente texto
> ```
> web: java -cp target/classes;target/dependency/* edu.escuelaing.arep.designprimer.SparkWebApp
> ```


Despues de ejecutarlo saldra este texto, el cual indica que las pruebas que se ejecutaron al interior del programa, fueron ejecutadas de manera exitosa.
![img](img/testpackage.PNG)


## Construido con

* [Maven](https://es.wikipedia.org/wiki/Maven): Herramienta la cual permite realizar la construción de proyectos, realizarles pruebas y otras funciones.
* [Git](https://es.wikipedia.org/wiki/Git): Software de control de versionamiento centralizado.
* [Heroku](https://es.wikipedia.org/wiki/Heroku): Heroku es una plataforma como servicio (PaaS) de computación en la Nube que soporta distintos lenguajes de programación.
* [Intelij](https://es.wikipedia.org/wiki/IntelliJ_IDEA): es un entorno de desarrollo integrado (IDE) para el desarrollo de programas informáticos. Es desarrollado por JetBrains, y está disponible en dos ediciones: edición para la comunidad1 y edición comercial.
* [Java](https://www.oracle.com/java/): Lenguaje de programación de propósito general, es decir, que sirve para muchas cosas, para web, servidores, aplicaciones móviles, entre otros. Java también es un lenguaje orientado a objetos, y con un fuerte tipado de variables.

## Autor
[Richard Santiago Urrea Garcia](https://github.com/RichardUG)

## Licencia & Derechos de Autor
**©** Richard Santiago Urrea Garcia, Estudiante de Ingeniería de Sistemas de la Escuela Colombiana de Ingeniería Julio Garavito

Licencia bajo la [GNU General Public License](https://github.com/RichardUG/Arep-IntroduccionMvnGit/blob/main/License).
