### Cálculo de las Medidas de Dispersión

#### 1. **Rango (Amplitud)**
El rango es la diferencia entre el valor más grande y el más pequeño en un conjunto de datos.

**Fórmula:**
\[ \text{Rango} = x_{\text{Máximo}} - x_{\text{Mínimo}} \]

**Ejemplo:**
Dados los datos: 4, 5, 6, 7, 8
\[ \text{Rango} = 8 - 4 = 4 \]

#### 2. **Desviación Media**
La desviación media es el promedio de las desviaciones absolutas de la media.

**Fórmula:**
\[ \text{Desviación Media} = \frac{\sum |x_i - \bar{x}|}{n} \]

**Paso a Paso:**
1. Calcular la media (\(\bar{x}\)).
2. Calcular la desviación absoluta de cada dato (\(|x_i - \bar{x}|\)).
3. Sumar todas las desviaciones absolutas.
4. Dividir la suma por el número de datos (\(n\)).

**Ejemplo:**
Dados los datos: 4, 5, 6, 7, 8
1. Media: \(\bar{x} = \frac{4 + 5 + 6 + 7 + 8}{5} = 6\)
2. Desviaciones absolutas: \(|4-6| = 2\), \(|5-6| = 1\), \(|6-6| = 0\), \(|7-6| = 1\), \(|8-6| = 2\)
3. Suma de desviaciones: \(2 + 1 + 0 + 1 + 2 = 6\)
4. Desviación Media: \(\frac{6}{5} = 1.2\)

#### 3. **Varianza**
La varianza es el promedio de los cuadrados de las desviaciones de la media.

**Fórmula para Muestra:**
\[ s^2 = \frac{\sum (x_i - \bar{x})^2}{n-1} \]

**Fórmula para Población:**
\[ \sigma^2 = \frac{\sum (x_i - \mu)^2}{N} \]

**Paso a Paso:**
1. Calcular la media (\(\bar{x}\)).
2. Calcular la desviación de cada dato (\(x_i - \bar{x}\)).
3. Elevar al cuadrado cada desviación.
4. Sumar todos los cuadrados de las desviaciones.
5. Dividir la suma por \(n-1\) (para muestra) o \(N\) (para población).

**Ejemplo:**
Dados los datos: 4, 5, 6, 7, 8
1. Media: \(\bar{x} = 6\)
2. Desviaciones: \(4-6 = -2\), \(5-6 = -1\), \(6-6 = 0\), \(7-6 = 1\), \(8-6 = 2\)
3. Cuadrados de desviaciones: \((-2)^2 = 4\), \((-1)^2 = 1\), \(0^2 = 0\), \(1^2 = 1\), \(2^2 = 4\)
4. Suma de cuadrados: \(4 + 1 + 0 + 1 + 4 = 10\)
5. Varianza: \(\frac{10}{5-1} = 2.5\)

#### 4. **Desviación Estándar**
La desviación estándar es la raíz cuadrada de la varianza.

**Fórmula para Muestra:**
\[ s = \sqrt{s^2} \]

**Fórmula para Población:**
\[ \sigma = \sqrt{\sigma^2} \]

**Paso a Paso:**
1. Calcular la varianza (\(s^2\) o \(\sigma^2\)).
2. Tomar la raíz cuadrada de la varianza.

**Ejemplo:**
Varianza: \(2.5\)
Desviación Estándar: \(\sqrt{2.5} \approx 1.58\)

#### 5. **Coeficiente de Variación**
El coeficiente de variación es la relación entre la desviación estándar y la media, expresada como un porcentaje.

**Fórmula:**
\[ \text{CV} = \frac{s}{\bar{x}} \times 100\% \]

**Paso a Paso:**
1. Calcular la desviación estándar (\(s\)).
2. Calcular la media (\(\bar{x}\)).
3. Dividir la desviación estándar por la media.
4. Multiplicar por 100 para obtener el porcentaje.

