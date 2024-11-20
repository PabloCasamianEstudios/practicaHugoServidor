+++
date = '2024-11-13T20:18:08+01:00'
draft = false
title = 'Gráficos Markdown'
+++


<!-- TD -> Top-Down LR -> Left-Right -->
# Graficos
{{< mermaid >}}
graph LR;  
A[Limones]-->B[Limonada];
B-->C[Beneficio]
{{< /mermaid >}}

---

{{< mermaid >}}
graph TD;
    A--> B
    B --> C
    C -->|Sí| D
    C -->|No| A
{{< /mermaid >}}

---
# Diagrama de secuencia
{{< mermaid >}}
sequenceDiagram
    A->>B: Solicitud
    B-->>A: Respuesta
{{< /mermaid >}}