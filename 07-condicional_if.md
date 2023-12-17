# Lección sobre la Estructura Condicional `if` en Python

En esta lección, exploraremos en detalle la estructura condicional `if` en Python. Esta estructura es fundamental en la programación, ya que permite que un programa ejecute ciertas acciones basadas en si una condición es verdadera o falsa.

## ¿Qué es el Condicional `if`?

El condicional `if` en Python es una estructura de control que evalúa una expresión lógica y, en función de si esta expresión es verdadera (`True`) o falsa (`False`), ejecuta un bloque de código asociado.

### Sintaxis Básica

La sintaxis básica de un `if` en Python es:

```python
if condicion:
    # Bloque de código que se ejecuta si condicion es True
```

Aquí, `condicion` es una expresión que Python evaluará. Si `condicion` es verdadera, se ejecutará el bloque de código indentado que sigue al `if`.

### Importancia de la Indentación

En Python, la indentación es crucial para definir bloques de código. El bloque de código dentro de un `if` debe estar correctamente indentado para que Python lo interprete correctamente.

## Ejemplo 1: Condicional `if` Simple

**Enunciado**:
Escribe un código que verifique si un número es positivo.

**Solución en Código**:

```python
numero = 5

if numero > 0:
    print("El número es positivo.")
```

**Explicación Oral**:
"En este código, he definido una variable `numero` con el valor 5. Utilizo un condicional `if` para verificar si `numero` es mayor que 0. Si esta condición es verdadera, lo que en este caso lo es, el programa ejecuta el bloque de código indentado bajo el `if`, imprimiendo 'El número es positivo.'"

## Ejemplo 2: Uso de `if` con `else`

**Enunciado**:
Modifica el código anterior para que también maneje el caso en que el número no sea positivo.

**Solución en Código**:

```python
numero = -3

if numero > 0:
    print("El número es positivo.")
else:
    print("El número no es positivo.")
```

**Explicación Oral**:
"Además del condicional `if`, uso un `else` para manejar el caso en que la condición `numero > 0` no se cumpla. Si `numero` es mayor que 0, se ejecuta el bloque de código después del `if`. De lo contrario, el flujo del programa va al bloque `else` y se ejecuta el código que imprime 'El número no es positivo'. En este caso, como `numero` es -3, se ejecuta el bloque `else`."

## Ejemplo 3: Uso de `elif`

**Enunciado**:
Amplía el código anterior para identificar si el número es cero.

**Solución en Código**:

```python
numero = 0

if numero > 0:
    print("El número es positivo.")
elif numero == 0:
    print("El número es cero.")
else:
    print("El número es negativo.")
```

**Explicación Oral**:
"Utilizo `elif` para agregar otra condición: si `numero` es igual a 0. El flujo del programa primero verifica si `numero` es mayor que 0. Si no lo es, pasa a la siguiente condición `elif` y verifica si `numero` es 0. Si ninguna de estas condiciones se cumple, se ejecuta el bloque `else`. Así, este código puede identificar si un número es positivo, cero o negativo."

## Conclusión

El uso del condicional `if` junto con `else` y `elif` proporciona una herramienta poderosa para controlar el flujo del programa, permitiendo ejecutar diferentes bloques de código según las condiciones dadas. Esta estructura es fundamental para la toma de decisiones en la programación y es esencial para cualquier desarrollador de Python.