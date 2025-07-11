# Algoritmos de Optimización
## Máster en Inteligencia Artificial - VIU

### 📚 Descripción del Curso

Este repositorio contiene los trabajos prácticos y proyectos desarrollados para la asignatura **Algoritmos de Optimización** del Máster en Inteligencia Artificial de la Universidad Internacional de Valencia (VIU).

La asignatura abarca las principales técnicas algorítmicas para la resolución de problemas de optimización, desde algoritmos básicos hasta técnicas avanzadas aplicadas a problemas complejos del mundo real.

---

### 🗂️ Estructura del Repositorio

```
├── README.md                           # Este archivo
├── .gitignore                          # Archivos ignorados por Git
├── Algoritmos_AG1.ipynb               # Actividad Guiada 1
├── Algoritmos_AG2.ipynb               # Actividad Guiada 2
├── G3/
│   └── Algoritmos_AG3.ipynb           # Actividad Guiada 3
├── Proyecto/
│   ├── VIU-03MIAR-Trabajo_Práctico(1).pdf  # Enunciado del proyecto
│   ├── Seminario_Algoritmos.ipynb     # Proyecto desarrollado
│   └── Seminario_Algoritmos_plantilla.ipynb  # Plantilla del proyecto
```

---

### 📖 Contenido del Curso

#### 🎯 Actividad Guiada 1 - Técnicas Algorítmicas Fundamentales
**Archivo:** `Algoritmos_AG1.ipynb`

#### 🎯 Actividad Guiada 2 - Programación Dinámica Avanzada
**Archivo:** `Algoritmos_AG2.ipynb`

#### 🎯 Actividad Guiada 3 - Algoritmos de Optimización Avanzada
**Archivo:** `G3/Algoritmos_AG3.ipynb`

**Contenido:**
- **Problema del Viajante (TSP)**
  - Uso de librerías especializadas (tsplib95)
  - Carga de datasets reales (swiss42.tsp)
  - Implementación de algoritmos de optimización
  - Análisis de resultados y comparación de técnicas

#### 🎯 Proyecto Final - Seminario de Algoritmos
**Archivo:** `Proyecto/Seminario_Algoritmos.ipynb`

**Opciones de Problemas:**
1. **Programación de Sesiones de Doblaje**
---

### 🛠️ Técnicas Algorítmicas Estudiadas

| Técnica | Descripción | Problemas Ejemplo |
|---------|-------------|------------------|
| **Divide y Vencerás** | Descompone problema en subproblemas más pequeños | Torres de Hanoi, Fibonacci |
| **Técnica Voraz** | Selecciona la mejor opción local en cada paso | Cambio de monedas, Scheduling |
| **Vuelta Atrás** | Explora sistemáticamente el espacio de soluciones | N-Reinas, Sudoku |
| **Programación Dinámica** | Optimiza mediante soluciones de subproblemas | Viaje por río, Knapsack |
| **Algoritmos de Grafos** | Optimización en estructuras de red | TSP, Caminos mínimos |

---

### 🔧 Herramientas y Librerías

- **Python 3.x**: Lenguaje principal de implementación
- **Jupyter Notebook**: Entorno de desarrollo interactivo
- **NumPy**: Computación numérica
- **Matplotlib**: Visualización de datos
- **tsplib95**: Problemas estándar de TSP
- **requests**: Descarga de datasets

---

### 📊 Complejidad Algorítmica

| Algoritmo | Complejidad Temporal | Complejidad Espacial | Observaciones |
|-----------|---------------------|---------------------|---------------|
| Torres de Hanoi | O(2^n) | O(n) | Exponencial, recursión |
| Fibonacci (recursivo) | O(2^n) | O(n) | Ineficiente, muchas recalculaciones |
| Cambio Voraz | O(n) | O(1) | Óptimo para monedas canónicas |
| N-Reinas | O(n!) | O(n²) | Backtracking, podado |
| Prog. Dinámica | O(n²) - O(n³) | O(n²) | Depende del problema |

---

### 🎯 Objetivos de Aprendizaje

1. **Comprender** las principales técnicas algorítmicas de optimización
2. **Implementar** algoritmos eficientes para problemas complejos
3. **Analizar** la complejidad temporal y espacial de los algoritmos
4. **Aplicar** técnicas de optimización a problemas reales
5. **Evaluar** la eficiencia y optimalidad de las soluciones
6. **Desarrollar** habilidades de resolución de problemas algorítmicos

---

### 🚀 Cómo Usar Este Repositorio

1. **Clonar el repositorio:**
   ```bash
   git clone [URL_DEL_REPOSITORIO]
   cd algoritmos-optimizacion
   ```

2. **Instalar dependencias:**
   ```bash
   pip install jupyter numpy matplotlib requests tsplib95
   ```

3. **Ejecutar los notebooks:**
   ```bash
   jupyter notebook
   ```

4. **Explorar los contenidos:**
   - Comenzar con `Algoritmos_AG1.ipynb` para fundamentos
   - Continuar con `Algoritmos_AG2.ipynb` para programación dinámica
   - Avanzar a `G3/Algoritmos_AG3.ipynb` para TSP
   - Revisar `Proyecto/Seminario_Algoritmos.ipynb` para el proyecto final

---

### 📚 Referencias Bibliográficas

- Cormen, T. H., Leiserson, C. E., Rivest, R. L., & Stein, C. (2009). *Introduction to Algorithms*
- Dasgupta, S., Papadimitriou, C., & Vazirani, U. (2006). *Algorithms*
- Kleinberg, J., & Tardos, E. (2005). *Algorithm Design*
- Documentación oficial de Python y librerías utilizadas

---

### 👨‍💻 Autor

**Estudiante**: William David Vasquez Parada
**Programa**: Máster en Inteligencia Artificial  
**Universidad**: Universidad Internacional de Valencia (VIU)  
**Curso**: 2025-2026