#### Ejemplo 1: Operador Módulo para Determinar Múltiplos

**Enunciado**:
Verifica si un número es múltiplo de 3 y de 5.

**Solución en Código**:
```python
numero = 15

es_multiplo_de_3 = numero % 3 == 0
es_multiplo_de_5 = numero % 5 == 0

if es_multiplo_de_3 and es_multiplo_de_5:
    print("El número es múltiplo de 3 y 5")
else:
    print("El número no es múltiplo de 3 y 5")
```

**Explicación Oral**:
"Utilizo el operador módulo `%` para comprobar si `numero` es múltiplo de 3 y de 5. Si `numero % 3` y `numero % 5` resultan en 0, significa que es múltiplo de ambos. Usamos un `if` con `and` para verificar que ambas condiciones sean verdaderas. En este caso, como 15 es múltiplo de ambos, se imprime la primera declaración."

#### Ejemplo 2: Bucle `for` con `range()` para Suma Acumulativa

**Enunciado**:
Suma los números del 1 al 5 utilizando un bucle `for`.

**Solución en Código**:
```python
suma = 0
for i in range(1, 6):
    suma += i
print("La suma es:", suma)
```

**Explicación Oral**:
"Este código suma los números del 1 al 5. Inicializamos `suma` en 0 y luego iteramos sobre los números del 1 al 5 con `range(1, 6)`. En cada iteración, añadimos el valor de `i` a `suma`. Después del bucle, `suma` contiene el total acumulado, que es 15 en este caso."

#### Ejemplo 3: Uso de `while` para una Secuencia Descendente

**Enunciado**:
Imprime una cuenta regresiva desde 5 hasta 1 con un bucle `while`.

**Solución en Código**:
```python
contador = 5
while contador > 0:
    print(contador)
    contador -= 1
```

**Explicación Oral**:
"En este ejemplo, usamos un bucle `while` para imprimir una cuenta regresiva desde 5 hasta 1. La condición del bucle es `contador > 0`, y en cada iteración, imprimimos el valor actual de `contador` y luego lo disminuimos en 1. Cuando `contador` llega a 0, el bucle termina."

#### Ejemplo 4: Combinación de Operadores Lógicos y de Comparación

**Enunciado**:
Determina si un año es bisiesto.

**Solución en Código**:
```python
año = 2020

if año % 4 == 0 and (año % 100 != 0 or año % 400 == 0):
    print("Es un año bisiesto")
else:
    print("No es un año bisiesto")
```

**Explicación Oral**:
"Para determinar si un año es bisiesto, comprobamos si es divisible por 4 pero no por 100, a menos que también sea divisible por 400. El uso de operadores lógicos `and` y `or` permite evaluar estas condiciones compuestas. En este caso, como el año 2020 cumple estas condiciones, se reconoce como bisiesto."
