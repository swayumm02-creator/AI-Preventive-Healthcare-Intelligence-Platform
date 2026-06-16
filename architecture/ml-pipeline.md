```markdown
```mermaid
graph LR
    classDef step fill:#fff,stroke:#475569,color:#1e293b,stroke-width:2px;
    
    A["Raw Data Ingestion <br> (Time-Series & Text)"]:::step --> 
    B["Preprocessing Block <br> (Vector Packaging & Scaling)"]:::step --> 
    C["LSTM Hidden Layers <br> (Sequential Vector Evaluation)"]:::step --> 
    D["Dense Activation Layer <br> (Multidimensional Reduction)"]:::step --> 
    E["Prediction Output <br> (JSON Response Payload)"]:::step
