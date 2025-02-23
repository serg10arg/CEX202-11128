### Aplicación de la Regla Empírica en el Caso del Banco HSUR

La **regla empírica** (también conocida como la regla del 68-95-99.7 o la regla de las tres desviaciones estándar) es una herramienta estadística que se aplica a datos que siguen una distribución normal (también llamada distribución gaussiana o campana de Gauss). Esta regla nos permite estimar la proporción de datos que caen dentro de ciertos rangos alrededor de la media.

### Regla Empírica
La regla empírica establece que, para una distribución normal:
- **Aproximadamente el 68%** de los datos caen dentro de una desviación estándar de la media (\(\mu \pm \sigma\)).
- **Aproximadamente el 95%** de los datos caen dentro de dos desviaciones estándar de la media (\(\mu \pm 2\sigma\)).
- **Aproximadamente el 99.7%** de los datos caen dentro de tres desviaciones estándar de la media (\(\mu \pm 3\sigma\)).

### Verificación de la Distribución Normal
Antes de aplicar la regla empírica, es crucial verificar si los datos siguen una distribución normal. Esto se puede hacer mediante:
- **Gráficos de probabilidad normal**: Verificar si los datos se alinean en una recta.
- **Pruebas estadísticas**: Como la prueba de Shapiro-Wilk.
- **Comparación de medidas de tendencia central**: La media, la mediana y la moda deben ser aproximadamente iguales.

### Caso del Banco HSUR
En el caso del banco HSUR, tenemos dos conjuntos de datos: uno antes y otro después del aumento de personal. Vamos a analizar si estos datos siguen una distribución normal y, de ser así, aplicar la regla empírica.

#### Datos Iniciales (Antes del Aumento de Personal)
- **Media (\(\bar{x}_1\))**: 8.08 minutos
- **Desviación Estándar (\(s_1\))**: 2.89 minutos

#### Datos Después del Aumento de Personal
- **Media (\(\bar{x}_2\))**: 5.84 minutos
- **Desviación Estándar (\(s_2\))**: 2.49 minutos

### Verificación de la Distribución Normal
Para aplicar la regla empírica, necesitamos verificar si los datos siguen una distribución normal. En el caso del banco HSUR, no se proporcionan gráficos de probabilidad normal ni resultados de pruebas estadísticas, por lo que debemos basarnos en las medidas de tendencia central.

#### Medidas de Tendencia Central
- **Media (\(\bar{x}\))**: Ya calculada.
- **Mediana**: El valor central cuando los datos están ordenados.
- **Moda**: El valor que aparece con más frecuencia.

#### Cálculo de la Mediana y la Moda
**Antes del Aumento de Personal:**
- **Mediana**:
    1. Determinar la clase mediana: La clase cuya frecuencia acumulada es mayor a \(n/2 = 25\).
    2. Clase mediana: 6-8 minutos.
    3. Aplicar la fórmula de la mediana para datos agrupados:
       \[
       \text{Mediana} = L_i + \left( \frac{\frac{n}{2} - F_{i-1}}{f_i} \right) \times c
       \]
       Donde:
        - \(L_i\) = límite inferior de la clase mediana (6)
        - \(n\) = número total de datos (50)
        - \(F_{i-1}\) = frecuencia acumulada de la clase anterior (20)
        - \(f_i\) = frecuencia de la clase mediana (12)
        - \(c\) = amplitud de la clase (2)
          \[
          \text{Mediana} = 6 + \left( \frac{25 - 20}{12} \right) \times 2 = 6 + \left( \frac{5}{12} \right) \times 2 \approx 6.83 \text{ minutos}
          \]

- **Moda**:
    1. Determinar la clase modal: La clase con la mayor frecuencia (8-10 minutos).
    2. Aplicar la fórmula de la moda para datos agrupados:
       \[
       \text{Moda} = L_i + \left( \frac{f_i - f_{i-1}}{2f_i - f_{i-1} - f_{i+1}} \right) \times c
       \]
       Donde:
        - \(L_i\) = límite inferior de la clase modal (8)
        - \(f_i\) = frecuencia de la clase modal (15)
        - \(f_{i-1}\) = frecuencia de la clase anterior (12)
        - \(f_{i+1}\) = frecuencia de la clase siguiente (10)
        - \(c\) = amplitud de la clase (2)
          \[
          \text{Moda} = 8 + \left( \frac{15 - 12}{2 \times 15 - 12 - 10} \right) \times 2 = 8 + \left( \frac{3}{8} \right) \times 2 \approx 8.75 \text{ minutos}
          \]