**Ejemplo:**
Desviación Estándar: \(1.58\)
Media: \(6\)
Coeficiente de Variación: \(\frac{1.58}{6} \times 100\% \approx 26.33\%\)

### Resolución del Caso del Banco HSUR

#### Datos Iniciales
**Tabla 1 (Antes del Aumento de Personal):**
| N.° de clase | Tiempo en minutos | Marca de clase (\(x_{mi}\)) | N.° de clientes (\(f_i\)) | \(x_{mi} \times f_i\) |
|-------------|------------------|---------------------------|-------------------------|----------------------|
| 1           | 0-2              | 1                         | 2                       | 2                    |
| 2           | 2-4              | 3                         | 3                       | 9                    |
| 3           | 4-6              | 5                         | 5                       | 25                   |
| 4           | 6-8              | 7                         | 12                      | 84                   |
| 5           | 8-10             | 9                         | 15                      | 135                  |
| 6           | 10-12            | 11                        | 10                      | 110                  |
| 7           | 12-14            | 13                        | 3                       | 39                   |
| Total       |                  |                           | 50                      | 404                  |

**Media:**
\[ \bar{x}_1 = \frac{404}{50} = 8.08 \text{ minutos} \]

**Desviación Estándar:**
1. Calcular la media: \(\bar{x}_1 = 8.08\)
2. Calcular las desviaciones y sus cuadrados:
    - \( (1-8.08)^2 = 50.1264 \)
    - \( (3-8.08)^2 = 25.8064 \)
    - \( (5-8.08)^2 = 9.4864 \)
    - \( (7-8.08)^2 = 1.1664 \)
    - \( (9-8.08)^2 = 0.8464 \)
    - \( (11-8.08)^2 = 8.5264 \)
    - \( (13-8.08)^2 = 24.2064 \)
3. Multiplicar por las frecuencias y sumar:
    - \( 2 \times 50.1264 = 100.2528 \)
    - \( 3 \times 25.8064 = 77.4192 \)
    - \( 5 \times 9.4864 = 47.432 \)
    - \( 12 \times 1.1664 = 13.9968 \)
    - \( 15 \times 0.8464 = 12.696 \)
    - \( 10 \times 8.5264 = 85.264 \)
    - \( 3 \times 24.2064 = 72.6192 \)
    - Suma total: \( 409.68 \)
4. Calcular la varianza:
   \[ s^2_1 = \frac{409.68}{50-1} = \frac{409.68}{49} \approx 8.36 \]
5. Calcular la desviación estándar:
   \[ s_1 = \sqrt{8.36} \approx 2.89 \]
6. Coeficiente de Variación:
   \[ \text{CV}_1 = \frac{2.89}{8.08} \times 100\% \approx 35.79\% \]

#### Datos Después del Aumento de Personal
**Tabla 2:**
| N.° de clase | Tiempo en minutos | Marca de clase (\(x_{mi}\)) | N.° de clientes (\(f_i\)) | \(x_{mi} \times f_i\) |
|-------------|------------------|---------------------------|-------------------------|----------------------|
| 1           | 0-2              | 1                         | 1                       | 1                    |
| 2           | 2-4              | 3                         | 12                      | 36                   |
| 3           | 4-6              | 5                         | 14                      | 70                   |
| 4           | 6-8              | 7                         | 15                      | 105                  |
| 5           | 8-10             | 9                         | 5                       | 45                   |
| 6           | 10-12            | 11                        | 2                       | 22                   |
| 7           | 12-14            | 13                        | 1                       | 13                   |
| Total       |                  |                           | 50                      | 292                  |

**Media:**
\[ \bar{x}_2 = \frac{292}{50} = 5.84 \text{ minutos} \]

**Desviación Estándar:**
1. Calcular la media: \(\bar{x}_2 = 5.84\)
2. Calcular las desviaciones y sus cuadrados:
    - \( (1-5.84)^2 = 23.4256 \)
    - \( (3-5.84)^2 = 8.0656 \)
    - \( (5-5.84)^2 = 0.7056 \)
    - \( (7-5.84)^2 = 1.3456 \)
    - \( (9-5.84)^2 = 9.9856 \)
    - \( (11-5.84)^2 = 26.6256 \)
    - \( (13-5.84)^2 = 51.2656 \)
