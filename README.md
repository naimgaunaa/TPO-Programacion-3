# Trabajo Práctico Cuatrimestral - Programación III

[cite_start]Este repositorio contiene la resolución del **Trabajo Práctico Cuatrimestral de Programación III**. [cite_start]El objetivo del trabajo es aplicar las principales técnicas de diseño de algoritmos (Divide & Conquer, Greedy y Programación Dinámica) a problemas concretos, además de aplicar el algoritmo de Floyd-Warshall para la resolución de un problema de grafos inventado[cite: 2, 3].

El proyecto incluye:
* [cite_start]**Pseudocódigo detallado** de cada solución[cite: 6, 81].
* [cite_start]**Análisis de complejidad temporal** (mejor, peor y promedio si aplica)[cite: 7, 82].
* [cite_start]**Implementación en código real** en [Mencionar el lenguaje de programación elegido, ej: Python/Java/C#][cite: 8, 88].
* [cite_start]**Comparación y conclusiones finales** sobre las técnicas y tiempos de ejecución[cite: 9, 91, 93].

---

## 💻 Contenido del Repositorio

[cite_start]El repositorio está organizado en cuatro partes principales, correspondientes a los problemas a resolver[cite: 10]:

### 1. Parte 1 - Divide & Conquer: Par de Puntos Más Cercanos

[cite_start]**Problema:** Encontrar el par de puntos a la menor distancia posible en un plano bidimensional con $n$ puntos[cite: 13, 14].

**Resoluciones Implementadas:**
* [cite_start]Solución ingenua ($O(n^2)$)[cite: 15].
* [cite_start]**Solución con Divide & Conquer**[cite: 16].

**Expectativas cumplidas:**
* [cite_start]Pseudocódigo del algoritmo[cite: 18].
* [cite_start]Explicación paso a paso de la solución D&C[cite: 19].
* [cite_start]Comparación de complejidad con la solución $O(n^2)$[cite: 20].
* [cite_start]Implementación con al menos 5 ejemplos de prueba[cite: 21].

***

### 2. Parte 2 - Greedy: Selección de Actividades

**Problema:** Seleccionar la **máxima cantidad** de actividades que no se superpongan, dada una lista de $n$ actividades con horarios de inicio y fin[cite: 24, 25].

**Expectativas cumplidas:**
* [cite_start]Pseudocódigo Greedy[cite: 27].
* [cite_start]Justificación de por qué funciona la elección Greedy[cite: 28].
* Análisis de Complejidad[cite: 29].
* [cite_start]Implementación en código real con casos de prueba[cite: 30].

***

### 3. Parte 3 - Programación Dinámica: Mochila 0/1 (Knapsack Problem)

**Problema:** Maximizar el valor total de objetos seleccionados sin exceder la capacidad de peso $W$ de una mochila, donde cada objeto tiene un peso $w_i$ y un valor $v_i$[cite: 32, 33, 34].

**Ejemplo de prueba:**
* [cite_start]Mochila con capacidad $W=10$[cite: 36].
* [cite_start]Objetos: O1 (peso 6, valor 30), O2 (peso 3, valor 14), O3 (peso 4, valor 16)[cite: 37, 38, 39, 40].
* Solución óptima: {O2, O3} con valor total de 30[cite: 41].

**Expectativas cumplidas:**
* [cite_start]Pseudocódigo del algoritmo[cite: 43].
* [cite_start]Análisis de Complejidad[cite: 44].
* Implementación con pruebas con diferentes capacidades y objetos[cite: 45, 46].

***

### 4. Parte 4 - Grafos: Algoritmo de Floyd-Warshall

**Problema:** Inventar un problema de la vida real modelado con un grafo ponderado y **resolverlo** utilizando el algoritmo de Floyd-Warshall[cite: 48, 49, 50].

**Objetivo:** Obtener las distancias más cortas **entre todos los pares de nodos** del grafo[cite: 50].

**Expectativas cumplidas:**
1.  **Modelado del problema:**
    * [cite_start]Descripción inventada del caso real[cite: 56].
    * [cite_start]Justificación del modelado como grafo[cite: 53].
    * Representación del grafo (matriz de adyacencia)[cite: 54].
2.  **Aplicación del algoritmo:**
    * [cite_start]Pseudocódigo de Floyd-Warshall[cite: 63].
    * [cite_start]Ejecución paso a paso sobre un ejemplo pequeño (4-5 nodos)[cite: 64].
    * Complejidad temporal[cite: 65].
3.  **Implementación en código real:**
    * [cite_start]Mostrar la tabla final de distancias mínimas[cite: 70].
4.  **Discusión:**
    * [cite_start]Explicación del significado de los resultados en el contexto inventado[cite: 74].

---

## 📂 Estructura del Proyecto
