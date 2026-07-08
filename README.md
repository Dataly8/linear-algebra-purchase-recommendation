# matematica_analitica
Caso práctico de álgebra lineal aplicada: cálculo de gasto y recomendación de compra mediante producto de matrices en Python.

# Sprint 1 — Aplicaciones del producto de matrices

Ejercicio del módulo *Matemáticas y estadística en el tratamiento de datos*.
Aplica el producto de matrices a un caso práctico de recomendación de compra.

## Problema

Tres personas (Rafa, Pedro y María) quieren comprar cuatro productos y pueden
elegir entre dos tiendas con precios distintos. El objetivo es calcular cuánto
gastaría cada persona en cada tienda y recomendar a cada una dónde comprar.

## Enfoque

El cálculo se resuelve como un **producto de matrices**:

- Matriz de **cantidades** (personas × productos), de dimensión 3×4.
- Matriz de **precios** (productos × tiendas), de dimensión 4×2.
- Su producto genera la matriz de **gasto** (personas × tiendas), de dimensión 3×2.

Cada celda del resultado combina, en una sola operación, la compra de una persona
con los precios de una tienda: cruza dos fuentes de datos y agrega el gasto total.

## Contenido del repositorio

- `sprint1_producto_matrices.ipynb`: notebook con el desarrollo completo
  (construcción de matrices, producto, presentación en tabla y recomendación).

## Herramientas

- Python (NumPy y pandas)
- Google Colab

## Conclusiones

- **Rafa** → Starbucks (49,0 €).
- **Pedro** → Manolo Bakes (58,5 €); las tartas son su factor diferencial.
- **María** → empate (43,5 € en ambas): el precio no decide, la recomendación
  pasa a basarse en calidad o conveniencia.

El caso de María ilustra que el dato ofrece la respuesta, pero la interpretación
aporta el criterio: un empate numérico requiere razonar más allá del precio.
