---
Fecha de creación: 2026-03-10 19:45
Fecha de Modificación: 2026-03-10 19:45
tags:
  - implementación
Tema: IA
---
## 📚 Idea/Concepto 
La ventana de contexto es la cantidad máxima de tokens (fragmentos de texto) que un modelo como un Transformer puede tener “en mente” al mismo tiempo mientras procesa o genera una respuesta.

## 📌 Puntos Claves (Opcional)
- ## untos Claves (Opcional)

- Es análoga a la memoria de trabajo humana: puedes recordar cierta cantidad de información mientras piensas, pero no todo lo que has visto en tu vida.    
- La eficiencia de la tokenización influye directamente en cuánta información real cabe en esa ventana: menos tokens por texto ⇒ más contenido dentro del mismo límite.    
- La ventana interactúa con el mecanismo de atención: la atención solo puede “mirar” hasta el número de tokens que entran en esa ventana.    
- Ventanas muy grandes también amplían la superficie para instrucciones maliciosas o ruido dentro del contexto.

## 🔗 Connections
- [[Product Backlog]]
- [[Pruebas Funcionales]]
- [[Tokenización]]
- [[Redes Neuronales]]
- [[Arquitectura Transformer]]

## 💡 Personal Insight (Opcional)
- En la práctica, la ventana de contexto es el “presupuesto de memoria” que tienes en cada llamada al modelo; diseñar bien cómo lo gastas (resúmenes, chunks, RAG) suele ser tan importante como elegir el modelo mismo.
## 🧾 Recursos (Opcional)
- 