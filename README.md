# llama70b-circuits-chartdata  

This repository contains experiments exploring how **LLaMA 3.3 70B Instruct** processes **chart-structured data**. The goal is to analyze model internals (attention heads, residual streams, and circuits) to better understand how the model detects patterns such as maxima in tables and chart features.  

## Overview  
- **Model:** LLaMA 3.3 70B Instruct  
- **Focus:** Mechanistic interpretability & circuit analysis  
- **Data:** Synthetic and real-world chart/table datasets  
- **Methods:**  
  - Activation patching  
  - Attention head analysis  
  - Residual stream tracing  
  - Feature activation studies
 
## Tools & Dependencies
- PyTorch
- transformers
- nnsight (for interpretability experiments)
  - 0.4 or 0.5 (in process to update code for 0.5)
- matplotlib / seaborn for visualization