3. Multiplicar por las frecuencias y sumar:
    - \( 1 \times 23.4256 = 23.4256 \)
    - \( 12 \times 8.0656 = 96.7872 \)
    - \( 14 \times 0.7056 = 9.8784 \)
    - \( 15 \times 1.3456 = 20.184 \)
    - \( 5 \times 9.9856 = 49.928 \)
    - \( 2 \times 26.6256 = 53.2512 \)
    - \( 1 \times 51.2656 = 51.2656 \)
    - Suma total: \( 304.72 \)
4. Calcular la varianza:
   \[ s^2_2 = \frac{304.72}{50-1} = \frac{304.72}{49} \approx 6.22 \]
5. Calcular la desviación estándar:
   \[ s_2 = \sqrt{6.22} \approx 2.49 \]
6. Coeficiente de Variación:
   \[ \text{CV}_2 = \frac{2.49}{5.84} \times 100\% \approx 42.64\% \]

### Conclusión
- **Antes del Aumento de Personal:**
    - Media: 8.08 minutos
    - Desviación Estándar: 2.89 minutos
    - Coeficiente de Variación: 35.79%

- **Después del Aumento de Personal:**
    - Media: 5.84 minutos
    - Desviación Estándar: 2.49 minutos
    - Coeficiente de Variación: 42.64%

Aunque la media de demora disminuyó de 8.08 minutos a 5.84 minutos, la variabilidad aumentó del 35.79% al 42.64%. Esto indica que, aunque el tiempo promedio de atención mejoró, la dispersión de los tiempos de espera aumentó, lo que podría sugerir que hay algunos clientes que aún experimentan largos tiempos de espera.

---

### Significado de las Medidas de Dispersión en el Caso del Banco HSUR

#### 1. **Rango (Amplitud)**
El rango es la diferencia entre el valor más grande y el más pequeño en un conjunto de datos. En el contexto del banco HSUR, el rango nos da una idea de la variabilidad total en los tiempos de espera.

**Antes del Aumento de Personal:**
- Rango: \(14 - 0 = 14\) minutos
    - **Significado:** El tiempo de espera más largo fue de 14 minutos, mientras que el más corto fue de 0 minutos. Esto indica que había una variabilidad total de 14 minutos en los tiempos de espera.

**Después del Aumento de Personal:**
- Rango: \(14 - 0 = 14\) minutos
    - **Significado:** Aunque el rango sigue siendo el mismo (14 minutos), esto no nos dice si la distribución de los tiempos de espera ha mejorado o empeorado. El rango solo nos da una idea de la variabilidad total, pero no de la dispersión central.

#### 2. **Desviación Media**
La desviación media es el promedio de las desviaciones absolutas de la media. En el contexto del banco HSUR, la desviación media nos da una idea de cuánto se desvían en promedio los tiempos de espera de la media.

**Antes del Aumento de Personal:**
- Desviación Media: 2.89 minutos
    - **Significado:** En promedio, los tiempos de espera se desvían 2.89 minutos de la media de 8.08 minutos. Esto indica que, en promedio, los clientes esperan alrededor de 2.89 minutos más o menos que el tiempo promedio de espera.

**Después del Aumento de Personal:**
- Desviación Media: 2.49 minutos
    - **Significado:** En promedio, los tiempos de espera se desvían 2.49 minutos de la media de 5.84 minutos. Esto indica que, en promedio, los clientes esperan alrededor de 2.49 minutos más o menos que el tiempo promedio de espera. Aunque la media de espera disminuyó, la desviación media también disminuyó ligeramente, lo que sugiere una mejora en la consistencia de los tiempos de espera.

