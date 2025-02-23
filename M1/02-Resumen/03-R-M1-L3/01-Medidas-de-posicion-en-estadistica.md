# Resumen: Medidas de Posición en Estadística

## Introducción
En estadística, las **medidas de posición** (también llamadas **medidas de tendencia central**) son valores que nos ayudan a resumir y entender cómo se distribuyen los datos alrededor de un valor central. Las más comunes son la **media**, la **mediana** y la **moda**. Estas medidas son útiles para analizar datos y tomar decisiones basadas en la información recopilada.

## Medidas de Posición para Datos Sin Agrupar

### 1. Media Aritmética (Promedio)
- **Definición**: Es la suma de todos los valores dividida por el número de observaciones.
- **Fórmula**:

  - **Media = (Σ x_i) / n**

Donde `x_i` son los valores de los datos y `n` es el número de observaciones.

- **Ejemplo**:

Si las notas de 5 estudiantes son `7, 8, 6, 9, 10`, la media es:

- (7 + 8 + 6 + 9 + 10) / 5 = 8


**Interpretación**: El promedio de las notas es 8.

### 2. Mediana
- **Definición**: Es el valor que se encuentra en el centro de los datos cuando están ordenados de menor a mayor.
- **Cálculo**:
- Si el número de datos es **impar**, la mediana es el valor central.
- Si el número de datos es **par**, la mediana es el promedio de los dos valores centrales.

- **Ejemplo**:

Para los datos `3, 5, 7, 9, 11`, la mediana es `7`.

Para los datos `3, 5, 7, 9`, la mediana es:

- **(5 + 7) / 2 = 6**


**Interpretación**: La mitad de los datos está por debajo de 6 y la otra mitad por encima.

### 3. Moda
- **Definición**: Es el valor que más se repite en un conjunto de datos.
- **Ejemplo**:

Para los datos `2, 3, 4, 4, 5`, la moda es `4`.

**Interpretación**: El número `4` es el valor más frecuente.

## Medidas de Posición para Datos Agrupados

Cuando los datos están agrupados en intervalos (por ejemplo, rangos de edades o ingresos), las medidas de posición se calculan de manera diferente.

### 1. Media Aritmética para Datos Agrupados
- **Fórmula**:

- **Media = (Σ (x_m * f_i)) / n**


Donde `x_m` es la **marca de clase** (el punto medio del intervalo) y `f_i` es la frecuencia del intervalo.

- **Ejemplo**:

Si tenemos un intervalo `10-20` con `5` observaciones, la marca de clase es `15`. Si la suma de todos los productos `(x_m * f_i)` es `300` y hay `20` observaciones, la media es:

- **300 / 20 = 15**


**Interpretación**: El promedio de los datos es 15.

### 2. Mediana para Datos Agrupados
- **Fórmula**:

  * **Mediana = L_i + (Δx * ((n / 2 - F_m-1) / f_m))**


Donde:
- `L_i` = límite inferior del intervalo que contiene la mediana.
- `Δx` = amplitud del intervalo.
- `F_m-1` = frecuencia acumulada del intervalo anterior.
- `f_m` = frecuencia del intervalo que contiene la mediana.

- **Ejemplo**:

Si el intervalo que contiene la mediana es `20-30`, con `L_i = 20`, `Δx = 10`, `F_m-1 = 15`, y `f_m = 10`, la mediana es:

- **20 + (10 * ((50 / 2 - 15) / 10)) = 25**


**Interpretación**: La mitad de los datos está por debajo de 25 y la otra mitad por encima.

### 3. Moda para Datos Agrupados
- **Fórmula**:
    
  - **Moda = L_i + (Δx * (d_1 / (d_1 + d_2)))**


Donde:
- `L_i` = límite inferior del intervalo modal.
- `d_1` = diferencia entre la frecuencia del intervalo modal y el intervalo anterior.
- `d_2` = diferencia entre la frecuencia del intervalo modal y el intervalo siguiente.

- **Ejemplo**:

Si el intervalo modal es `30-40`, con `L_i = 30`, `d_1 = 5`, y `d_2 = 3`, la moda es:

- **30 + (10 * (5 / (5 + 3))) = 36.25**


**Interpretación**: El valor más frecuente está alrededor de `36.25`.

## Otras Medidas de Posición

### 1. Cuartiles
- **Definición**: Son valores que dividen los datos en cuatro partes iguales.
- **Q1**: Primer cuartil (25% de los datos están por debajo).
- **Q2**: Segundo cuartil (coincide con la mediana, 50% de los datos están por debajo).
- **Q3**: Tercer cuartil (75% de los datos están por debajo).

### 2. Percentiles
- **Definición**: Son valores que dividen los datos en 100 partes iguales.
- **P50**: Percentil 50 (coincide con la mediana).

## Relación entre Media, Mediana y Moda

- **Distribución Simétrica**: Media = Mediana = Moda.
- **Distribución Asimétrica a la Derecha (Sesgo Positivo)**: Media > Mediana > Moda.
- **Distribución Asimétrica a la Izquierda (Sesgo Negativo)**: Media < Mediana < Moda.

## Conclusión
Las medidas de posición (media, mediana y moda) son herramientas fundamentales en estadística para resumir y analizar datos. Dependiendo de cómo estén distribuidos los datos, estas medidas nos ayudan a entender la tendencia central y la forma de la distribución. Con estos conceptos, podemos tomar decisiones más informadas basadas en datos.

