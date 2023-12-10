### Lección sobre el Uso del Condicional `if` en Python

Como profesor experto en Python, voy a guiarlos a través de una lección completa sobre el uso del condicional `if` en Python. El condicional `if` es una estructura fundamental de control de flujo en la programación, que permite ejecutar ciertas acciones basadas en si una condición es verdadera o falsa.

#### Concepto del Condicional `if`

El condicional `if` evalúa una expresión lógica y ejecuta un bloque de código si la condición es `True`. Si la condición es `False`, el bloque de código bajo el `if` no se ejecuta.

#### Sintaxis Básica de `if`

La sintaxis básica de un `if` en Python es la siguiente:

```python
if condicion:
    # Bloque de código que se ejecuta si condicion es True
```

Noten la importancia de la indentación en Python. El bloque de código dentro del `if` debe estar indentado.

#### Ejemplo 1: Condicional `if` Simple

**Enunciado**:
Escribe un código que verifique si un número es positivo.

**Solución en Código**:
```python
numero = 5

if numero > 0:
    print("El número es positivo.")
```

**Explicación Oral**:
"En este código, tengo una variable `numero` con valor 5. Utilizo un condicional `if` para verificar si `numero` es mayor que 0. Si esta condición es verdadera, lo que en este caso lo es, el programa ejecuta el bloque de código indentado bajo el `if`, imprimiendo 'El número es positivo.'"

#### Ejemplo 2: Uso de `if` con `else`

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
"Ahora, además del condicional `if`, uso un `else`. Si `numero` es mayor que 0, se imprime 'El número es positivo'. De lo contrario, el flujo del programa va al bloque `else` y se imprime 'El número no es positivo.' En este caso, como `numero` es -3, se ejecuta el bloque `else`."

#### Ejemplo 3: Uso de `elif`

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

#### Conclusión

El uso del condicional `if` junto con `else` y `elif` proporciona una poderosa herramienta para el control del flujo del programa, permitiendo ejecutar diferentes bloques de código según las condiciones dadas. Esta estructura es fundamental para la toma de decisiones en la programación y es esencial para cualquier desarrollador de Python.