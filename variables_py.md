# Variables

Las variables son contenedores que nos permiten almacenar y manipular datos en nuestros programas. Puedes pensar en una variable como una etiqueta a la que asignas a un valor específico. En Python, no es necesario declarar el tipo de datos de una variable de antemano, ya que Python infiere el tipo de datos automáticamente en función del valor asignado.

# Declaración y asignación de variables

Las variables son contenedores que nos permiten almacenar y manipular datos en nuestros programas. Para declarar y asignar un valor a una variable en Python, utilizamos el operador de asignación =. El nombre de la variable va a la izquierda del operador, y el valor que deseas asignar va a la derecha. Por ejemplo:

nombre = "Juan"
edad = 25
altura = 1.75
es estudiante = True

En el ejemplo, hemos declarado y asignado valores a las variables nombre, edad, altura y es_estudiante. Python infiere automáticamente el tipo de datos de cada variable en función del valor asignado.

También puedes asignar el mismo valor a múltiples variables en una sola línea utilizando el operador de asignación múltiple:

a = b = c = 10
En este caso, las variables a, b y c tendrán el valor 10.

# Normas para nombrar variables

Al nombrar variables en Python, es importante seguir algunas normas para mantener un código legible y evitar errores:

Los nombres de las variables solo pueden contener letras (a-z, A-Z), números (0-9) y guiones bajos (\_). No pueden comenzar con un número.

Python distingue entre mayúsculas y minúsculas, por lo que nombre y Nombre son variables diferentes.

No se pueden utilizar palabras clave reservadas de Python como nombres de variables (por ejemplo, if, else, for, while, etc.).

Se recomienda utilizar nombres descriptivos para las variables, que indiquen claramente su propósito: nombre, edad, total_ventas, etc.

Siguiendo estas normas, algunos ejemplos de nombres de variables válidos son:

edad
nombre_completo
total_ventas
\_contador
Y algunos ejemplos de nombres de variables inválidos son:

1edad # Comienza con un número
nombre-completo # Utiliza un guion en lugar de un guion bajo
if # Palabra clave reservada de Python

SOA_LID_Ten en cuenta.png

# Ten en cuenta Elegir nombres descriptivos para tus variables facilita la lectura y comprensión del código, tanto para ti como para otros desarrolladores que puedan trabajar en el mismo proyecto.
