# quiz-prework-ts-node

JavaScript Básico:

Describe qué es una función en JavaScript y cómo se declara.

Respuesta: Una función es un metodo o una acción de algo especifico que se crea de forma abstracta y luego se puede reutilizar en varios contextos. En javascrip existen tres tipos de funciones:
Funciones expresadas: Son funciones que se declaran mediante una variable, las cuales no se pueden utilizar antes de ser declaradas, y el objeto this hace referencia a la misma función donde se esta inicializando.
Funciones declaradas: No se declaran mediante variables y no necesariamente tienen que ser declaradas antes de ser utilizadas, el objeto this funciona igual que las expresadas.
Funciones flecha: No tienen hosting al igual que las expresadas, es decir deben ser primero declaradas antes de ser utilizadas, y el objeto this funciona diferente a los anteriores ya que este hace referencia al objeto que contiene la funcion donde esta siendo declarado.

Manipulación del DOM:

Explica cómo seleccionar un elemento del DOM y cambiar su contenido.

Respuesta: Para obtener el elemento se hace uso de alguno de los selectores que javascript nos ofrece, podemos seleccionar por id (document.getElementById), por clases (document.querySelector y document.querySelectorAll), por nombre, por etiqueta etc..
Luego de obtener el elemento para cambiar su contenido utilizamos innerHtml o textContet



Programación Orientada a Objetos (OOP):

¿Qué es una clase en JavaScript y cómo se define una?

Respuesta: Una clase es un modelo a seguir o un molde para crear instancias de esa clase donde se establecen los atributos (caracteristicas de ese objeto) y los metodos (acciones que ese objeto puede ejecutar), normalmente hacen referencia a objetos del mundo real
Eventos en JavaScript:

¿Cómo se agrega un evento de clic a un botón en JavaScript?
Respuesta: Primero se debe obtener el boton con la ayuda de los selectores anteriormente mencionados, luego por medio de un escuchador de eventos en este caso addEventListener el cual recibe dos parametros, el tipo de evento que para este caso seria click, y la funcion a ejecutar luego de ese click.

Variables y Tipos de Datos:

Explica las diferencias entre var, let, y const en JavaScript.
Respuesta: var: es la forma de declarar una variable la cual puede cambiar su valor y tipo de dato en el transcurso del código, y tiene un alcance más global con respecto a las otras dos, se usa en casos muy especificos ya que luego de la incorporación de let se ha vuelto casi obsoleta.
let: al igual que var se utiliza para declarar una variable que puede cambiar, y a diferencia de var tiene un alcance más local, lo cual ayuda a tener un rendimiento más especifico en nuestro código.
const: es la forma que se utiliza para declarar una constante, ya que en el transcurso del codigo no es posible cambiar su valor o su tipo de dato, es recomendable utilizarla siempre que nuestros datos no vayan a cambiar para garantizar la permanencia de estos datos durante todo el programa.

Control de Flujo:

¿Qué son las estructuras de control de flujo y cuáles son algunas de las más comunes en JavaScript?
Son estructuras que nos ayudan a optimizar ciertas tareas las cuales son repetitivas en el caso de los ciclos como while, for, for in y derivadas en javascript, y en el caso de condicionales nos ayudan a ejecutar ciertas tareas basadas en las posibles respuestas que podemos obtener, las más comunes son if else, try catch, switch
Funciones de Flecha:

Describe qué es una función de flecha en JavaScript y proporciona un ejemplo de cómo se usa.
JSON:

¿Qué es JSON y cómo se utiliza en JavaScript?
Promesas:

Explica qué es una promesa en JavaScript y proporciona un ejemplo de su uso.
Depuración:

