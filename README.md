# SI3003 – Inteligencia Artificial


## Grupo 8 – Algoritmos de búsqueda

### Juan Esteban Jimenez
### Andres Osorio
### Simon Mazo

Los notebooks están en sus carpetas originales, se subió toda la carpeta de lecture2 ya que en esta hay archivos necesarios para ejecutar los notebooks.

## Contenido

```
.
├── 02_algoritmos_busqueda_grafo.ipynb
├── 02_busqueda_en_laberintos.ipynb 
├── 01_hill_climbing.ipynb
├── 03_algoritmos_geneticos.ipynb
└── requirements.txt
```

### 1. `02_algoritmos_busqueda_grafo.ipynb`

Introducción a los algoritmos clásicos de búsqueda sobre grafos.

Temas:

- Representación de problemas de búsqueda
- Frontier
- BFS (Breadth-First Search)
- DFS (Depth-First Search)
- Uniform Cost Search (UCS)
- Greedy Best-First Search
- A*
- Comparación de complejidad temporal y espacial

Incluye actividades para resolver durante la clase.

---

### 2. `02_busqueda_en_laberintos.ipynb`

Implementación de algoritmos de búsqueda sobre un laberinto.

Temas:

- Modelado de estados
- Acciones
- Función de transición
- Visualización de la exploración
- Comparación de algoritmos sobre el mismo problema

Incluye varias actividades que resolveremos durante la clase.

---

### 3. `01_hill_climbing.ipynb`

Implementación de Hill Climbing y Random Restart sobre un problema de ubicación óptima de hospitales.

Temas:
- Modelado de estados, vecinos y función objetivo
- Distancia Manhattan y distancia euclídea
- Algoritmo Hill Climbing
- Óptimos locales y Random Restart
- Comparación de vecindarios y análisis de convergencia

---

### 4. `03_algoritmos_geneticos.ipynb`

#### Objetivos

- representar soluciones mediante cromosomas;
- implementar selección, cruce y mutación;
- observar la evolución de una población;
- analizar el balance entre exploración y explotación.

# Análisis de complejidad

Para complementar la clase, el archivo [**complexity.md**](search_complexity.md) explica de manera intuitiva cómo se derivan las complejidades de tiempo y memoria de BFS, DFS, UCS, Greedy y A*.

---

# Descarga de los datos

El notebook **02_degrees_bfs.ipynb** requiere descargar un conjunto de datos.

Los datos pueden descargarse desde:

> **🔗 [link](https://drive.google.com/drive/folders/1hnI1x7DM4IX6BeMhPKLeQr9ZaVVHjPrc?usp=sharing)**

Una vez descargados, descomprima el archivo y ubique la carpeta de datos en el directorio indicado dentro del notebook.

---

# Objetivos de aprendizaje

Al finalizar esta práctica el estudiante será capaz de:

- Modelar un problema como un espacio de estados.
- Comprender el funcionamiento de la frontera (*frontier*).
- Implementar BFS y DFS.
- Comparar UCS, Greedy y A*.
- Analizar las diferencias en optimalidad, completitud, tiempo y memoria.
- Aplicar algoritmos de búsqueda a problemas reales.

---

# Referencias

- Stuart Russell & Peter Norvig. *Artificial Intelligence: A Modern Approach*. 4th Edition.
- Harvard CS50 AI – Search.
