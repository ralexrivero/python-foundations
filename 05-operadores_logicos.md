# Operadores Lógicos en Python

Los operadores lógicos son esenciales en Python, ya que nos permiten realizar comparaciones y tomar decisiones basadas en múltiples condiciones. En esta lección, exploraremos los operadores lógicos `and`, `or`, y `not`, y veremos cómo se pueden combinar para crear lógicas complejas.

## 1. Operador `and`

El operador `and` evalúa si ambas expresiones son verdaderas. Si lo son, devuelve `True`; de lo contrario, devuelve `False`.

**Ejemplo de Código**:

```python
a = True
b = False

resultado = a and b
print(resultado)  # Imprimirá False porque b es False

resultado = a and True
print(resultado)  # Imprimirá True porque ambos son True
```

## 2. Operador `or`

El operador `or` devuelve `True` si al menos una de las expresiones es verdadera. Devuelve `False` solo si ambas expresiones son falsas.

**Ejemplo de Código**:

```python
a = True
b = False

resultado = a or b
print(resultado)  # Imprimirá True porque a es True

resultado = False or b
print(resultado)  # Imprimirá False porque ambos son False
```

## 3. Operador `not`

El operador `not` invierte el valor de verdad. Si la expresión es verdadera, `not` la convierte en falsa, y viceversa.

**Ejemplo de Código**:

```python
a = True

resultado = not a
print(resultado)  # Imprimirá False porque a es True

b = False
resultado = not b
print(resultado)  # Imprimirá True porque b es False
```

## Combinando Operadores Lógicos

Es posible combinar estos operadores para evaluar condiciones más complejas.

**Ejemplo de Código Combinado**:

```python
edad = 25
esEstudiante = True

if edad > 20 and esEstudiante:
    print("Mayor de 20 años y estudiante")
else:
    print("Condición no cumplida")
```

## Ejemplos Prácticos

Para profundizar la comprensión, aquí hay algunos ejercicios:

1. **Ejercicio**: Determina si una persona es elegible para votar, considerando edad y ciudadanía.

   **Solución en Código**:

   ```python
   edad = 20
   esCiudadano = True

   puedeVotar = edad >= 18 and esCiudadano
   print("Puede votar:", puedeVotar)
   ```

2. **Ejercicio**: Evalúa si un número es par o impar.

   **Solución en Código**:

   ```python
   numero = 5

   esPar = numero % 2 == 0
   print("El número es par:", esPar)
   ```

## Más Ejemplos con Técnica de Explicación Oral

### Ejemplo 1: Uso del Operador Módulo (`%`) con `and`

**Enunciado**: Determina si un número es divisible por 4 y 6.

**Solución en Código**:

```python
numero = 24

esDivisiblePor4 = numero % 4 == 0
esDivisiblePor6 = numero % 6 == 0

resultado = esDivisiblePor4 and esDivisiblePor6
print("El número es divisible por 4 y 6:", resultado)
```

**Explicación Oral**:
"Para verificar la divisibilidad por 4 y 6, uso el operador módulo. Si `numero % 4` y `numero % 6` son ambos 0, el número es divisible por 4 y 6. Luego, combino estas dos condiciones con `and`. Si ambas son verdaderas, el número cumple la condición."

### Ejemplo 2: Combinando `and` para Evaluar Condiciones

**Enunciado**: Verifica si un número es positivo y menor que 10.

**Solución en Código**:

```python
numero = 5

esPositivo = numero > 0
esMenorQueDiez = numero < 10

resultado = esPositivo and esMenorQueDiez
print("El número es positivo y menor que 10:", resultado)
```

**Explicación Oral**:
"Para este caso, defino dos condiciones: `numero > 0` y `numero < 10`. Utilizo `and` para asegurarme de que

 ambas condiciones sean verdaderas. El resultado será `True` solo si el número es positivo y a la vez menor que 10."

### Ejemplo 3: Uso del Operador `not`

**Enunciado**: Determina si un número no es divisible por 3.

**Solución en Código**:

```python
numero = 7

esDivisiblePor3 = numero % 3 == 0
resultado = not esDivisiblePor3
print("El número no es divisible por 3:", resultado)
```

**Explicación Oral**:
"Primero verifico si el número es divisible por 3. Luego, uso `not` para invertir el resultado. Si el número no es divisible por 3, `not esDivisiblePor3` será `True`, indicando que el número no cumple la condición de ser divisible por 3."

## Conclusión

Los operadores lógicos son fundamentales en Python para realizar comparaciones y tomar decisiones basadas en múltiples condiciones. Su uso adecuado y combinado permite crear lógicas complejas y eficientes en la programación.