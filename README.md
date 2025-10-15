# Trabajo Práctico Cuatrimestral - Programación III

Este repositorio contiene la resolución del **Trabajo Práctico Cuatrimestral de Programación III**. El objetivo del trabajo es aplicar las principales técnicas de diseño de algoritmos (Divide & Conquer, Greedy y Programación Dinámica) a problemas concretos, además de aplicar el algoritmo de Floyd-Warshall para la resolución de un problema de grafos inventado.

El proyecto incluye:
* **Pseudocódigo detallado** de cada solución.
* **Análisis de complejidad temporal** (mejor, peor y promedio si aplica).
* **Implementación en código real** en Python.
* **Comparación y conclusiones finales** sobre las técnicas y tiempos de ejecución.

---

## 💻 Contenido del Repositorio

El repositorio está organizado en cuatro partes principales, correspondientes a los problemas a resolver:

### 1. Parte 1 - Divide & Conquer: Par de Puntos Más Cercanos

**Problema:** Encontrar el par de puntos a la menor distancia posible en un plano bidimensional con $n$ puntos.

**Resoluciones Implementadas:**
* Solución ingenua ($O(n^2)$).
* **Solución con Divide & Conquer**.

**Expectativas cumplidas:**
* Pseudocódigo del algoritmo.
* Explicación paso a paso de la solución D&C.
* Comparación de complejidad con la solución $O(n^2)$.
* Implementación con al menos 5 ejemplos de prueba.

***

### 2. Parte 2 - Greedy: Selección de Actividades

**Problema:** Seleccionar la **máxima cantidad** de actividades que no se superpongan, dada una lista de $n$ actividades con horarios de inicio y fin.

**Expectativas cumplidas:**
* Pseudocódigo Greedy.
* Justificación de por qué funciona la elección Greedy.
* Análisis de Complejidad.
* Implementación en código real con casos de prueba.

***

### 3. Parte 3 - Programación Dinámica: Mochila 0/1 (Knapsack Problem)

**Problema:** Maximizar el valor total de objetos seleccionados sin exceder la capacidad de peso $W$ de una mochila, donde cada objeto tiene un peso $w_i$ y un valor $v_i$.

**Ejemplo de prueba:**
* Mochila con capacidad $W=10$.
* Objetos: O1 (peso 6, valor 30), O2 (peso 3, valor 14), O3 (peso 4, valor 16).
* Solución óptima: {O2, O3} con valor total de 30.

**Expectativas cumplidas:**
* Pseudocódigo del algoritmo.
* Análisis de Complejidad.
* Implementación con pruebas con diferentes capacidades y objetos.

***

### 4. Parte 4 - Grafos: Algoritmo de Floyd-Warshall

**Problema:** Inventar un problema de la vida real modelado con un grafo ponderado y **resolverlo** utilizando el algoritmo de Floyd-Warshall.

**Objetivo:** Obtener las distancias más cortas **entre todos los pares de nodos** del grafo.

**Expectativas cumplidas:**
1.  **Modelado del problema:**
    * Descripción inventada del caso real.
    * Justificación del modelado como grafo.
    * Representación del grafo (matriz de adyacencia).
2.  **Aplicación del algoritmo:**
    * Pseudocódigo de Floyd-Warshall.
    * Ejecución paso a paso sobre un ejemplo pequeño (4-5 nodos).
    * Complejidad temporal.
3.  **Implementación en código real:**
    * Mostrar la tabla final de distancias mínimas.
4.  **Discusión:**
    * Explicación del significado de los resultados en el contexto inventado.

---
