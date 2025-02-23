### Tabla de Frecuencias con Intervalos de Clase

Cuando trabajamos con datos cuantitativos que tienen muchos valores diferentes (por ejemplo, más de 15), es útil agruparlos en **intervalos de clase**. Esto nos permite resumir la información sin perder su calidad y facilita su interpretación. A continuación, se presenta una tabla de frecuencias con intervalos de clase, junto con una explicación de cómo se calcula y su relación con el concepto de **marca de clase**.

---

### Tabla de Frecuencias con Intervalos de Clase

Supongamos que tenemos los siguientes datos sobre el costo total de pasajes (en dólares) para un grupo de solicitudes turísticas:

**Datos**: 338, 500, 700, 1000, 1200, 1500, 1800, 2000, 2200, 2500, 2800, 3000, 3200, 3500, 4000, 4500, 5000, 5500, 6000, 6500, 7000, 7500, 8000.

#### Pasos para Construir la Tabla:

1. **Determinar el Número de Intervalos (k)**:
    - Usamos la fórmula: k = √n, donde n es el número de datos.
    - En este caso, n = 23, entonces k = √23 ≈ approx 4.8. Redondeamos a 5 intervalos.

2. **Calcular la Amplitud del Intervalo (Δx)**:
    -             Fórmula: Δx = Dato mayor - Dato menor / k
    - Dato mayor = 8000, Dato menor = 338.
    - Δx = 8000 - 338 / 5  = 7662 / 5 = 1532.4 Redondeamos a 1533.

3. **Definir los Intervalos**:
    - Los intervalos se construyen sumando la amplitud (1533) al límite inferior de cada intervalo.
    - Los intervalos son cerrados por la izquierda y abiertos por la derecha: [L₁, L₂).

4. **Calcular la Marca de Clase (xmᵢ)**:
    - La marca de clase es el punto medio de cada intervalo y se calcula como:
    -                       xmᵢ = L₁ + L₂ / 2
    - Representa el valor central del intervalo y se usa para cálculos posteriores, como el promedio.

5. **Contar las Frecuencias**:
    - Contamos cuántos datos caen en cada intervalo.

---

#### Tabla de Frecuencias con Intervalos de Clase

| **N.º de Clase** | **Intervalo de Clase (US$)** | **Marca de Clase (xmᵢ)** | **Frecuencia Absoluta (fᵢ)** | **Frecuencia Relativa (frᵢ)** | **Frecuencia Porcentual (frᵢ%)** | **Frecuencia Absoluta Acumulada (Fᵢ)** |
|-------------------|------------------------------|--------------------------|------------------------------|-------------------------------|----------------------------------|----------------------------------------|
| 1                 | [338, 1871)                  | 1104.5                   | 7                            | 0.30                          | 30%                                | 7                                      |
| 2                 | [1871, 3404)                 | 2637.5                   | 6                            | 0.26                          | 26%                                | 13                                     |
| 3                 | [3404, 4937)                 | 4170.5                   | 5                            | 0.22                          | 22%                                | 18                                     |
| 4                 | [4937, 6470)                 | 5703.5                   | 3                            | 0.13                          | 13%                                | 21                                     |
| 5                 | [6470, 8003)                 | 7236.5                   | 2                            | 0.09                          | 9%                                 | 23                                     |

---

### Explicación de los Cálculos

#### 1. **Número de Intervalos (k)**
- Se calcula usando la fórmula;
-     k = √n, donde n es el número de datos.
- En este caso, n = 23 , entonces k = √23 ≈ 4.8. Redondeamos a 5 intervalos.

#### 2. **Amplitud del Intervalo (Δx)**
- Se calcula como:
-     Δx = Dato mayor - Dato menor / k
- Dato mayor = 8000, Dato menor = 338.
- Δx = 8000 - 338 / 5 = 7662 / 5 = 1532.4. Redondeamos a 1533.

#### 3. **Intervalos de Clase**
- Los intervalos se construyen sumando la amplitud (1533) al límite inferior de cada intervalo.
- Por ejemplo:
    - Primer intervalo: [338, 338 + 1533) = [338, 1871).
    - Segundo intervalo: [1871, 1871 + 1533) = [1871, 3404).
- Los intervalos son cerrados por la izquierda y abiertos por la derecha, lo que significa que el límite inferior está incluido, pero el límite superior no.

#### 4. **Marca de Clase (xmᵢ)**
- La marca de clase es el punto medio de cada intervalo y se calcula como:
-              xmᵢ = L₁ + L₂ / 2
- Por ejemplo, para el primer intervalo [338, 1871):
-       xmᵢ = 338 + 1871 / 2 = 2209 / 2 = 1104.5
- La marca de clase representa el valor central del intervalo y se usa en cálculos como el promedio.

#### 5. **Frecuencias**
- **Frecuencia Absoluta (fᵢ)**: Contamos cuántos datos caen en cada intervalo.
    - Por ejemplo, en el primer intervalo [338, 1871), hay 7 datos.
- **Frecuencia Relativa (frᵢ)**: Se calcula como;
-                 frᵢ= fᵢ / n
-     Para el primer intervalo: fr1 = 7 / 23 ≈ approx 0.30.        
- **Frecuencia Porcentual (frᵢ%)**: Se calcula como;
-             frᵢ% = frᵢ x 100 
-      Para el primer intervalo: frᵢ% = 0.30 x 100 = 30%.
- **Frecuencia Absoluta Acumulada (Fᵢ)**: Es la suma de las frecuencias absolutas de todos los intervalos anteriores.
-     Para el segundo intervalo: F2 = 7 + 6 = 13 . 

---

### Relación entre Intervalos de Clase y Marca de Clase

La **marca de clase** es un concepto clave en las tablas de frecuencias con intervalos de clase. Representa el valor central de cada intervalo y se utiliza para:

1. **Cálculos Estadísticos**: La marca de clase se usa para calcular medidas como el promedio (media) y la varianza cuando los datos están agrupados.
2. **Gráficos**: En gráficos como los histogramas y polígonos de frecuencia, la marca de clase se usa para ubicar los puntos en el eje horizontal.
3. **Interpretación**: La marca de clase proporciona un valor representativo de cada intervalo, lo que facilita la interpretación de los datos.

---

### Conclusión

La tabla de frecuencias con intervalos de clase es una herramienta útil para resumir y organizar datos cuantitativos con muchos valores diferentes. La **marca de clase** es esencial para representar cada intervalo y realizar cálculos estadísticos. Con esta tabla, podemos entender mejor la distribución de los datos y tomar decisiones basadas en información organizada y clara.
