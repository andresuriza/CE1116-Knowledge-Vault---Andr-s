---
Fecha de creación: 2025-08-06 16:59
Fecha de Modificación: 2025-08-06 16:59
tags:
Topic:
---

## 📚 Idea/Concepto 


El broker en arquitecturas event-driven es el canal central que gestiona el flujo de mensajes de manera asíncrona. Funciona como un intermediario que permite que los productores envíen eventos mediante un broadcast y utilizando el modelo Pub/Sub, y es una topología ideal ya que carece de coordinación centralizada. Este recibe datos de eventos y puede crear un registro de estos mediante un log, lo que permite que se puedan repetir los eventos y que los datos sean persistentes, busca proporcionar un desacoplamiento muy bajo entre los componentes de procesamiento, además de que se utiliza un componente mediador/orquestador para controlar el flujo de trabajo.
## 🔗 Connections


