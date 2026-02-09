flowchart TD
    A[Start] --> B[Review current node coverage<br/>and identify gaps]
    B --> C[Check historical ride data<br/>to understand demand]
    C --> D{Is demand sufficient?}
    D -- No --> Z[Do not add node<br/>(revisit later)] --> I[End]
    D -- Yes --> E[Check NPZ / legal issues]
    E --> F{Any blocking legal issues?}
    F -- Yes --> Z
    F -- No --> G[Analyse parking situation]
    G --> H{Is parking feasible/safe?}
    H -- No --> Z
    H -- Yes --> J[Check location to estimate<br/>how many scooters fit]
    J --> K[Add node with decided capacity]
    K --> L[Publish node]
    L --> I[End]
