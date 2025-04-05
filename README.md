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
  :target {
    scroll-margin-top: 80px;
  }
</style>

## <span id="education" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Education</span>

- **The University of Edinburgh, Edinburgh, UK**  
  *MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*
- **Vellore Institute of Technology (VIT), Vellore, India**  
  *BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

## <span id="experience" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</span>

- **Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station**  
  *Student Researcher – March 2024 to August 2024*  
  <img src="assets/img/ForestResearch.jpg" alt="Forest Research Logo" style="height: 40px; margin-top: 6px; display: block;">
  <details><summary>View Details</summary><br>
  <ul>
    <li>Conducted machine learning research with Forest Research, focusing on classifying tree species using high-resolution multispectral satellite imagery.</li>
    <li>Trained ResNet-34, DenseNet-40, and Vision Transformers (ViT) for species classification and used QGIS for preprocessing and analysis.</li>
    <li>Compared model performance and used species spectral curves to interpret predictions for precision forestry applications.</li>
  </ul>
  </details>

- **Wipro Limited, Chennai, India**  
  *SAP BW Consultant – July 2021 to June 2023*  
  <img src="assets/img/WIPRO.jpeg" alt="Wipro Logo" style="height: 40px; margin-top: 6px; display: block;">
  <details><summary>View Details</summary><br>
  <ul>
    <li>Built optimized SAP BW process chains and aDSO models to improve automation and data integration for Nomad Foods Europe Limited.</li>
    <li>Created SAP queries aligned to KPIs for accurate and actionable reports.</li>
    <li>Implemented SAP BW/4HANA provisioning and ETL flows to boost BI performance and decision-making efficiency.</li>
  </ul>
  </details>

## <span id="projects" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

- **Non-Self-Referential Attention in Transformers**  
  <a href="https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Explored Transformer architecture changes and introduced Non-Self-Referential Attention.</li>
    <li>Downweighted diagonal self-attention to promote diverse token interactions and improve translation accuracy.</li>
    <li>Achieved a 2.12% BLEU improvement on the opus_books 'en-pt' translation task.</li>
  </ul>
  </details>

- **Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search**  
  <a href="https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Built a pipeline to let LLMs query textbook PDFs using retrieval-augmented generation.</li>
    <li>Embedded and indexed textbook chunks for semantic search based on user queries.</li>
    <li>Used GEMMA-7B-it LLM to generate context-aware answers with retrieved knowledge.</li>
  </ul>
  </details>

- **Multi-Label Learning from Single Positive Labels**  
  <a href="https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Addressed learning from presence-only data using deep learning and single-positive supervision.</li>
    <li>Focused on species distribution modeling where only observed species locations are recorded.</li>
    <li>Formulated it as Single Positive Multi-Label Learning (SPML), inferring complete labels from single-class training.</li>
    <li>Introduced the UPL (Up-weighting Positive Label) loss to improve learning under weak supervision.</li>
    <li>UPL yielded a 72% improvement over binary cross-entropy in ecological datasets.</li>
  </ul>
  </details>

- **Evaluating the Robustness of Classical ML vs Deep Learning**  
  <a href="https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification" target="_blank">
    <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
  </a>
  <details><summary>View Details</summary><br>
  <ul>
    <li>Compared SVM and Random Forest vs AlexNet on clean and perturbed sports image data.</li>
    <li>Applied distortions like noise, blur, brightness/contrast changes, occlusion, and salt-pepper noise.</li>
    <li>Showed classical models degrade faster under noise, while deep learning models generalize better.</li>
  </ul>
  </details>

## <span id="skills" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</span>

- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, SQL, OpenCV, spaCy, NLTK, Transformers (Hugging Face), LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Deep Learning (Transformers, CNNs, RNNs, VAEs, GANs), Bayesian Inference, Supervised/Unsupervised Learning, Computer Vision, NLP, LLM Fine-Tuning (LoRA), Retrieval-Augmented Generation (RAG), LLM Compression

## <span id="contact" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Contact</span>

📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)