#### 3. **Varianza**
La varianza es el promedio de los cuadrados de las desviaciones de la media. En el contexto del banco HSUR, la varianza nos da una idea de la dispersión de los tiempos de espera alrededor de la media.

**Antes del Aumento de Personal:**
- Varianza: 8.36
    - **Significado:** La varianza de 8.36 indica que, en promedio, los cuadrados de las desviaciones de la media son 8.36. Esto sugiere una dispersión moderada en los tiempos de espera.

**Después del Aumento de Personal:**
- Varianza: 6.22
    - **Significado:** La varianza de 6.22 indica que, en promedio, los cuadrados de las desviaciones de la media son 6.22. Esto sugiere una dispersión ligeramente menor en los tiempos de espera, lo que indica una mejora en la consistencia de los tiempos de espera.

#### 4. **Desviación Estándar**
La desviación estándar es la raíz cuadrada de la varianza. En el contexto del banco HSUR, la desviación estándar nos da una idea de la dispersión de los tiempos de espera en términos lineales.

**Antes del Aumento de Personal:**
- Desviación Estándar: 2.89 minutos
    - **Significado:** La desviación estándar de 2.89 minutos indica que, en promedio, los tiempos de espera se desvían 2.89 minutos de la media de 8.08 minutos. Esto sugiere una dispersión moderada en los tiempos de espera.

**Después del Aumento de Personal:**
- Desviación Estándar: 2.49 minutos
    - **Significado:** La desviación estándar de 2.49 minutos indica que, en promedio, los tiempos de espera se desvían 2.49 minutos de la media de 5.84 minutos. Esto sugiere una dispersión ligeramente menor en los tiempos de espera, lo que indica una mejora en la consistencia de los tiempos de espera.

#### 5. **Coeficiente de Variación**
El coeficiente de variación es la relación entre la desviación estándar y la media, expresada como un porcentaje. En el contexto del banco HSUR, el coeficiente de variación nos da una idea de la variabilidad relativa de los tiempos de espera.

**Antes del Aumento de Personal:**
- Coeficiente de Variación: 35.79%
    - **Significado:** El coeficiente de variación del 35.79% indica que la desviación estándar es aproximadamente el 35.79% de la media. Esto sugiere una variabilidad moderada en los tiempos de espera.

**Después del Aumento de Personal:**
- Coeficiente de Variación: 42.64%
    - **Significado:** El coeficiente de variación del 42.64% indica que la desviación estándar es aproximadamente el 42.64% de la media. Esto sugiere una variabilidad mayor en los tiempos de espera, a pesar de que la media de espera disminuyó. Esto podría indicar que, aunque el tiempo promedio de espera mejoró, la consistencia de los tiempos de espera empeoró, con algunos clientes experimentando tiempos de espera más largos que antes.

### Resumen
- **Media:** La media de espera disminuyó de 8.08 minutos a 5.84 minutos, lo que indica una mejora en el tiempo promedio de atención.
- **Desviación Media:** La desviación media disminuyó ligeramente de 2.89 minutos a 2.49 minutos, lo que sugiere una mejora en la consistencia de los tiempos de espera.
- **Varianza:** La varianza disminuyó de 8.36 a 6.22, lo que sugiere una dispersión ligeramente menor en los tiempos de espera.
- **Desviación Estándar:** La desviación estándar disminuyó de 2.89 minutos a 2.49 minutos, lo que sugiere una dispersión ligeramente menor en los tiempos de espera.
- **Coeficiente de Variación:** El coeficiente de variación aumentó del 35.79% al 42.64%, lo que sugiere una variabilidad mayor en los tiempos de espera, a pesar de que la media de espera disminuyó. Esto podría indicar que, aunque el tiempo promedio de espera mejoró, la consistencia de los tiempos de espera empeoró, con algunos clientes experimentando tiempos de espera más largos que antes.

En resumen, aunque el tiempo promedio de espera mejoró, la variabilidad en los tiempos de espera aumentó, lo que sugiere que la consistencia en la atención al cliente no mejoró significativamente.