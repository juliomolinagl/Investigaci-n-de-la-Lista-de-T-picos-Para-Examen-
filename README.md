# Investigaci-n-de-la-Lista-de-T-picos-Para-Examen-
Ciclo de vida de las variables

Variables Estáticas
En informática una variable estática es una variable que ha sido ubicada estáticamente y cuyo tiempo de vida se extiende durante toda la ejecución del programa. Normalmente una variable estática tiene un ámbito más amplio que otras variables. Los valores de variables estáticas se pueden establecer una vez (durante el tiempo de ejecución) o se pueden cambiar en múltiples ocasiones durante la ejecución del programa. La terminología "variable estática" se basa en C y C++, pero también se usa en muchos lenguajes de programación derivados. En lenguajes de diferente origen el mismo concepto puede denominarse "variable global".

Memoria Dinámica
La memoria dinámica se refiere a aquella memoria que no puede ser definida ya que no se conoce o no se tiene idea del número de la variable a considerarse, la solución a este problema es la memoria dinámica que permite solicitar memoria en tiempo de ejecución, por lo que cuanta más memoria se necesite, más se solicita al sistema operativo. El sistema operativo maneja la memoria gracias al uso de punteros, por la misma naturaleza del proceso nos impide conocer el tamaño de la memoria necesaria en el momento de compilar.
Un dato importante es que como tal este tipo de datos se crean y se destruyen mientras se ejecuta el programa y por lo tanto la estructura de datos se va dimensionando de forma precisa a los requerimientos del programa, evitándonos así perder datos o desperdiciar memoria si hubiéramos tratado de definir la cantidad de memoria a utilizar en el momento de compilar el programa.

Clase
En informática, una clase es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases se utilizan para representar entidades o conceptos, como los sustantivos en el lenguaje. Cada clase es un modelo que define un conjunto de variables el estado, y métodos apropiados para operar con dichos datos el comportamiento. Cada objeto creado a partir de la clase se denomina instancia de la clase.




Objeto
En el paradigma de programación orientada a objetos (POO, o bien OOP en inglés), un objeto es una unidad dentro de un programa de computadora que consta de un estado y de un comportamiento, que a su vez constan respectivamente de datos almacenados y de tareas realizables durante el tiempo de ejecución. Un objeto puede ser creado instanciando una clase, como ocurre en la programación orientada a objetos, o mediante escritura directa de código y la replicación otros objetos, como ocurre en la programación basada en prototipos.
Estos objetos interactúan unos con otros, en contraposición a la visión tradicional en la cual un programa es una colección de subrutinas (funciones o procedimientos), o simplemente una lista de instrucciones para el computador. Cada objeto es capaz de recibir mensajes, procesar datos y enviar mensajes a otros objetos de manera similar a un servicio.

Instanciación
La palabra instancia significa: solicitud o instancia.
Una instancia de un programa es una copia de una versión ejecutable del programa que ha sido escrito en la memoria del computador

una instancia de un programa es creada típicamente por el click del usuario en un icono de interfaz gráfico para usuario.

Herencia
En programación orientada a objetos, la herencia es, después de la agregación o composición, el mecanismo más utilizado para alcanzar algunos de los objetivos más preciados en el desarrollo de software como lo son la reutilización y la extensibilidad. A través de ella los diseñadores pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistente (ya comprobadas y verificadas) evitando con ello el rediseño, la modificación y verificación de la parte ya implementada. La herencia facilita la creación de objetos a partir de otros ya existentes e implica que una subclase obtiene todo el comportamiento (métodos) y eventualmente los atributos (variables) de su superclase.
Es la relación entre una clase general y otra clase más específica. Por ejemplo: Si declaramos una clase párrafo derivada de una clase texto, todos los métodos y variables asociadas con la clase texto, son automáticamente heredados por la subclase párrafo.



Sobrecarga
Es la capacidad de un lenguaje de programación, que permite nombrar con el mismo identificador diferentes variables u operaciones.
En programación orientada a objetos la sobrecarga se refiere a la posibilidad de tener dos o más funciones con el mismo nombre pero funcionalidad diferente. Es decir, dos o más funciones con el mismo nombre realizan acciones diferentes. El compilador usará una u otra dependiendo de los parámetros usados. A esto se llama también sobrecarga de funciones.
También existe la sobrecarga de operadores que al igual que con la sobrecarga de funciones se le da más de una implementación a un operador.
El mismo método dentro de una clase permite hacer cosas distintas en función de los parámetros.
Java no permite al programador implementar sus propios operadores sobrecargados, pero sí utilizar los predefinidos como el +. C++, por el contrario si permite hacerlo.

Shadowing
Se llama shadowing al hecho de que en una clase una variable miembro y una variable local definida en un método miembro, se llamen igual.

Ciclos de vida de las variables
 *Variables de instancia (u objeto):
- Se crean cuando se crea el objeto que las contiene. 
- Se inicializan por defecto si no se hace de modo explícito: • 0 para números, "false" para booleano, "null" para objetos. 
- Se destruyen cuando el recolector de basura de Java no encuentra referencias activas para el objeto. 

 *Variables estáticas (o de clase): 
– Se crean cuando la clase se usa por primera vez. 
– Se inicializan por defecto si no se hace de modo explícito: • 0 para números, "false" para booleano, "null" para objetos 
– Suelen existir para el resto del programa (salvo que no esté cargado). 

*Variables locales (o de bloque): 
– Creadas en la sentencia en la que están definidas. 
– No se inicializan por defecto. Contienen datos imprevisibles. 
– Se destruyen al salir del bloque (en la llave final).
