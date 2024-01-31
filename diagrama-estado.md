```mermaid
---
title: Diagrama de estado - Luz
---
stateDiagram-v2
state Apagado
state Encendido
state Parpadeando

[*] --> Apagado
Apagado --> Encendido : Encender
Apagado --> Parpadeando : Parpadear
Parpadeando --> [*]
Encendido --> [*]
```
