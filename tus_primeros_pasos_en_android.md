## Tus primeros pasos en Android

### ¿Porqué Android Nativo?
- React tiene que generar código para representar lo que estamos escribiendo en Javascript o Typescript. Eso nos quita algo de control sobre cómo queremos desarrollar nuestra aplicación.
- Y luego esta el problema de la compatibilidad. Android saca una nueva versión cada año. En la mayoría de los casos, implica un cambio en el hardware (como una versión nueva de la cámara que maneje una perspectiva 3D).
- Cuando Google saca una nueva versión de su sistema operativo, lanza un SDK (Software Development Kit). Esto es un conjunto de herramientas que nos permite trabajar con las nuevas funcionalidades de ese sistema.
Y React, conjunto de los demás frameworks, tiene que lanzar un soporte específico para cada nuevo SDK. En el caso de los programadores nativos, trabajos directamente con el que nos provee Google.

React es muy bueno, su soporte también. Si tu objetivo es trabajar independiente en aplicaciones que no involucren un manejo de hardware muy específico, te va a funcionar sin problemas.
Pero por ejemplo, no confiaría a React una aplicación de reconocimiento facial. Prefiero crear una con Android que trabaje con un Bridge en C o C++ con OpenCV.

Resumiendo: Programar Android nativo nos pone al frente de todo lo nuevo que vaya saliendo. Y no nos limitemos a móviles, también tenemos Android TV, Android Wear, Android Auto, entre otros.

* Android: Java o Kotlin.
* React: Javascript o Typescript.

### Antes de empezar:
- [Cómo aprender a programar desde cero?](https://medium.com/@maxwellnewage/como-aprender-a-programar-desde-cero-ac8f05a0da07)
- [Udemy: Android desde cero](https://www.udemy.com/course/aprende-a-desarrollar-aplicaciones-android-desde-cero/?referralCode=0B03BB2E354F8EBC83DD)

### Herramientas indespensables:
- [Intellij](https://www.jetbrains.com/es-es/idea/): Con este IDE vas a poder correr aplicaciones en Java. Con la versión Community te alcanza.
- [Android Studio](https://developer.android.com/studio): Es fundamental. Con este IDE vas a correr aplicaciones en Android. La instalación ya viene con el SDK incluido.
- [JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html): Es el kit de desarrollo de Java. Cualquier versión de la 8 o superior te sirve.
- [Visual Studio Code](https://code.visualstudio.com/): Esto podría ser opcional. Se trata de un editor de código creado por Microsoft. El más famoso hasta la fecha. A veces puede que necesites editar un archivo puntual y no quieras abrir un IDE.
- Windows, Linux o Mac: Android se puede desarrollar en cualquiera de estos sistemas operativos. Aunque la instalación en Linux puede ser un poco más compleja.
- Disco SSD: Un disco sólido, indispensable. Android Studio accede al disco constantemente, por lo que tener una velocidad buena te va a beneficiar en muchos aspectos, especialmente en la compilación.
- 8GB de RAM: Es lo recomendable. Lo mínimo sería cuatro.
- Café, Mate o Té: Cualquier cosa que te mantenga despierto por muchas horas. Probablemente el requisito mas importante :)

### Aprender Java:
- Si leen por ahí que Java está muriendo, no se preocupen: No es así. Esto lo digo con seguridad porque Java es un lenguaje multiplataforma. Hoy día muchos bancos confían su sistema a Java Spring (un framework de desarrollo web y APIs).
- Minecraft esta desarrollado en Java y siguen lanzando actualizaciones, aunque muchos estemos de acuerdo que la optimización es un tema complejo de tratar. [Minecraft Plugins con Spigot](https://medium.com/@maxwellnewage/diario-de-un-desarrollador-1-minecraft-plugins-con-spigot-d2c79942b0cf)
- También se han desarrollado muchas aplicaciones para escritorio, aunque en este caso yo me inclino más por usar Electron, una librería de interfaces visuales usando Javascript.

1. Es fundamental entender que Java corre en una JVM (Java Virtual Machine), que viene a ser una máquina virtual con su propio entorno para correr sus aplicaciones.
1. Otra particularidad es que Java soporta el paradigma de programación orientada a objetos, estructurada, funcional y reactiva. Por lo tanto, es un lenguaje multiparadigma que se va a adecuar a nuestras necesidades.

#### Cursos:
- [Píldoras Informáticas](https://www.youtube.com/watch?list=PLU8oAlHdN5BktAXdEVCLUYzvDyqRQJ2lk&v=coK4jM5wvko)
- [freeCodeCamp](https://www.youtube.com/watch?v=grEKMHGYyns)
- [libros O'Reilly](https://www.oreilly.com/search/?query=java&extended_publisher_data=true&highlight=true&include_assessments=false&include_case_studies=true&include_courses=true&include_orioles=true&include_playlists=true&include_collections=true&include_notebooks=true&is_academic_institution_account=false&source=user&sort=relevance&facet_json=true&page=0)
