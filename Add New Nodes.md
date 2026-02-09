flowchart TD
    A[Start] --> B[Review current node coverage<br/>and identify gaps]
    B --> C[Check historical ride data<br/>to understand demand]
    C --> D[Check NPZ / legal issues]
    D --> E[Analyse parking situation<br/>in the area]
    E --> F[Check location to estimate<br/>how many scooters fit]
    F --> G[Add node with decided capacity]
    G --> H[Publish node]
    H --> I[End]