**Después del Aumento de Personal:**
- **Mediana**:
    1. Determinar la clase mediana: La clase cuya frecuencia acumulada es mayor a \(n/2 = 25\).
    2. Clase mediana: 6-8 minutos.
    3. Aplicar la fórmula de la mediana para datos agrupados:
       \[
       \text{Mediana} = 6 + \left( \frac{25 - 27}{15} \right) \times 2 = 6 + \left( \frac{-2}{15} \right) \times 2 \approx 5.87 \text{ minutos}
       \]

- **Moda**:
    1. Determinar la clase modal: La clase con la mayor frecuencia (6-8 minutos).
    2. Aplicar la fórmula de la moda para datos agrupados:
       \[
       \text{Moda} = 6 + \left( \frac{15 - 14}{2 \times 15 - 14 - 5} \right) \times 2 = 6 + \left( \frac{1}{16} \right) \times 2 \approx 6.125 \text{ minutos}
       \]

### Análisis de la Distribución Normal
- **Antes del Aumento de Personal:**
    - Media: 8.08 minutos
    - Mediana: 6.83 minutos
    - Moda: 8.75 minutos
    - La media y la moda son similares, pero la mediana es significativamente menor. Esto sugiere una distribución sesgada a la izquierda, no normal.

- **Después del Aumento de Personal:**
    - Media: 5.84 minutos
    - Mediana: 5.87 minutos
    - Moda: 6.125 minutos
    - La media, la mediana y la moda son bastante similares, lo que sugiere una distribución más simétrica. Sin embargo, no podemos afirmar con certeza que sea normal sin más pruebas.

### Aplicación de la Regla Empírica
Dado que no podemos confirmar con certeza que los datos siguen una distribución normal, la regla empírica no se puede aplicar directamente. Sin embargo, para fines ilustrativos, veamos cómo se aplicaría si los datos fueran normales.

#### Antes del Aumento de Personal
- **Media (\(\mu\))**: 8.08 minutos
- **Desviación Estándar (\(\sigma\))**: 2.89 minutos

- **Rango de 1 desviación estándar (\(\mu \pm \sigma\))**:
  \[
  8.08 \pm 2.89 \Rightarrow [5.19, 10.97]
  \]
    - **Interpretación**: Aproximadamente el 68% de los clientes esperan entre 5.19 y 10.97 minutos.

- **Rango de 2 desviaciones estándar (\(\mu \pm 2\sigma\))**:
  \[
  8.08 \pm 2 \times 2.89 \Rightarrow [2.30, 13.86]
  \]
    - **Interpretación**: Aproximadamente el 95% de los clientes esperan entre 2.30 y 13.86 minutos.

- **Rango de 3 desviaciones estándar (\(\mu \pm 3\sigma\))**:
  \[
  8.08 \pm 3 \times 2.89 \Rightarrow [-0.61, 16.75]
  \]
    - **Interpretación**: Aproximadamente el 99.7% de los clientes esperan entre -0.61 y 16.75 minutos. (Notar que un tiempo negativo no tiene sentido en este contexto, lo que sugiere que la distribución no es perfectamente normal).

#### Después del Aumento de Personal
- **Media (\(\mu\))**: 5.84 minutos
- **Desviación Estándar (\(\sigma\))**: 2.49 minutos

- **Rango de 1 desviación estándar (\(\mu \pm \sigma\))**:
  \[
  5.84 \pm 2.49 \Rightarrow [3.35, 8.33]
  \]
    - **Interpretación**: Aproximadamente el 68% de los clientes esperan entre 3.35 y 8.33 minutos.

- **Rango de 2 desviaciones estándar (\(\mu \pm 2\sigma\))**:
  \[
  5.84 \pm 2 \times 2.49 \Rightarrow [0.86, 10.82]
  \]
    - **Interpretación**: Aproximadamente el 95% de los clientes esperan entre 0.86 y 10.82 minutos.

- **Rango de 3 desviaciones estándar (\(\mu \pm 3\sigma\))**:
  \[
  5.84 \pm 3 \times 2.49 \Rightarrow [-1.63, 13.31]
  \]
    - **Interpretación**: Aproximadamente el 99.7% de los clientes esperan entre -1.63 y 13.31 minutos. (Nuevamente, un tiempo negativo no tiene sentido, lo que sugiere que la distribución no es perfectamente normal).

### Conclusión
Aunque la regla empírica proporciona una herramienta útil para datos normales, no se puede aplicar directamente en este caso sin confirmar la normalidad de los datos. Sin embargo, la regla empírica puede ser útil para entender la dispersión de los datos si se asume que los datos son aproximadamente normales. En el caso del banco HSUR, la media de espera disminuyó después del aumento de personal, pero la variabilidad aumentó, lo que sugiere que, aunque el tiempo promedio de espera mejoró, la consistencia de los tiempos de espera empeoró.