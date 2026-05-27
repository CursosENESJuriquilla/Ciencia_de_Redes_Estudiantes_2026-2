# Proyecto final Diego Trejo Gómez ciencia de redes - Redes de Sistemas Culinarios
Bueno para correr el codigo se necesitan las dependecias basicas, pandas, numpy, matplotlib, pandas, itertools
y networkx, ademas de python y jupyter


Este proyecto analiza redes complejas construidas a partir de recetas e ingredientes de distintas regiones del mundo, principalmente África y Latinoamérica.  

El objetivo es estudiar las propiedades estructurales de estas redes culinarias utilizando herramientas de teoría de grafos y análisis de redes complejas.

---

# Objetivos

- Construir redes de ingredientes a partir de recetas.
- Comparar propiedades estructurales entre regiones.
- Identificar ingredientes importantes mediante medidas de centralidad.
- Detectar comunidades de ingredientes.
- Comparar las redes reales con modelos aleatorios clásicos.

---

# Datos Utilizados

Las redes fueron construidas utilizando conjuntos de recetas regionales.

Cada nodo representa un ingrediente y cada arista representa la coocurrencia de dos ingredientes dentro de una receta.

Se analizan aspectos como:

- Número total de recetas.
- Número de ingredientes distintos.
- Tamaño promedio de las recetas.
- Ingredientes más frecuentes.

---

# Análisis de Redes

## Propiedades Básicas

Se calcularon diversas métricas de teoría de redes:

- Número de nodos y aristas.
- Densidad de la red.
- Componentes conexas.
- Componente gigante.
- Distribución de grados.
- Grado promedio.
- Coeficiente de clustering.
- Distancia promedio.
- Diámetro de la red.

---

## Centralidades

Para identificar ingredientes importantes se utilizaron distintas medidas de centralidad:

- Centralidad de grado.
- Centralidad de cercanía.
- Centralidad de intermediación.
- Eigenvector centrality.
- PageRank.
- Katz centrality.

Estas métricas permiten identificar ingredientes fundamentales dentro de cada cocina regional.

---

## Detección de Comunidades

El proyecto también analiza la estructura modular de las redes mediante algoritmos de detección de comunidades.

Se estudian:

- Comunidades de ingredientes.
- Modularidad.
- Relación entre comunidades y patrones culinarios regionales.

---

# Comparación con Modelos Aleatorios

Las redes reales fueron comparadas con modelos clásicos de redes:

- Modelo Erdős–Rényi.
- Modelo Small World.
- Modelo Barabási–Albert.

La comparación sugiere que las redes culinarias presentan:

- Estructuras no completamente aleatorias.
- Presencia de hubs importantes.
- Comportamientos similares a redes libres de escala.

---

# Visualización

El notebook incluye visualizaciones de:

- Redes completas.
- Ingredientes importantes.
- Distribuciones de grado.
- Comunidades detectadas.
- Comparaciones entre regiones.

---

# Regiones Analizadas

El análisis se realizó principalmente sobre:

- África.
- Latinoamérica.

Posteriormente se realizó una comparación entre ambas regiones.

---

# Herramientas Utilizadas

- Python
- NetworkX
- Pandas
- NumPy
- Matplotlib


