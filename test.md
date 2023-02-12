```mermaid
flowchart TB
    subgraph Flow
        direction LR
        A --> B
        B --> C
    end
    subgraph API
        direction BT
        D{Something ?} -- Yes --> E
        D -- No --> F
        E --> G
    end
    Flow --> API