¿Cuáles son algunas de las herramientas o métodos que se pueden usar para depurar código JavaScript?
Preguntas de Selección Múltiple (20)
¿Cuál de las siguientes es la forma correcta de declarar una variable en JavaScript?
A) var myVariable;
B) variable myVariable;
C) let myVariable;
D) A y C son correctas.
¿Qué método se utiliza para agregar un elemento al final de un array en JavaScript?
A) push()
B) pop()
C) shift()
D) unshift()
¿Cuál de los siguientes operadores se utiliza para comparar tanto el valor como el tipo de dos variables en JavaScript?
A) ==
B) ===
C) !=
D) !==
¿Cuál es la salida del siguiente código?
console.log(typeof null);
Explicar
A) null
B) undefined
C) object
D) number
¿Cuál de los siguientes métodos se usa para recorrer todos los elementos de un array?
A) forEach()
B) map()
C) filter()
D) Todas las anteriores
¿Qué se entiende por “hoisting” en JavaScript?
A) Declaraciones de variables y funciones se mueven al principio de su ámbito.
B) Es un término para describir la eliminación de variables.
C) Es un método para agrupar varias funciones.
D) Ninguna de las anteriores.
¿Cuál es la diferencia entre null y undefined en JavaScript?
A) null significa que una variable ha sido declarada pero no definida, undefined significa que no se ha declarado.
B) null es un valor asignado intencionalmente, undefined significa que una variable no tiene valor.
C) undefined es un valor asignado intencionalmente, null significa que una variable no tiene valor.
D) No hay diferencia.
¿Cuál es el propósito del método Array.prototype.map()?
A) Modificar el array original.
B) Crear un nuevo array con los resultados de aplicar una función a cada elemento del array original.
C) Filtrar los elementos de un array.
D) Encontrar un elemento en un array.
¿Qué es el Event Loop en JavaScript?
A) Un ciclo que controla las llamadas recursivas.
B) Un proceso que permite a JavaScript realizar operaciones asincrónicas.
C) Un método para iterar sobre arrays.
D) Ninguna de las anteriores.
¿Cuál es la salida del siguiente código?

console.log(0.1 + 0.2 === 0.3);
Explicar
A) true
B) false
C) undefined
D) NaN
¿Qué se entiende por strict mode en JavaScript?

A) Un modo que permite utilizar características experimentales.
B) Un modo que cambia la forma en que se ejecuta JavaScript, haciéndolo más seguro.
C) Un método para validar datos.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una forma correcta de crear un objeto en JavaScript?

A) let obj = {};
B) let obj = Object.create();
C) let obj = new Object();
D) A y C son correctas.
¿Qué es un callback en JavaScript?

A) Una función que se pasa como argumento a otra función.
B) Un tipo de variable especial.
C) Un método para declarar funciones.
D) Ninguna de las anteriores.
¿Cuál es el propósito de async y await en JavaScript?

A) Ejecutar funciones síncronas.
B) Manejar operaciones asincrónicas de manera más simple y legible.
C) Declarar variables globales.
D) Ninguna de las anteriores.
¿Cuál de las siguientes es una estructura de datos inmutable en JavaScript?

A) Arrays
B) Strings
C) Objetos
D) Ninguna de las anteriores.
¿Cómo se puede convertir un objeto JSON en una cadena de texto en JavaScript?

A) JSON.parse()
B) JSON.stringify()
C) toString()
D) parseInt()
¿Qué es un Promise en JavaScript?

A) Una función que se ejecuta inmediatamente.
B) Un objeto que representa la eventual finalización (o falla) de una operación asincrónica.
C) Un método para declarar variables.
D) Ninguna de las anteriores.
¿Qué método se utiliza para agregar uno o más elementos al principio de un array y devolver la nueva longitud del array?

A) push()
B) pop()
C) shift()
D) unshift()
¿Cuál es la diferencia entre localStorage y sessionStorage en JavaScript?

A) localStorage almacena datos solo durante la sesión del navegador, sessionStorage almacena datos de manera persistente.
B) sessionStorage almacena datos solo durante la sesión del navegador, localStorage almacena datos de manera persistente.
C) No hay diferencia entre ellos.
D) Ambos almacenan datos solo durante la sesión del navegador.
¿Qué método se utiliza para detener la propagación de un evento en el DOM?

A) event.stopPropagation()
B) event.preventDefault()
C) event.stop()
D) event.cancel()
