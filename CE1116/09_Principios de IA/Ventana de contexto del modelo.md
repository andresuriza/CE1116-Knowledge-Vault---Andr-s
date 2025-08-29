---
Fecha de creación: 2025-08-06 16:59
Fecha de Modificación: 2025-08-06 16:59
tags:
  - inteligencia-artificial
Topic:
  - LLM
---

## 📚 Idea/Concepto 


La ventana de contexto de un modelo representa el límite de tokens que se pueden procesar simultáneamente para realizar una predicción. Si se excede esta ventana, se reduce la capacidad del modelo de recordar entradas pasadas, debe paginar los tokens antiguos en base al orden definido por las codificaciones posicionales, los cuales son sumados a los embeddings de entrada en las capas iniciales del transformer, y esto puede afectar la coherencia de las respuestas. Aumentar la ventana de contexto por lo tanto mejora la capacidad de obtener resultados más coherentes y relevantes, sin embargo, esto tiene implicaciones de recursos y de tiempo de entrenamiento, por lo que significa un cuello de botella.

## 🔗 Connections

- [[Tokenización]]
- [[Embeddings]]
