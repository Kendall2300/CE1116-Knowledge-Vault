---
Fecha de creación: 2025-08-05 00:10
Fecha de Modificación: 2025-08-05 00:10
tags:
  - "#arquitectura"
Topic:
  - estilos-arquitectura-software
---


## 📚 Idea/Concepto 
Estilo de arquitectura donde una aplicación se construye como un conjunto de servicios pequeños, independientes y poco acoplados, cada uno encargado de una función de negocio específica y que se comunican entre sí mediante APIs bien definidas.

## 📌 Puntos Claves (Opcional)
- Cada microservicio puede desarrollarse, desplegarse y escalarse de forma independiente sin afectar a los demás.
- Cada servicio suele tener su propio almacenamiento de datos o estado, evitando dependencias fuertes con una base de datos central única.
- Facilitan la evolución del sistema: se puede cambiar una parte sin reescribir toda la aplicación, incluso usando diferentes tecnologías por servicio.
- Suelen reemplazar a arquitecturas monolíticas donde todo está en un solo bloque difícil de escalar y mantener.

## 🔗 Connections
- [[Requerimentos no Funcionales]]

## 💡 Personal Insight (Opcional)
- Varios servicios pequeños que juntos forman la app completa
## 🧾 Recursos (Opcional)
- 