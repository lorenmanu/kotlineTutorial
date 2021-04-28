# kotlineTutorial

[![EC2](https://www.dropbox.com/s/st4etj28pyu11lb/aws-ec2_logo_small.jpg?dl=1)](http://ec2-52-11-219-71.us-west-2.compute.amazonaws.com)


## **Proyecto de IV(infraestructura Virtual) junto con DAI(DESARROLLO DE APLICACIONES DE INTERNET** ##

### Introducción: ###
Kotlin[3] es un lenguage fuertemente tipado, con grandes semejanzas con otros lenguages de
programación como Scala, Groovy o C. Genera código para JVM(máquina virtual de Java
6), Javacript, y últimas versiones también de ejecutables nativos.


Entre sus ventajas, nos encontramos las siguientes:
- Es compatible con Java, por lo que se puede usar cualquier librería escrita en este lenguage.
- Tiene clase de datos, permitiendo el uso de equals, hashCode, getters, setters y copy.
- Podemos sobrecargar operadores.
- Como hemos mencionado antes, es compatible con Java 6, lo que es interesante para An-
droid.
- Su codificación es clara, sencilla y simple.
- Realizaremos las mismas tareas con menos líneas
de código que en Java.
- Ofrece el respaldo de JetBrains, Google y Spring Framework, lo que le convierte en un
lenguage con gran proyección de futuro.
- Al ser un lenguage muy parecido a Java, lo hace didáctico para los alumnos, facilitando la ense-
ñanza de conceptos como Herencia, Polimorfismo y
- Programación Orientada a Objetos,
los cuales son básicos y esenciales para cualquier programador.


#### Estructura simple kotline

Como podemos observar, desde principio muestra similitudes con otros lenguajes de programación como **C++** o **Java**. **Main** será la función principal que ejecutará el programa secuencialmente de arriba abajo. Desde ahí podremos llamar a otras funciones, declarar variables, realizar operaciones sobre ellas, crear objetos y trabajar con ellos ..., como veremos más adelante.

[![img1](https://github.com/lorenmanu/kotlineTutorial/blob/main/imgsVariablesKotline/img1.png)]

### Variables con Kotline

En Kotlin existen las palabras clave **val** para crear una variable constante o **var** para crear una variable. Si queremos declarar el tipo de variable, tal como String o Int, se indica después del nombre de la variable.

```
val integer: Int = 1
val firstName: String = "Chike"

```

#### Tipos básicos

En comparación con Java, encontramos dos tipos de tipo:
- Primitivo (ej. int, long, boolean, byte, char, etc.)
- Tipos de referencia (ej. array, String). Java tiene librerías (como java.lang.Integer) para que los tipos primitivos se comporten como objetos.

En el caso de **C++**, todos los datos básicos son de tipo primitivo, a no ser que usemos alguna librería de **stl**.

En Kotlin, a diferencia de **C++** y **Java**, todos los tipos son objetos.

Para los datos numéricos, disponemos de las siguientes variables.

[![img2](https://github.com/lorenmanu/kotlineTutorial/blob/main/imgsVariablesKotline/img2.png)]

En la anterior imagen podemos ver el tipo de variables que  hay, el numero de bit que ocupan en memoria. **Double** y **Float** son para valores decimales, las cuatro siguientes son para enteros. Además de ellas, también tenemos para caracteres(**Char**), vectores o colecciones de elemento(**Array**) ...

En las variables de tipo numerico vemos funciones de ayuda que convierten de un tipo de número a otro : toByte(), toInt(), toLong(), toFloat(), toDouble(), toChar(), toShort().


```
val myInt = 987
val myLong = myInt.toLong()

```

También puedes convertir un String en un tipo número.

```

val stringNumber = "101"
val intValue = stringNumber.toInt()

```

#### Vectores o colecciones de elementos

En Kotlin, hay dos formas para crear una colección de elementos: usando la función de ayuda arrayOf() o el constructor Array().

Ahora, para acceder a cualquiera del elemento, podemos usar su índice: myArray[2].

[![img3](https://github.com/lorenmanu/kotlineTutorial/blob/main/imgsVariablesKotline/img3.png)]
