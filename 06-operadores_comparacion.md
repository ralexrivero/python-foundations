# Operadores de Comparación en Python

Los operadores de comparación son fundamentales en Python, ya que nos permiten comparar valores y tomar decisiones basadas en estas comparaciones. Esta lección explora los diferentes operadores de comparación disponibles en Python y cómo se utilizan en la programación.

## 1. Operador Igual (`==`)

El operador `==` verifica si dos valores son iguales. Devuelve `True` si son iguales y `False` si no lo son.

**Ejemplo de Código**:

```python
a = 10
b = 10

resultado = a == b
print(resultado)  # Imprimirá True porque a y b son iguales
```

## 2. Operador No Igual (`!=`)

El operador `!=` verifica si dos valores son diferentes. Devuelve `True` si son diferentes, `False` si son iguales.

**Ejemplo de Código**:

```python
a = 10
b = 5

resultado = a != b
print(resultado)  # Imprimirá True porque a y b son diferentes
```

## 3. Operador Mayor Que (`>`)

El operador `>` verifica si el valor a la izquierda es mayor que el valor a la derecha.

**Ejemplo de Código**:

```python
a = 15
b = 10

resultado = a > b
print(resultado)  # Imprimirá True porque a es mayor que b
```

## 4. Operador Menor Que (`<`)

El operador `<` verifica si el valor a la izquierda es menor que el valor a la derecha.

**Ejemplo de Código**:

```python
a = 5
b = 10

resultado = a < b
print(resultado)  # Imprimirá True porque a es menor que b
```

## 5. Operador Mayor o Igual Que (`>=`)

El operador `>=` verifica si el valor a la izquierda es mayor o igual al valor a la derecha.

**Ejemplo de Código**:

```python
a = 10
b = 10

resultado = a >= b
print(resultado)  # Imprimirá True porque a es igual a b
```

## 6. Operador Menor o Igual Que (`<=`)

El operador `<=` verifica si el valor a la izquierda es menor o igual al valor a la derecha.

**Ejemplo de Código**:

```python
a = 5
b = 10

resultado = a <= b
print(resultado)  # Imprimirá True porque a es menor o igual a b
```

## Ejemplos Prácticos

Para mejorar la comprensión, aquí hay algunos ejercicios:

1. **Ejercicio**: Verifica si dos cadenas de texto son iguales.

   **Solución en Código**:

   ```python
   cadena1 = "Hola"
   cadena2 = "Hola"

   sonIguales = cadena1 == cadena2
   print("Las cadenas son iguales:", sonIguales)
   ```

2. **Ejercicio**: Determina si un número es menor o igual a 100.

   **Solución en Código**:

   ```python
   numero = 150

   esMenorOIgual = numero <= 100
   print("El número es menor o igual a 100:", esMenorOIgual)
   ```

## Conclusión

Los operadores de comparación son herramientas esenciales en Python para realizar comparaciones entre valores. Su uso correcto es crucial para la toma de decisiones y el control del flujo en la programación. Practicar con estos operadores mejorará su habilidad para escribir código más efectivo y eficiente.
