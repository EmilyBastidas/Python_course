# Conceptos básicos de la sintaxis en Python

Antes de sumergirnos en conceptos más avanzados, es importante familiarizarse con algunos aspectos básicos de la sintaxis de Python.

# Indentación

En Python, la indentación (espacios o tabulaciones al inicio de una línea) se utiliza para delimitar bloques de código. A diferencia de otros lenguajes que utilizan llaves o palabras clave, Python utiliza la indentación para determinar el alcance de las declaraciones. Por ejemplo: 

if condition:

    # Bloque de código si la condición es verdadera

    instrucción1
    instrucción2

else:

    # Bloque de código si la condición es falsa

    instrucción3
    instrucción4

# IMPORTANTE: Es fundamental mantener una indentación consistente en todo el código para evitar errores de sintaxis.

# Comentarios

Los comentarios son líneas de texto en el código que son ignoradas por el intérprete de Python. Se utilizan para explicar o documentar el código. En Python, los comentarios de una sola línea comienzan con el símbolo #, mientras que los comentarios de varias líneas se encierran entre triples comillas """. Por ejemplo:

# Este es un comentario de una sola línea

"""
Este es un comentario
de varias líneas
"""

# Sensibilidad a mayúsculas y minúsculas

Python distingue entre mayúsculas y minúsculas. Por lo tanto, variable, Variable y VARIABLE se consideran variables diferentes.

 

# Punto y coma

A diferencia de otros lenguajes, Python no requiere el uso de punto y coma (;) al final de cada instrucción. Sin embargo, si deseas escribir varias instrucciones en una sola línea, puedes separarlas con un punto y coma. Por ejemplo:

instruccion1; instruccion2; instruccion3

# Uso de paréntesis

Los paréntesis se utilizan para agrupar expresiones, definir funciones y realizar llamadas a funciones. Por ejemplo:

resultado = (a + b) * c
 