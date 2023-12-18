#### Ejercicio 1: Operadores de Comparación

**Enunciado**:
Determina si un número es igual, menor o mayor que otro.

**Solución en Código**:
```python
numero1 = 10
numero2 = 15

if numero1 < numero2:
    print("numero1 es menor que numero2")
elif numero1 > numero2:
    print("numero1 es mayor que numero2")
else:
    print("numero1 y numero2 son iguales")
```

**Explicación Oral**:
"Este código utiliza operadores de comparación para evaluar la relación entre `numero1` y `numero2`. Primero, con `if numero1 < numero2`, comprobamos si `numero1` es menor. Si esta condición es verdadera, se imprime que `numero1` es menor. Si no, `elif numero1 > numero2` comprueba si `numero1` es mayor, y si es así, se imprime que es mayor. Finalmente, si ninguna de las condiciones anteriores es verdadera, el `else` se ejecuta, indicando que ambos números son iguales."

#### Ejercicio 2: Bucle `for` con `range()`

**Enunciado**:
Imprime los primeros cinco números enteros positivos.

**Solución en Código**:
```python
for i in range(1, 6):
    print(i)
```

**Explicación Oral**:
"Aquí, usamos un bucle `for` con `range(1, 6)` para iterar desde 1 hasta 5. `range(1, 6)` genera una secuencia de números que comienza en 1 y termina en 5, ya que el límite superior en `range()` es exclusivo. En cada iteración, la variable `i` toma el valor del número actual en el rango y se imprime. De esta manera, el bucle imprime los números del 1 al 5."

#### Ejercicio 3: Bucle `while`

**Enunciado**:
Escribe un programa que cuente hacia atrás desde 5 y luego imprima "¡Despegue!".

**Solución en Código**:
```python
contador = 5
while contador > 0:
    print(contador)
    contador -= 1
print("¡Despegue!")
```

**Explicación Oral**:
"Utilizamos un bucle `while` que se ejecuta mientras `contador` sea mayor que 0. Dentro del bucle, imprimimos el valor actual de `contador` y luego lo disminuimos en 1. Cuando `contador` llega a 0, el bucle `while` termina y se imprime '¡Despegue!'. Este código es un ejemplo clásico de un bucle `while` que se utiliza para una cuenta regresiva."
