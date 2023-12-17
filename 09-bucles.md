# Lección sobre Bucles `for` y `while` en Python

## Introducción a los Bucles en Python

En programación, un bucle es una estructura fundamental que permite repetir un bloque de código múltiples veces hasta que se cumpla una condición específica. Python ofrece principalmente dos tipos de bucles: `for` y `while`. Estos bucles son herramientas poderosas que hacen que la ejecución repetitiva de código sea más manejable, legible y eficiente.

### Bucle `for`

El bucle `for` en Python es utilizado para iterar sobre una secuencia (como una lista, una tupla, un diccionario, un conjunto o una cadena). Este tipo de bucle es especialmente útil cuando sabes de antemano cuántas veces quieres que se ejecute el bloque de código, o cuando deseas realizar una operación en cada elemento de una secuencia.

#### Características del Bucle `for`:
- Iteración sobre secuencias.
- Control preciso sobre la iteración.
- Fácil de leer y escribir.

### Bucle `while`

A diferencia del bucle `for`, el bucle `while` se basa en una condición: el bloque de código se ejecuta repetidamente mientras la condición sea verdadera. Es ideal para situaciones donde no sabes cuántas veces necesitas ejecutar el bloque de código, pero quieres que continúe hasta que se cumpla una cierta condición.

#### Características del Bucle `while`:
- Basado en una condición verdadera o falsa.
- Útil para bucles con un número desconocido de iteraciones.
- Requiere cuidado para evitar bucles infinitos.

## Introducción al Bucle `for`

El bucle `for` en Python es un iterador basado en una secuencia. Se utiliza para recorrer elementos de cualquier secuencia, como listas o cadenas. Aquí está la sintaxis básica:

```python
for elemento in secuencia:
    # Realizar acciones con elemento
```

Este bucle es increíblemente versátil y puede ser utilizado para ejecutar un bloque de código para cada elemento en una secuencia.

## Introducción al Bucle `while`

El bucle `while` en Python permite realizar una serie de acciones mientras se cumpla una condición. La sintaxis básica es:

```python
while condicion:
    # Realizar acciones mientras la condición sea verdadera
```

Este tipo de bucle sigue ejecutando el bloque de código mientras la condición especificada sea verdadera. Es crucial asegurarse de que la condición en algún momento se vuelva falsa para evitar bucles infinitos.

## Conclusión

Tanto los bucles `for` como los `while` son herramientas fundamentales en la programación con Python, permitiendo a los programadores manejar tareas repetitivas de manera eficiente. En las siguientes lecciones, exploraremos en detalle cada uno de estos bucles, incluyendo ejemplos y casos prácticos de uso.