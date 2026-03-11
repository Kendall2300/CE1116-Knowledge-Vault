---
Fecha de creación: 2026-03-10 19:31
Fecha de Modificación: 2026-03-10 19:31
tags:
  - arquitectura
Tema: IA
---
## 📚 Idea/Concepto 
Una función de activación es la operación matemática que aplica cada neurona a la suma ponderada de sus entradas para decidir qué valor pasa a la siguiente capa. Sin esa transformación, la red sería solo una combinación lineal y no podría aprender patrones complejos.

## 📌 Puntos Claves (Opcional)
- Funciones típicas: Sigmoid y Tanh en salidas o capas poco profundas, ReLU y variantes (Leaky ReLU, GELU) en capas ocultas, Softmax en la capa de salida para clasificación multiclase.
- La elección de la función de activación impacta directamente precisión, velocidad de entrenamiento y estabilidad numérica.
- Si todas las neuronas usaran funciones lineales, varias capas se colapsarían a una sola capa lineal, perdiendo toda la potencia del deep learning.
- Cambiar la función de activación puede ser una mejora de arquitectura tan importante como cambiar el número de capas o neuronas.

## 🔗 Connections
- [[Product Backlog]]
- [[Pruebas Funcionales]]

## 💡 Personal Insight (Opcional)
- Para mí, una red no está realmente “hecha” hasta que la función de activación elegida demuestra, con experimentos, que entrena establemente y mejora las métricas frente a alternativas simples.
## 🧾 Recursos (Opcional)
- 