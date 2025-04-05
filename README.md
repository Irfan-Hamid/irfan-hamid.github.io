<!-- Navigation Bar -->
<nav style="position: sticky; top: 0; background-color: #ffffff; padding: 12px 20px; font-family: sans-serif; font-size: 16px; z-index: 999; border-bottom: 1px solid #ccc; white-space: nowrap; overflow-x: auto; display: flex; min-width: 100%;">
  <a href="#education" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Education</a>
  <a href="#experience" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Experience</a>
  <a href="#projects" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Projects</a>
  <a href="#skills" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Skills</a>
  <a href="#contact" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Contact</a>
  <a href="/assets/resume/Irfan_Resume.pdf" download style="text-decoration: none; font-weight: bold; color: #333;">Resume</a>
</nav>

<!-- CSS -->
<style>
  details {
    transition: all 0.3s ease-in-out;
    overflow: hidden;
    margin-bottom: 12px;
    padding: 8px 12px;
    border-left: 3px solid #ccc;
    background-color: #f9f9f9;
    border-radius: 4px;
  }
  details[open] summary ~ * {
    animation: slideDown 0.3s ease-in-out;
  }
  @keyframes slideDown {
    0% { opacity: 0; transform: translateY(-5px); }
    100% { opacity: 1; transform: translateY(0); }
  }
  summary {
    cursor: pointer;
    font-weight: 600;
  }
</style>

<a id="education"></a>
<div style="height: 120px;"></div>
## <span style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Education</span>

- **The University of Edinburgh, Edinburgh, UK**  
  *MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*
- **Vellore Institute of Technology (VIT), Vellore, India**  
  *BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

<a id="experience"></a>
<div style="height: 120px;"></div>
## <span style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</span>

- **Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station, Edinburgh, UK**  
  *Student Researcher – March 2024 to August 2024*  
  <img src="assets/img/ForestResearch.jpg" alt="Forest Research Logo" style="height: 40px; margin-top: 6px; display: block;">
  <details><summary>View Details</summary><br>
  <ul>
    <li>Conducted industry-partnered machine learning research for MSc dissertation, classifying tree species using multispectral satellite imagery from Planet Labs’ SuperDove 8 satellites.</li>
    <li>Developed deep learning models (ResNet-34, DenseNet-40, Vision Transformers) and used QGIS for geospatial preprocessing and spatial analysis of tree labels.</li>
    <li>Performed evaluation and explanation of model predictions via species spectral curves, advancing forestry classification through AI-driven remote sensing.</li>
  </ul>
  </details>

- **Wipro Limited, Chennai, India**  
  *SAP BW Consultant – July 2021 to June 2023*  
  <img src="assets/img/WIPRO.jpeg" alt="Wipro Logo" style="height: 40px; margin-top: 6px; display: block;">
  <details><summary>View Details</summary><br>
  <ul>
    <li>Designed SAP BW process chains for Nomad Foods Europe, enhancing automation, reducing manual overhead, and improving data reliability.</li>
    <li>Built SAP BW queries and models with aDSOs and composite providers, aligned with business KPIs to enable actionable reporting.</li>
    <li>Implemented BW/4HANA provisioning and optimized ETL workflows to support business intelligence performance.</li>
  </ul>
  </details>

<a id="projects"></a>
<div style="height: 120px;"></div>
## <span style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

- **Non-Self-Referential Attention in Transformers**  
  <a href="https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Developed Non-Self-Referential Attention to reduce main diagonal dominance in attention matrices.</li>
    <li>Applied to English–Portuguese translation (opus_books dataset), achieving 2.12% BLEU score improvement over baseline.</li>
  </ul>
  </details>

- **Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search**  
  <a href="https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Built a RAG pipeline with embedding-based retrieval for answering textbook questions via LLM (GEMMA-7B-it).</li>
    <li>Processed textbook PDFs, chunked and embedded content, performed vector search, and generated accurate responses.</li>
  </ul>
  </details>

- **Multi-Label Learning from Single Positive Labels**  
  <a href="https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Explored SPMLL (Single Positive Multi-Label Learning) where training labels are incomplete per instance.</li>
    <li>Developed a UPL (Up-weighting Positive Label) loss function that improved metrics by 72% over binary cross-entropy.</li>
    <li>Applied to ecological SDM datasets where species presence is observed sparsely, leveraging spatial cues for full label inference.</li>
  </ul>
  </details>

- **Evaluating the Robustness of Classical ML vs Deep Learning**  
  <a href="https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Benchmarked AlexNet against Random Forest and SVM on clean vs noisy Sports Balls dataset (Kaggle).</li>
    <li>Tested noise, blur, occlusion, and contrast perturbations — AlexNet showed stronger robustness and generalization.</li>
  </ul>
  </details>

<a id="skills"></a>
<div style="height: 120px;"></div>
## <span style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</span>

- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, SQL, OpenCV, spaCy, NLTK, Transformers (Hugging Face), LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Deep Learning (Transformers, CNNs, RNNs, VAEs, GANs), Bayesian Inference, Supervised/Unsupervised Learning, Computer Vision, NLP, LLM Fine-Tuning (LoRA), RAG, LLM Compression

<a id="contact"></a>
<div style="height: 120px;"></div>
## <span style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Contact</span>

📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)
