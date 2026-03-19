This is a small project created for learning distributed systems and practicing system designs.

High-level design:

flowchart TD

A[Client] --> B[Backend API]
B --> C[Matching Engine]
C --> D[(Database)]
C --> E[(Cache - Redis)]
E --> F[WebSocket]
F --> A