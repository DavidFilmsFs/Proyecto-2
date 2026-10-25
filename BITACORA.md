Preguntas para la bitácora de decisiones

¿Por qué usar un id único en lugar de identificar al personaje por su nombre? ¿Qué pasaría si dos personajes se llaman igual?
Crear un id único para cada personaje nos permite que a la hora de buscar al personaje, no haya errores y se agarre otro personaje que no corresponde y al ser un ID único nos permite que en caso de que haya nombres repetido sde personajes, tengamos la posibilidad de poder elegir el personaje que estamos queriendo elegir y no otro.  

¿Conviene guardar todo el arreglo en una sola clave de localStorage o un personaje por clave? Compara ventajas y desventajas. 
Para esta aplicación, conviene guardar todo el arreglo en una sola clave, porque la lista de personajes es pequeña y las acciones trabajan sobre la colección completa.
Si es en una sola clave leer y guardar toda la lista es directo; agregar, editar y eliminar usan operaciones normales de arreglos.
Mientras que que un personaje por clave Permite actualizar o borrar un personaje individual sin reescribir los demás Y se tiene que modificar uno por uno haciéndolo una actividad tediosa.

¿Se debe permitir guardar un personaje con nombre solo de espacios en blanco? ¿Y uno duplicado? Reflexión crítica sobre la tecnología 
Opino que no, ya que ocasiona un conflicto debido a la sintaxis, debido a que esos espacios y lo que está duplicado puede confundir diferentes valores ya establecidos previamente, haciendo que el programa no sepa cual poner o si no duplicar ambos resultados.

¿Es seguro guardar información sensible en localStorage? ¿Quién más puede leerla? ¿Qué datos nunca guardarías ahí? 
No, ya que todos los que tengan acceso al dispositivo pueden ver lo que se almacena y en caso de que alguien acceda va a poder ver información privada y lo que nunca se debería poner son identificaciones, cuentas bancarias, contraseñas, etc..

Tu aplicación vive en GitHub Pages. Si un compañero abre tu URL, ¿verá tus personajes? Explica por qué y qué implica para el diseño de la aplicación. Reto de diseño 
En GitHub Pages, todos ven los personajes iniciales publicados en el código, pero los cambios guardados en localStorage solo están en el navegador donde se hicieron; no se comparten con los compañeros. Como la app no tiene servidor y la tarea pide usar solo localStorage, está diseñada para guardar cambios localmente, no para sincronizarlos entre usuarios.
