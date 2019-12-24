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
1. Es fundamental entender que Java corre en una JVM (Java Virtual Machine), que viene a ser una máquina virtual con su propio entorno para correr sus aplicaciones.
1. Otra particularidad es que Java soporta el paradigma de programación orientada a objetos, estructurada, funcional y reactiva. Por lo tanto, es un lenguaje multiparadigma que se va a adecuar a nuestras necesidades.

- Si leen por ahí que Java está muriendo, no se preocupen: No es así. Esto lo digo con seguridad porque Java es un lenguaje multiplataforma. Hoy día muchos bancos confían su sistema a Java Spring (un framework de desarrollo web y APIs).
- Minecraft esta desarrollado en Java y siguen lanzando actualizaciones, aunque muchos estemos de acuerdo que la optimización es un tema complejo de tratar. [Minecraft Plugins con Spigot](https://medium.com/@maxwellnewage/diario-de-un-desarrollador-1-minecraft-plugins-con-spigot-d2c79942b0cf)
- También se han desarrollado muchas aplicaciones para escritorio, aunque en este caso yo me inclino más por usar Electron, una librería de interfaces visuales usando Javascript.
- Cursos:
    - [Píldoras Informáticas](https://www.youtube.com/watch?list=PLU8oAlHdN5BktAXdEVCLUYzvDyqRQJ2lk&v=coK4jM5wvko)
    - [freeCodeCamp](https://www.youtube.com/watch?v=grEKMHGYyns)
    - [libros O'Reilly](https://www.oreilly.com/search/?query=java&extended_publisher_data=true&highlight=true&include_assessments=false&include_case_studies=true&include_courses=true&include_orioles=true&include_playlists=true&include_collections=true&include_notebooks=true&is_academic_institution_account=false&source=user&sort=relevance&facet_json=true&page=0)

### Aprender lo más básico de Android:
- Android, si bien es llamado un lenguaje de programación, en realidad es un SDK de Java.
- Entonces podríamos decir que Android es un conjunto de librerías que contienen super clases, las cuales nos permiten heredarlas y convertir nuestras clases Java en componentes de una aplicación en Android.

Es importante que aprendas lo básico e indispensable, pero que todavía no te centres en lo avanzado. Con poder crear un “Hola mundo” y verlo desde tu celular o emulador, es suficiente.
- [Documentación oficial de Google](https://developer.android.com/?hl=es-419)
- [TUTORIALES](https://developer.android.com/guide?hl=es-419)


### Se aprende haciendo:
1. Empezar con una idea:
   - Tienen que pensar que es lo que realmente quieren hacer con esto que están dedicando horas a ver vídeos y leer libros.
   - Parados en Android, podemos crear aplicaciones. Lo primero que deberías hacer es salir a la calle y detectar necesidades, sean tuyas o de otras personas.
   - No por estar aprendiendo vas a negarte a crear un producto.
1. Manos a la obra:
   - Consigue un trabajo mientras estudias, y no después.
       - Un trabajo te genera enfoques, porque hay gente que ya tiene una idea y necesita ejecutarla. Cuando te la transmite, ahí es donde notás si realmente aprendiste lo suficiente. La respuesta suele ser: no.
       - Porque los problemas reales son mucho más grandes y complejos que cualquier curso o tutorial. Pero esto no es un fallo de tu esquema de aprendizaje, al contrario, es parte del flujo.
   - El primer paso es que la app sea estéticamente aceptable. Tenemos que aprender los fundamentos de [Material Design](https://material.io/develop/android/)
       - Si tu app no responde a estos principios, podría no ser atractiva, y un producto entra por los ojos.
1. Marco de referencia:
   - Las ideas no suelen salir de la nada. Debemos investigar previamente apps similares a lo que intentamos hacer. De esta manera desarrollamos un marco de referencia, y aprendemos de los errores y aciertos de los ejemplos que estamos investigando.
1. MockUp:
   - Si bien aprendimos a maquetar una app, todavía no podemos diseñar nada si no sabemos como estructurarla. 
   - Una vez tenemos claras las pantallas, tomamos lapiz y papel y empezamos a dibujar un bosquejo del detalle de cada una. Unos botones, la lista, como se va a ver el detalle, la posición de los input de usuario y contraseña. Todo lo que nos defina la estructura en la que nos vamos a basar.
   - Esto es un MockUp. También hay herramientas web para hacerlo, pero recomiendo en primera instancia que sea a mano. Esto es un proceso psicológico, dado que con el lapiz tenemos mayores libertades, y nos podemos centrar en la idea más que en el uso de una herramienta.

Ahora llegó el momento de aprender más intensamente.

### Ampliar panorama:
1. Nuestra primer pantalla es el Login Social. Hay varias formas de hacer esto, pero la más popular en este momento es usar los servicios de Firebase.
   - [Integrar Firebase](https://firebase.google.com/docs/android/setup?hl=es-419)
   - [Implementar login social](https://firebase.google.com/docs/auth?hl=es-419)
1. Una vez el usuario ingresa a la app y llega a la pantalla principal, la home. Pero tenemos un problema: Aunque el usuario logre ingresar, en nuestro flujo actual siempre vamos a pedirle que ingrese cuando se reinicie la app.
   - [Persistir la Información: SharedPreferences de Android](https://developer.android.com/reference/android/content/SharedPreferences), la cual nos va a permitir mantener una sesión de usuario activa, incluso si se desinstalara la app (investigar allow backup para esto).
1. Algo que no consideramos es agregar una función de logout, quizá implementando un menú lateral con una opción que indique dicho comportamiento. 
   - [DrawerLayout](https://danielme.com/2018/12/19/diseno-android-menu-lateral-con-navigation-drawer/)
1. Desarrollo de una API: Lo que necesitamos para gestionar los datos de los bares, es una API que nos permita accederlos desde nuestra app en Android.
   - [Udemy: API's en Laravel](https://www.udemy.com/course/desarrollo-de-apis-y-sitios-web-con-laravel-php-de-cero/?referralCode=7F8CA581D96D4AC834FE)
   - [Artículos: Desarrollo de API con NodeJS](https://medium.com/@maxwellnewage/como-crear-una-api-con-express-y-nodejs-27adf2640a30)
   - [Cómo crear vistas en ExpressJS](https://medium.com/@maxwellnewage/como-crear-vistas-en-expressjs-59192ead65bb)
   - [Cómo enlazar vistas en Plug con ExpressJS](https://medium.com/@maxwellnewage/como-enlazar-vistas-en-pug-con-expressjs-157a1064b0e7)
1. Consumo de API: Una vez tenemos la API desarrollada, sea de terceros o nuestra, debemos consumirla a través de nuestra aplicación.
   - [Implementar Retrofit en nuestra App](https://medium.com/@maxwellnewage/como-implementar-retrofit-en-nuestra-app-6ba7cee6e0a5)
1. Representar la información en una lista con CardViews [Tutorial detallado](https://guides.codepath.com/android/using-the-recyclerview)
1. Dónde queda? [API de Google Maps](https://developers.google.com/maps/documentation/android-sdk/intro)
1. Crear una galeria de fotos [ViewPager](https://developer.android.com/training/animation/screen-slide). En el medio también aprenderemos a manejar Fragments, un componente de Android que nació con el surgimiento de las tabletas, si mal recuerdo en la versión 4.

### Finalmente:
- Nuestra pantalla de favoritos se podría manejar de dos maneras:
   - SharedPreferences: Guardamos la información de los bares favoritos localmente.
   - API: Guardamos la información en la API asociado a un id de usuario. Luego la recuperamos mediante algún método GET.

La primera forma puede ser compleja, dado que debemos guardar objetos, y SharedPreferences no lo soporta. Como alternativa, podemos usar la librería Gson que ya habíamos importado con Retrofit. Nuestro algoritmo sería:
   - Recibimos objeto lista.
   - Convertimos objeto en json string mediante Gson.
   - Guardamos json string en SharedPreferences.
   - Pedimos objeto json string.
   - Convertimos json string a objeto lista mediante Gson.
   - Recorremos la lista con nuestro Adapter del RecyclerView.

### Hay una motivación y un producto. Difícil detenernos, ¿no?
Si aprendemos sobre la marcha, podemos lograr adquirir lo que llamo “conocimiento inconsciente”. Aprendemos sin darnos cuenta, porque estamos poniéndolo a prueba y experimentando en un caso real.

Todo lo aprendido en este proyecto:
   - Fundamentos en Java y Android.
   - Tomar ejemplos como punto de partida para tu proyecto.
   - Cómo armar mocks.
   - Los principios de Material Design.
   - Consumo e implementación de APIs con Retrofit.
   - Listas con RecyclerViews y CardViews.
   - Galerías con ViewPager.
   - Geolocalización y mapeo con Google Maps API.
   - SharedPreferences para mantener sesiones. 
   - Manejo de Firebase.
   - Menus laterales con DrawerLayout.
   - Fragments.
   - Gson.

Y a todo esto deberíamos sumarle ciertas habilidades adquiridas con la gestión de un proyecto. :)

* [Fuente](https://medium.com/@maxwellnewage/diario-de-un-desarrollador-19-tus-primeros-pasos-en-android-c0796bc64d6c)
