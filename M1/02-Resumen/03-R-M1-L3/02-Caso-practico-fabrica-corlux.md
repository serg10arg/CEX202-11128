### Caso Práctico: Fábrica CORLUX

En este caso, la fábrica CORLUX produce lámparas de bajo consumo y ha recopilado datos sobre la cantidad de lámparas defectuosas en cajas de 12 unidades y la vida útil de las lámparas. A continuación, se presenta una tabla que refleja las **medidas de posición** (media, mediana y moda) para ambos conjuntos de datos.

---

### **Tabla 1: Medidas de Posición para las Lámparas Defectuosas**

| **Medida de Posición** | **Cálculo** | **Resultado** | **Interpretación** |
| --- | --- | --- | --- |
| **Media** | sum(x_i x f_i)/n = 51/30 | **1.7** | El promedio de lámparas defectuosas por caja es 1.7. |
| **Mediana** | Se calcula la posición central (n/2 = 15). La mediana es **1**. | **1** | La mitad de las cajas tiene 1 o menos lámparas defectuosas. |
| **Moda** | El valor más frecuente es **0** (aparece en 10 cajas). | **0** | La mayoría de las cajas no tienen lámparas defectuosas. |

---

### **Tabla 2: Medidas de Posición para la Vida Útil de las Lámparas**

| **Medida de Posición** | **Cálculo** | **Resultado** | **Interpretación** |
| --- | --- | --- | --- |
| **Media** | sum (x_m x f_i) / n = 176,250 / 90 | **1958.33** | La vida útil promedio de las lámparas es 1958.33 horas. |
| **Mediana** | Se calcula la clase mediana (intervalo 2015-2315 horas) y se aplica la fórmula: Me = 2015 + 300 x (45 - 43)/22 | **2042.27** | La mitad de las lámparas tiene una vida útil menor a 2042.27 horas. |
| **Moda** | Se calcula la clase modal (intervalo 2315-2615 horas) y se aplica la fórmula: Mo = 2315 + 300  x 3/28 | **2347.14** | La vida útil más frecuente es 2347.14 horas. |

---

### Interpretación General

1. **Lámparas Defectuosas**:
    - **Media (1.7)**: En promedio, hay 1.7 lámparas defectuosas por caja.
    - **Mediana (1)**: La mitad de las cajas tiene 1 o menos lámparas defectuosas.
    - **Moda (0)**: La mayoría de las cajas no tienen lámparas defectuosas.
    - **Conclusión**: La distribución tiene un **sesgo positivo** (Media > Mediana > Moda), lo que indica que hay algunas cajas con más lámparas defectuosas que elevan el promedio.
2. **Vida Útil de las Lámparas**:
    - **Media (1958.33)**: La vida útil promedio es de 1958.33 horas.
    - **Mediana (2042.27)**: La mitad de las lámparas tiene una vida útil menor a 2042.27 horas.
    - **Moda (2347.14)**: La vida útil más frecuente es 2347.14 horas.
    - **Conclusión**: La distribución tiene un **sesgo negativo** (Media < Mediana < Moda), lo que indica que hay algunas lámparas con una vida útil más corta que reducen el promedio.

---

### Resumen

| **Variable** | **Media** | **Mediana** | **Moda** | **Sesgo** |
| --- | --- | --- | --- | --- |
| **Lámparas Defectuosas** | 1.7 | 1 | 0 | Positivo |
| **Vida Útil de las Lámparas** | 1958.33 | 2042.27 | 2347.14 | Negativo |

---

### Conclusión Final

- **Lámparas Defectuosas**: La mayoría de las cajas no tienen lámparas defectuosas, pero algunas cajas con más defectos elevan el promedio.
- **Vida Útil de las Lámparas**: La mayoría de las lámparas tienen una vida útil larga, pero algunas lámparas con menor duración reducen el promedio.

Estas medidas de posición ayudan a la fábrica CORLUX a entender la calidad de sus productos y tomar decisiones para mejorar sus procesos.