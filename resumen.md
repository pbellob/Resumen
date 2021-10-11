# Resumen
**Este es el resumen de los Estudiante Linda Orduy, Juan Prieto y Paola Bello**
**Strings->** Se crea a partir de “” o ‘’ se puede operar esta función cuando ejecutamos lo que podemos hacer con ese string estamos obteniendo métodos o funciones en el texto.unir dos strings se usa el símbolo “+”f indica que lo que esté en las {} debe interpretarlo 
**Funciones:** Se usa myStr.función_que_deseas.*upper* convierte en mayúscula el texto. *lower* convierte en minúscula .*swapcase* convierte en may y min.capitalize solo la primera en mayúscula .replace -> reemplaza la palabra que desea por otra (mystr.replace(‘hola’,’bye’)).si quiero incluir otra función junto a otro pones .y la función que quieras “métodos encadenados”.count contar cuantos caracteres tiene en el texto .startswith o endswith saber el texto escrito empieza o termina por la palabra que preguntas.split Divide el texto (por medio de una coma) y crea una lista.find te encuentra la posición del carácter.len Te da la longitud del texto.isnumeric isalpha Si el contenido es numérico o alfanumérico .Números-> int  números enteros.                    float números decimales 
Operaciones:Exponenciales Modulo División que me devuelve el residuo // o%.¿Cómo solicitar un dato al usuario? .Con la función input.Listas-> Constructor ->Es una .ufión que permite definir una lista list((y la lista de objetos)) hacer tuple se definen con [ ].Range toma dos parámetros para no poner todos los datos.solicitar posición se usa [ ].Las funciones de strings en cuanto a las características como find, len etc… Se puede usar también en listas.in es “en” el resultado indica si un dato hace parte de un grupo o no .append Agregar otro dato en la lista.(solo se le puede pasar de a un elemento).extend pasar dos elementos al mismo tiempo dejándolos individualmente tiene que ser con cupla lista .insert insertar un dato en la posición deseada. color.insert(posición_elDatoQueQuieroIngresar) .pop elimina el último dato de la lista o por la posición. Remove elimina dato por los caracteres sí quiero eliminar el verde, lo pongo tal cual no se usa con la posición. clear elimina toda la lista “limpia”.sort ordena los datos si quiere ordenarlo de manera inversa se una (reverse=true).index indica la posición de los elementos.count contar los datos que desees en una lista.Tuples Las tuplas se asigna un conjunto que no se va a poder cambiar, son muchas más rápido o para asegurar el código, se define entre paréntesis (),.para definir una tupla se usa “Tuple”.cuando uno quiere tener un solo dato en la tupla debe poner después de esta una , porque si solo esta en dato no lo tomara como una tuple .La tupla no se puede modificar .si quiero eliminarlo usar todo usar el “del”.SETS Colección desordenada y que no tiene un índice, se define con { }.se puede adicionar, remover, saber si pertenece un dato, limpiar .Esto depende de la aplicación, es bueno si solo quiere tener un conjunto de datos sin ningún orden
Al momento de programar es recomendable limpiar la consola cada cierto tiempo, esto puede ayudar a mantener el entorno organizado y principalmente ayuda a no perderse en el proceso.

**Dictionaries**:

Existe un tipo de dato que recibe el nombre de “Dictionaries” y funcionan de manera particular pero útil: suponiendo que se necesita guardar una gran cantidad de datos, podemos definir estos datos agregando sus características y si se quiere, guardarlas en una variable, por ejemplo: se tiene un carrito de compras, en el cual queremos añadir un producto específico pero junto con el queremos añadir su precio y cantidad de unidades, sin embargo son muchos productos, así que decidimos usar un tipo de dato diccionario y lo guardamos de este modo

Product = {
“name”: “phone”
“quantity”: 10
“price”: 1000
}

Aquí guardamos en la variable product (que puede tomar cualquier nombre) tres datos, el nombre, la cantidad y el precio. si queremos visualizar en la consola que tipo de variable es “producto” solo debemos escribir:

Print(type(product))

y nos saldrá que es una variable diccionario. 

**Conditionals:**

El comando clave para los condicionales es la palabra “IF” cuyo significado en español sería básicamente “si” pero no un sí afirmativo si no uno de condición. Este comando va acompañado de los operadores de comparación, los cuales son el mayor que (>) el menor que (<) y el igualdad (==) en este caso son son dos signos iguales pues uno solo significa asignar valores. Existe un comando complementario llamado Else, que podría servir como otro if, solo que else podría interpretarse como un “sin embargo” y funcionaria de modo que cuando la condición que programamos con IF no se cumple, automáticamente pasa a ejecutarse lo que se programó dentro de un Else, por ejemplo:

X=40

if x < 20:
	print( ”x es menor que 20”)
else:
	print(“x es mayor que 20”)

Y por último, es posible agregar un condicional anidado que funciona como otro If solo que el nombre del comando es “elif” y se coloca después del primer If también con una condicional. Junto a esta forma de programar se pueden usar también 3 operadores lógicos de utilidad tales como:
and: se usa cuando queremos extender el if con más información, creando una condición más compleja.
or: esta palabra puede significar “o” de elección, lo que provocaría generar dos condiciones en una, puede ser esta, o aquella..
not: este operador es básicamente una negación, donde se pregunta: “si esto no es así, realizar aquella acción”.
 
**Loops o bucles:**

Los dos bucles básicos que se usan a la hora de programar son dos, el for y el while

For: Un bucle en el que se ejecuta la instrucción de control durante un número de veces previamente conocido para obtener el resultado se conoce como bucle.
En el bucle for, el comando está controlado por una variable. Cada vez que el ciclo se repite, la variable predefinida obtiene un nuevo valor.Durante la inicialización del bucle for, se debe declarar un valor inicial para la variable. Este bucle requiere inicialización sólo una vez. Después de la inicialización, el compilador verifica si la condición es verdadera o no, y si es verdadera, el ciclo continúa iterando hasta que se obtiene el número predefinido de iteraciones. para parar un bucle es posible usar el comando “Break” Un ejemplo del bucle for es el siguiente:

for letter in “hello”:
	print(letter)

este comando dará como resultado que la consola muestre letra por letra la palabra “hello”

While: Un ciclo while es cuando el comando itera un número incierto de veces hasta que la condición es verdadera. Una vez que se demuestra que la condición es falsa, la iteración del comando se detiene. La inicialización en el ciclo while se realiza cada vez que el ciclo itera. El compilador verifica la condición y, si se demuestra que es falsa, el ciclo salta a la siguiente declaración.

Si falta la condición inicial en el ciclo while, el ciclo itera infinitamente. En el ciclo while, no se crea ningún valor nuevo para la variable, solo se cumple la condición. En el ciclo while, la condición se comprueba antes de la iteración, por lo que también se conoce como ciclo de prueba previa. Un ejemplo del comando while seria:

count = 4

while count <=10:
	print(count)
	count = count +1

**Funciones:**

Podría definirse como una porción de código que procesa internamente una entrada que le demos para así poder arrojar una salida o respuesta, por ejemplo la función que más se usa es la “print”. Para declarar una función solo se debe poner la palabra “def” seguido del nombre de la función. Un ejemplo de función sería:

def umas(a, b):
  return a + b

result = suma(1, 2)
