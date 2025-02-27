### Resumen Detallado: Tablas de Contingencia y Árboles de Decisión

---

### **Introducción**

El cálculo de probabilidades es fundamental en la toma de decisiones, especialmente en contextos donde es necesario evaluar diferentes escenarios y sus posibles resultados. En este sentido, las **tablas de contingencia** y los **árboles de decisión** son herramientas gráficas que facilitan el razonamiento probabilístico, permitiendo organizar y visualizar datos de manera clara y eficiente. Estas herramientas no solo simplifican el cálculo de probabilidades, sino que también ayudan a identificar relaciones entre eventos, ya sean dependientes o independientes. Su uso es especialmente relevante en campos como la administración, la economía y la ingeniería, donde es necesario tomar decisiones basadas en datos probabilísticos.

---

### **Fundamentos Teóricos**

### **1. Tablas de Contingencia**

- **Definición y características**:

  Una tabla de contingencia es una herramienta que organiza datos en filas y columnas, permitiendo clasificar eventos de manera cruzada. Cada celda de la tabla representa la frecuencia o probabilidad de ocurrencia de un evento conjunto, mientras que los márgenes (totales de filas y columnas) representan las probabilidades marginales de cada evento individual.

- **Estructura y componentes**:
  - **Filas**: Representan categorías de eventos mutuamente excluyentes y colectivamente exhaustivos.
  - **Columnas**: Representan otra categorización de eventos, también mutuamente excluyentes y exhaustivos.
  - **Celdas**: Contienen las frecuencias o probabilidades conjuntas de los eventos.
  - **Totales marginales**: Sumas de filas y columnas que representan las probabilidades marginales.
- **Relación con eventos dependientes e independientes**:

  Las tablas de contingencia permiten identificar si dos eventos son independientes o dependientes. Si la probabilidad conjunta de dos eventos es igual al producto de sus probabilidades marginales, los eventos son independientes. En caso contrario, son dependientes.


### **2. Árboles de Decisión**

- **Definición y características**:

  Un árbol de decisión es un diagrama que representa secuencias de eventos y decisiones. Está compuesto por nodos (puntos de decisión o eventos) y ramas (posibles resultados o acciones). Cada rama tiene asociada una probabilidad, y los nodos finales representan los resultados posibles.

- **Estructura y nodos**:
  - **Nodos de decisión**: Puntos donde se toman decisiones.
  - **Nodos de evento**: Puntos donde ocurren eventos aleatorios.
  - **Ramas**: Representan las posibles decisiones o resultados.
  - **Resultados**: Representan los puntos finales del árbol, asociados a probabilidades o valores.
- **Uso en la representación de secuencias de eventos**:

  Los árboles de decisión son especialmente útiles para representar experimentos de pasos múltiples, donde cada paso depende del anterior. Permiten calcular probabilidades condicionales y totales de manera secuencial.


---

### **Aplicaciones Prácticas**

### **1. Uso de Tablas de Contingencia**

- **Ejemplo 1: Gaseosas y defectos en envases**

  Se analizan botellas de gaseosas clasificadas por tamaño (500 ml, 1000 ml, 1500 ml) y defectos en el envase (menos de 2 defectos, 2 o más defectos). La tabla de contingencia permite calcular:

  - Probabilidad de que una botella sea de 1500 ml.
  - Probabilidad de que una botella tenga 2 o más defectos.
  - Probabilidad de que una botella sea de 1000 ml y tenga menos de 2 defectos.

  **Tabla de Contingencia**:

  | Capacidad | 500 ml | 1000 ml | 1500 ml | Totales |
      | --- | --- | --- | --- | --- |
  | Menos de 2 defectos | 350 | 390 | 200 | 940 |
  | 2 o más defectos | 50 | 130 | 80 | 260 |
  | Totales | 400 | 520 | 280 | 1200 |
- **Ejemplo 2: Becas de la Fundación Antares**

  Se analizan egresados de Córdoba clasificados por carrera (Administración-Dirección, Otras) y tipo de universidad (pública, privada). La tabla de contingencia permite calcular:

  - Probabilidad de que un egresado sea de Administración-Dirección.
  - Probabilidad de que un egresado sea de una universidad pública.
  - Probabilidad de que un egresado de Administración sea de una universidad pública.

  **Tabla de Contingencia**:

  | Universidad | Pública | Privada | Totales |
      | --- | --- | --- | --- |
  | Administración | 221 | 539 | 760 |
  | Otras | 9517 | 6198 | 15715 |
  | Totales | 9738 | 6737 | 16475 |

### **2. Uso de Árboles de Decisión**

- **Ejemplo 3: Lanzamiento de una moneda tres veces**

  Se representa un experimento de pasos múltiples donde se lanza una moneda tres veces. El árbol de decisión permite calcular:

  - Probabilidad de que salga cara las tres veces.
  - Probabilidad de que salga cara en la primera tirada.
  - Probabilidad de que salga cruz las dos primeras tiradas.

  **Árbol de Decisión**:

  - Primer nivel: Primera tirada (Cara o Cruz).
  - Segundo nivel: Segunda tirada (Cara o Cruz).
  - Tercer nivel: Tercera tirada (Cara o Cruz).
- **Ejemplo 4: Extracción de monedas falsas**

  Se extraen dos monedas de un conjunto de 10, donde 4 son falsas. El árbol de decisión permite calcular:

  - Probabilidad de que al menos una moneda sea falsa.
  - Probabilidad de que ambas monedas sean falsas.

  **Árbol de Decisión**:

  - Primer nivel: Primera extracción (Falsa o Buena).
  - Segundo nivel: Segunda extracción (Falsa o Buena), dependiendo de la primera.

---

### **Comparación entre Tablas de Contingencia y Árboles de Decisión**

- **Ventajas de las tablas de contingencia**:
  - Son útiles para analizar relaciones entre dos variables categóricas.
  - Permiten calcular probabilidades conjuntas y marginales de manera directa.
  - Son ideales para problemas basados en frecuencias relativas.
- **Ventajas de los árboles de decisión**:
  - Son útiles para representar secuencias de eventos y decisiones.
  - Permiten calcular probabilidades condicionales y totales en experimentos de pasos múltiples.
  - Son ideales para problemas donde los eventos son dependientes.
- **Limitaciones**:
  - Las tablas de contingencia pueden volverse complejas con muchas categorías.
  - Los árboles de decisión pueden volverse extensos y difíciles de manejar en experimentos con muchos pasos.

---

### **Conclusión**

Las **tablas de contingencia** y los **árboles de decisión** son herramientas esenciales en el análisis probabilístico. Las tablas de contingencia permiten organizar y calcular probabilidades de eventos conjuntos y marginales, mientras que los árboles de decisión son ideales para representar secuencias de eventos y calcular probabilidades condicionales. Ambas herramientas son complementarias y su elección depende del tipo de problema a resolver. En conjunto, facilitan la toma de decisiones basada en datos probabilísticos, permitiendo una mejor comprensión de los eventos y sus relaciones.

---

Este resumen proporciona una visión clara y estructurada de las herramientas, destacando su utilidad en el cálculo de probabilidades y la toma de decisiones.