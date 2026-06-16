```mermaid
graph LR
    A[Raw Data Ingestion] --> B[Preprocessing Block]
    B --> C[LSTM Hidden Layers]
    C --> D[Dense Activation Layer]
    D --> E[Prediction Output]

    classDef default fill:#ffffff,stroke:#475569,color:#1e293b,stroke-width:2px;
