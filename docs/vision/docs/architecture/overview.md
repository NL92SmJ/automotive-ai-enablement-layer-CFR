# Architecture Overview

The system is structured into four core layers:

1. **Data Ingestion Layer**  
   Connects to heterogeneous enterprise systems (ERP, MES, PLM, E/E architecture tools, logs) and normalizes data.

2. **Data Preparation & Feature Store**  
   Cleans, transforms, and enriches data into AI-ready features, including embeddings and structured representations.

3. **Use-Case Scoring Engine**  
   Evaluates potential AI use cases based on data availability, complexity, risk, and expected business value.

4. **AI Pipeline Builder**  
   Provides modular pipelines for training, inference, and integration into existing processes, with future GPU optimization in mind.
