Actividades a realizar:

i. Identifique las clases y lo que éstas representan. Luego, establezca una descripción textual breve del contexto problema.

Hay dos clases, la primera llamada calculadora que representa una Calculadora de la vida real que solo puede sumar y multiplicar dos numeros, y la otra clase llamada CarroCompra que representa un carrito de supermercado en donde se ingresan productos y se multiplican la cantidad de un mismo producto comprado por su valor y se suman todos los productos ya multiplicados. 

ii. Analice los atributos y métodos de cada clase, luego, identifique las relaciones existentes entre las clases identificadas y establezca una descripción textual breve del contexto problema..

La clase Calculadora tiene los atributos n1 y n2 que son dos variables de tipo int los cuales son utilizados en los metodos. El metodo Calculadora es el constructor, en esta clase hay dos constructores, uno que se inicializa el objeto con las variables con cero en ambas variables y el otro que tiene dos parametros de entrada, uno para cada variable. Ademas tiene los metodos sumar y multiplizcar, que estos suman y multiplicna los dos nuemros respectivamente y los retorno y luego tiene los metodos setN1 y setN2 los cuales cambian los valores de las variables respectivamente segun lo que se le entregue por parametro de entrada.

la clase CarroCompra tiene un solo atributo el cual es una matriz (un array de array), tiene un constrctor el cual hace que el objeto al inicializarce ya venga con la matriz llena, y despues tiene los metodos calcularTotal el cual calcula y retorna el total de lo que se debe pagar, el metodo subTotal el cual calcula la multiplicacion del precio de un producto por la cant de productos que compra (mismo producto) y el metodo mostrar total el cual muestra el total de la compra.

El problema es el siguente: utilizar la clase CarroCompra para incluir productos que se compraran, primero llama al metodo calcularTotal el cual llama a el metodo subtotal y este llama al metodo de la clase Calculadora llamado multiplicar, de esta forma se multiplica la cant de productos iguales con el valor del producto, luego estos se ingresan al subtotal y se suman en el total y luego se imprimer el total de la compra con el metodo mostrarTotal.