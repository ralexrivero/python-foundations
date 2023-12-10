# Ejercicios Prácticos con Soluciones Orales sobre Operadores de Comparación y Lógicos

## Ejercicio 1: Comparar Números

**Enunciado**: Verifica si un número es mayor que otro.

**Solución en Código**:

```python
numero1 = 15
numero2 = 10

esMayor = numero1 > numero2
print("Número 1 es mayor que número 2:", esMayor)
```

**Explicación Oral**:
"Para verificar si `numero1` es mayor que `numero2`, utilizo el operador de comparación `>`. Si `numero1` es mayor, la expresión `numero1 > numero2` devuelve `True`. En este caso, como 15 es mayor que 10, el resultado es `True`, indicando que `numero1` es efectivamente mayor que `numero2`."

## Ejercicio 2: Igualdad en Cadenas de Texto

**Enunciado**: Determina si dos cadenas de texto son iguales.

**Solución en Código**:

```python
cadena1 = "Python"
cadena2 = "python"

sonIguales = cadena1 == cadena2
print("Las cadenas son iguales:", sonIguales)
```

**Explicación Oral**:
"Para comparar dos cadenas de texto, uso el operador de igualdad `==`. Este operador compara `cadena1` y `cadena2` y devuelve `True` si son exactamente iguales. Dado que Python es sensible a mayúsculas y minúsculas, 'Python' y 'python' no son iguales, por lo que el resultado es `False`."

## Ejercicio 3: Número Par Utilizando Módulo

**Enunciado**: Verifica si un número es par.

**Solución en Código**:

```python
numero = 4

esPar = numero % 2 == 0
print("El número es par:", esPar)
```

**Explicación Oral**:
"Para determinar si un número es par, uso el operador módulo `%` para obtener el resto de la división de `numero` entre 2. Si el resto es 0 (`numero % 2 == 0`), entonces el número es par. En este ejemplo, 4 dividido entre 2 no deja resto, por lo que el resultado es `True`, indicando que el número es par."

## Ejercicio 4: Combinación de Operadores Lógicos y de Comparación

**Enunciado**: Verifica si una persona es adolescente (entre 13 y 19 años).

**Solución en Código**:

```python
edad = 15

esAdolescente = edad >= 13 and edad <= 19
print("La persona es adolescente:", esAdolescente)
```

**Explicación Oral**:
"Para determinar si la `edad` cae en el rango de un adolescente, utilizo una combinación de operadores de comparación y lógicos. Primero, compruebo si `edad` es mayor o igual a 13 (`edad >= 13`) y luego si es menor o igual a 19 (`edad <= 19`). Utilizo el operador lógico `and` para asegurarme de que ambas condiciones sean verdaderas. Si ambas son verdaderas, `esAdolescente` será `True`. En este caso, 15 cumple ambas condiciones."
