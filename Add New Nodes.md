```mermaid
flowchart TD
B[Review current node coverage]
    B --> C[Check historical ride data]
    C --> D[Check NPZ / legal issues]
    D --> E[Analyse parking situation]
    E --> F[Estimate scooter capacity]
    F --> G[Add node with capacity]
    G --> H[Publish]
