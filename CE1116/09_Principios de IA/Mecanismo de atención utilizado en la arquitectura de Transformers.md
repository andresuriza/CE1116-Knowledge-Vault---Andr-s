---
Fecha de creación: 2025-08-06 16:59
Fecha de Modificación: 2025-08-06 16:59
tags:
  - inteligencia-artificial
Topic:
  - LLM
---

## 📚 Idea/Concepto 


Los mecanismos de atención en los Transformers buscan dirigir la atención a los tokens más importantes para contextualizar la respuesta, esto mediante los vectores de Query, Key y Value, la relevancia del token se determina mediante una compatibilidad entre query y key, se realiza un producto punto entre Query y Key, el factor escalado de este resultado seguido de la función Softmax determina su peso correspondiente, generando así una matriz de atención la cual pondera el vector Value, sumándolo al embedding original, el cual ya contiene la codificación posicional, para actualizarlos y enriquecer el contexto. Estos mecanismos también utilizan la atención multi-cabeza para procesar relaciones contextuales en paralelo y simultáneamente.

## 🔗 Connections

- [[Tokenización]]
- [[Redes Neuronales]]
