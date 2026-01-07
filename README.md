### Hi there 👋 I'm Tahir

I'm a Computer Science Student @ Unimi focusing on AI & Cloud.

### 🔒 My Private Projects (Available upon request)

Although the source code for some of these projects is private, here is a detailed overview of what I have built:

- **🌍 Climate Monitoring System (Java RMI Distributed App)**
  - *Tech:* Java, Java RMI, Swing (GUI), PostgreSQL (JDBC), Design Patterns (Adapter, Proxy)
  - *Context:* Academic Project "Laboratorio B" (University of Insubria)
  - *Description:* A distributed Client-Server application for monitoring global climate parameters.
    - **Architecture:** Built on **Java RMI** middleware to enable remote method invocation between client and server components.
    - **Features:** Implemented advanced search algorithms (Coordinate-based proximity, Name matching) and role-based access (Citizen vs Operator).
    - **GUI:** Developed a responsive Swing interface using **CardLayout** for navigation and custom CellEditors for data integrity.
    - **Persistence:** Designed a robust PostgreSQL schema with automatic table initialization and checking.

- **🔐 Secure IoT Microservices System (Bachelor Thesis)**
  - *Tech:* Node.js, MongoDB, OpenSSL (AES-256 + ECC), REST APIs
  - *Context:* Bachelor's Degree Thesis (University of Insubria)
  - *Description:* A distributed architecture for Smart Building monitoring (CO2/Temp) designed to balance robust security with system performance.
    - **Architecture:** Developed 5 interacting microservices including a custom **Certificate Authority (CA)** and a Data Visualization gateway.
    - **Security:** Implemented **Hybrid Cryptography** (AES-256 for high-volume data, ECC for key exchange) and strict **RBAC** logic.
    - **Outcome:** Benchmarked the system to prove that high-security standards introduced negligible latency overhead.

- **🧠 Quantifying Cultural Alignment in LLMs (NLP Research)**
  - *Tech:* Python, PyTorch, Transformers (Hugging Face), Qwen 2.5, Phi-3
  - *Context:* Academic Research (Natural Language Processing Course)
  - *Description:* A quantitative investigation into performance discrepancies of LLMs between High-Resource (Chinese) and Low-Resource (Yoruba) languages.
    - **Methodology:** Applied **Shannon Entropy** to Softmax output distributions to measure model uncertainty.
    - **Key Finding:** Demonstrated how **BPE Tokenization** causes structural failures ("Nigeria Failure") by fragmenting low-resource terms.
    - **Outcome:** Proved that Persona Prompting (Bayesian Inference) fails to correct structural biases in low-resource contexts.

- **🫀 Advanced ECG Signal Decomposition (Biomedical Engineering)**
  - *Tech:* Python, Deep Learning (1D U-Net), TensorFlow/Keras, Signal Processing (SciPy)
  - *Context:* Academic Project (Biomedical Signal Processing Course)
  - *Description:* A comparative study shifting ECG processing from frequency filtering to **Semantic Segmentation** to resolve spectral overlap.
    - **The Problem:** Addressed the physical limitation of frequency-based filters (Fourier/Butterworth) in separating overlapping P-QRS-T wave spectra.
    - **The Solution:** Architected a **1D U-Net** (Encoder-Decoder) to reconstruct waveforms based on temporal context, achieving artifact-free segmentation.
    - **Outcome:** Outperformed mathematical models by eliminating **Gibbs phenomenon** and preserving T-wave morphology on the MIT-BIH database.

- **🧬 PDAC Multi-Omic Integration (Scientific Visualization)**
  - *Tech:* Python, Similarity Network Fusion (SNF), Scikit-learn (PCA, Random Forest), Lifelines (Survival Analysis)
  - *Context:* Academic Assignment (Scientific Visualization Course)
  - *Description:* A comparative analysis of multi-omic integration strategies (mRNA, miRNA, Proteomics) for Pancreatic Cancer subtyping.
    - **Methodology:** Contrasted **Latent Factor Analysis (PCA)** against **Similarity Network Fusion (SNF)** to handle heterogeneous biological noise.
    - **Key Finding:** Demonstrated that Network Fusion recovers robust subtypes driven by **post-transcriptional regulation (miRNAs)**.
    - **Validation:** Quantified cluster stability via Silhouette Score and biological drivers via **Random Forest** feature importance.

- **📊 Automotive Data Analysis (Scientific Visualization)**
  - *Tech:* Python, Scikit-learn (PCA, K-Means), Pandas, Matplotlib/Seaborn
  - *Context:* Academic Assignment (Scientific Visualization Course)
  - *Description:* A computational analysis pipeline applied to the Auto MPG dataset to identify vehicle segments.
    - **Techniques:** Implemented **PCA** for dimensionality reduction and **K-Means** for clustering (optimized via Silhouette Score).
    - **Validation:** Verified cluster significance using statistical methods (**Kruskal-Wallis H-test**).
    - **Visualization:** Generated 2D/3D scatter plots and heatmaps to interpret high-dimensional relationships.

- **📱 Android Social App**
  - *Tech:* Kotlin, Firebase, Android Studio
  - *Description:* A fully functional native social network app featuring real-time feeds, user authentication, and media handling.

---
[Visit my Portfolio Website for more details](https://tahiragalliu.vercel.app/)
