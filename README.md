# Practica-de-C-y-QT-creator
Empezando a aprender como hacer una interfase visual y poder terminar el crud en C++ que empecé hace semanas. 

La idea fue usar el framework mas facil y con menos requerimientos para mi notebook. Elegi QT creator, muy amigable y no pesa chiquicientos mil megas como Visual Studio. El plan era aprender la logica del framework y como funciona haciendo una ventana de holamundo! con un label, un cuadro de dialogo para ingreso de datos, un boton de evento y una salida de datos.

use como referencia este video maravilloso en castellano: https://www.youtube.com/watch?v=cnFItSiEJTU

Todo usando C++, que es el lenguaje en el que estoy escribiendo mi crud (lo tengo a medio hacer en otro repositorio) con persistencia en archivos.

Qt es muy facil de usar peeero tiene un punto choto, primero tiene todos los nombres cambiados y lo otro es que para hacer el "release" de tu aplicacion si queres usar un programa 
como "Dependency walker" y empaquetarle todas las dependencias, dll y porquerias que le haga falta para funcionar... te volves loco. Por alguna razon hay un revoltijo de versiones x86 y x64 y donde tengas un archivo cambiado cagaste.
La solucion (cuando no!) fue visitar la documentacion de QT y usar el metodo ortodoxo para hacer el "deploy" del programa. Que es basicamente abrir el CMD que trae built-in Qt dentro de sus ejecutables, en el navegar hasta el directorio de tu proyecto, borrar los archivos de la carpeta "debug" menos el ejecutable de tu proyecto (podes hacerlo antes desde el explorer) y lanzar el comando "windeployqt.exe --quick" y magia! te agrega todas las dependencias para que tu proyecto quede autonomo como lo explican en este video: https://www.youtube.com/watch?v=8qozxqSZQEg unos amigos rusos.

Muchos diran que es un tonteria poner acá un Holamundo! peero mi perfil, mis reglas jaja. Para mi esto es un hobby y todo es un hito en mi aprendizaje.

