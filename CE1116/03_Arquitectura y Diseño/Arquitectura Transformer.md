---
Fecha de creación: 2026-03-10 19:34
Fecha de Modificación: 2026-03-10 19:34
tags:
  - arquitectura
Tema: IA
---
## 📚 Idea/Concepto 
La arquitectura Transformer es un tipo de red neuronal basada casi por completo en el mecanismo de atención, organizada en bloques de codificador y decodificador apilados, que procesa secuencias en paralelo (no paso a paso como una RNN).

## 📌 Puntos Claves (Opcional)
- Su gran ventaja es que permite entrenar y procesar secuencias largas en paralelo, aprovechando muy bien la GPU y capturando dependencias a largo plazo.  
- Es la base de modelos modernos de IA generativa (BERT, GPT, LLaMA, etc.), tanto para texto como para visión y otros dominios.    
- La calidad depende del diseño (número de capas, cabezas de atención, tamaño de los embeddings) y de la cantidad de datos de entrenamiento.    
- Muchos modelos actuales usan solo el encoder (BERT‑like), solo el decoder (GPT‑like) o variantes simplificadas del Transformer original.

## 🔗 Connections
- [[Product Backlog]]
- [[Redes Neuronales]]
- [[Función de Activación]]

## 💡 Personal Insight (Opcional)
- Para mí, un Transformer está realmente “hecho” cuando su entrenamiento es reproducible, la arquitectura está documentada (capas, cabezas, dimensiones) y demuestra una mejora clara frente a una RNN o CNN en la tarea del proyecto.
## 🧾 Recursos (Opcional)
- 