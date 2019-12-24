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
