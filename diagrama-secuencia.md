```mermaid
sequenceDiagram
  participant Cliente
  participant Sistema
  participant Proveedor

  Cliente->>Sistema: Seleccionar producto
  Sistema->>Proveedor: Consultar disponibilidad
  Proveedor-->>Sistema: Disponibilidad confirmada
  Sistema->>Cliente: Confirmar compra
  Cliente->>Sistema: Procesar pago
  Sistema->>Proveedor: Enviar producto
  Proveedor-->>Sistema: Producto enviado
  Sistema-->>Cliente: Recibir producto

```
