### Más Ejemplos de Examen Oral con Soluciones

#### Ejercicio 1: Operadores Matemáticos

**Enunciado**:
Calcula y muestra el resultado de la suma, resta, multiplicación y división de dos números.

**Solución en Código**:
```python
a = 10
b = 5

suma = a + b
resta = a - b
multiplicacion = a * b
division = a / b

print("Suma:", suma)
print("Resta:", resta)
print("Multiplicación:", multiplicacion)
print("División:", division)
```

**Explicación Oral**:
"Este código realiza operaciones matemáticas básicas con dos variables, `a` y `b`. Utilizamos los operadores `+`, `-`, `*` y `/` para sumar, restar, multiplicar y dividir los números, respectivamente. Cada operación se guarda en una variable correspondiente (`suma`, `resta`, `multiplicacion`, `division`) y luego se imprimen los resultados. Es un ejemplo claro de cómo aplicar operadores matemáticos básicos en Python."

#### Ejercicio 2: `for` in con Lista

**Enunciado**:
Itera sobre una lista de colores e imprime cada color.

**Solución en Código**:
```python
colores = ["rojo", "verde", "azul"]
for color in colores:
    print(color)
```

**Explicación Oral**:
"Aquí, tenemos una lista `colores` que contiene tres strings. Usamos un bucle `for` para iterar sobre esta lista. En cada iteración, la variable `color` toma el valor de cada elemento de la lista (cada color) y luego se imprime. Este ejemplo demuestra la iteración sobre una lista con un bucle `for`, que es una operación común en la manipulación de listas en Python."

#### Ejercicio 3: Operadores Lógicos y Aritméticos Combinados

**Enunciado**:
Determina si un número es par y mayor que 10.

**Solución en Código**:
```python
numero = 12

es_par = numero % 2 == 0
es_mayor_que_diez = numero > 10

if es_par and es_mayor_que_diez:
    print("El número es par y mayor que 10")
else:
    print("El número no cumple las condiciones")
```

**Explicación Oral**:
"En este código, primero determinamos si `numero` es par utilizando el operador módulo `%`. La expresión `numero % 2 == 0` devuelve `True` si el número es par. Luego, comprobamos si `numero` es mayor que 10 con `numero > 10`. Finalmente, usamos un `if` con un operador lógico `and` para verificar ambas condiciones. Si ambas son `True`, se imprime que el número es par y mayor que 10. De lo contrario, se imprime que no cumple las condiciones."
