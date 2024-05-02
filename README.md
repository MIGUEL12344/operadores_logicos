## operadores logicos##
Operadores lógicos
Los operadores lógicos o logical operators nos permiten trabajar con valores de tipo booleano. Un valor booleano o bool es un tipo que solo puede tomar valores True o False. Por lo tanto, estos operadores nos permiten realizar diferentes operaciones con estos tipos, y su resultado será otro booleano. Por ejemplo, True and True usa el operador and, y su resultado será True. A continuación lo explicaremos mas en detalle.
Operador and
El operador or devuelve True cuando al menos uno de los elementos es igual a True. Es decir, evalúa si el valor a la izquierda o el de la derecha son True
Operador not
Y por último tenemos el operador not, que simplemente invierte True por False y False por True. También puedes usar varios not juntos y simplemente se irán aplicando uno tras otro. La verdad que es algo difícil de ver en la realidad, pero simplemente puedes contar el número de not y si es par el valor se quedará igual. Si por lo contrario es impar, el valor se invertirá
>ejemplo:
```python
# Operadores lógicos en Python

# Operador AND
x = 5
y = 10
z = 15
if x < y and y < z:
    print("x es menor que y y y es mayor que z.")

# Operador OR
a = 20
b = 25
c = 30
if a > b or b > c:
    print("Al menos una de las condiciones es verdadera.")

# Operador NOT
verdadero = True
if not verdadero:
    print("Esta línea no se imprimirá porque verdadero es verdadero.")

# Operador de igualdad ==
numero1 = 10
numero2 = 20
if numero1 == numero2:
    print("Los números son iguales.")
else:
    print("Los números son diferentes.")

# Operador de desigualdad !=
color1 = "rojo"
color2 = "azul"
if color1 != color2:
    print("Los colores son diferentes.")
else:
    print("Los colores son iguales.")

# Operador de pertenencia in
lista = [1, 2, 3, 4, 5]
if 3 in lista:
    print("3 está en la lista.")

# Operador de no pertenencia not in
cadena = "Hola Mundo"
if "a" not in cadena:
    print("La letra 'a' no está en la cadena.")
```