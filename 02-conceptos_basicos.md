### 2. Conceptos Básicos de Programación en Python: Sintaxis Básica y Variables

#### Sintaxis Básica

La sintaxis en Python se caracteriza por su énfasis en la legibilidad y la simplicidad. A continuación, se profundiza en algunos aspectos esenciales:

**Líneas y Sangría**:
- Python utiliza la sangría para definir bloques de código. La consistencia en la sangría es crucial, ya que una mala sangría puede causar errores.
- No hay necesidad de terminar las líneas con un carácter especial (como `;` en otros lenguajes). Una nueva línea indica una nueva instrucción, a menos que la instrucción se extienda con un `\`.

**Ejemplo de Código con Sangría:**
```python
for i in range(5):
    print(i)  # Este bloque está correctamente indentado
```

**Caso de Múltiples Líneas:**
```python
total = (1 + 2 + 3 +
         4 + 5 + 6)
```

#### Variables

Las variables son fundamentales en cualquier lenguaje de programación y Python no es la excepción. Profundizaremos en su creación, nombramiento y tipos.

**Reglas de Nomenclatura**:
- Comenzar siempre con una letra o un guion bajo.
- Solo pueden contener letras, números y guiones bajos.
- No pueden coincidir con palabras reservadas de Python.
- Sensibles a mayúsculas y minúsculas: `variable`, `Variable`, y `VARIABLE` son tres entidades distintas.

**Ejemplo de Creación de Variables:**
```python
mi_variable = 10       # Correcto
_miVariable = "texto"  # Correcto
2miVariable = 20       # Incorrecto, no puede empezar con número
mi-variable = 30       # Incorrecto, guion medio no permitido
```

#### Tipos de Datos

Python es un lenguaje de tipado dinámico, lo que significa que el tipo de una variable puede cambiar durante la ejecución del programa. Los tipos de datos más comunes son:

- **Enteros (`int`)**: Representan números enteros, positivos o negativos, sin parte decimal.
- **Flotantes (`float`)**: Representan números reales con parte decimal.
- **Cadenas de Texto (`str`)**: Representan secuencias de caracteres.
- **Booleanos (`bool`)**: Toman los valores `True` o `False`.

**Ejemplo de Tipos de Datos:**
```python
edad = 25               # int
altura = 1.75           # float
nombre = "Laura"        # str
esEstudiante = False    # bool
```

#### Reasignación y Tipos Dinámicos

En Python, las variables pueden cambiar de tipo mediante la reasignación.

**Ejemplo de Reasignación:**
```python
var = 5         # Inicialmente int
var = "Cinco"   # Reasignada a str
```

#### Operaciones Básicas con Variables

Las operaciones básicas dependen del tipo de datos de las variables.

**Operaciones Aritméticas:**
- Suma (`+`), resta (`-`), multiplicación (`*`), división (`/`).
- División entera (`//`), módulo (`%`), potencia (`**`).

**Ejemplo de Operaciones Aritméticas:**
```python
num1 = 10
num2 = 3

suma = num1 + num2          # 13
resta = num1 - num2         # 7
multiplicacion = num1 * num2 # 30
division = num1 / num2      # 3.333...
```

**Concatenación y Operaciones con Cadenas:**
- Las cadenas se pueden unir mediante el operador `+`.
- Se pueden repetir mediante el operador `*`.

**Ejemplo de Concatenación:**
```python
nombre = "Ana"
mensaje = "Hola, " + nombre  # "Hola, Ana"
```

**Ejemplo de Repetición:**
```python
eco = "eco " * 3  # "eco eco eco "
```

En resumen, el dominio de la sintaxis básica y la comprensión de cómo se crean y manipulan las variables en Python son la base para cualquier programador que busque adentrarse en este lenguaje. La flexibilidad de Python en cuanto a tipado y operaciones