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
    scroll-margin-top: 100px;
  }
</style>

---

<section id="education">
  <h2 style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Education</h2>

  - **The University of Edinburgh, Edinburgh, UK**  
    *MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*
  - **Vellore Institute of Technology (VIT), Vellore, India**  
    *BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*
</section>

---

<section id="experience">
  <h2 style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</h2>

  - **Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station, Edinburgh, UK**  
    *Student Researcher – March 2024 to August 2024*  
    <img src="assets/img/ForestResearch.jpg" alt="Forest Research Logo" style="height: 40px; margin-top: 6px; display: block;">
    <details><summary>View Details</summary><br>
      <ul>
        <li>Conducted industry-partnered machine learning research using multispectral satellite imagery to classify tree species in the Forest of Dean.</li>
        <li>Used ResNet-34, DenseNet-40, and Vision Transformers; QGIS for preprocessing, spatial analysis, and visualization.</li>
        <li>Compared model accuracy across species and analyzed spectral curves to explain predictions.</li>
      </ul>
    </details>

  - **Wipro Limited, Chennai, India**  
    *SAP BW Consultant – July 2021 to June 2023*  
    <img src="assets/img/WIPRO.jpeg" alt="Wipro Logo" style="height: 40px; margin-top: 6px; display: block;">
    <details><summary>View Details</summary><br>
      <ul>
        <li>Developed optimized data pipelines and reporting models using SAP BW for Nomad Foods Europe Limited.</li>
        <li>Designed queries to align with KPIs and enabled real-time insights with advanced modeling techniques.</li>
        <li>Improved ETL pipelines and enhanced BI performance using SAP BW/4HANA.</li>
      </ul>
    </details>
</section>

---

<section id="projects">
  <h2 style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</h2>

  - **Non-Self-Referential Attention in Transformers**  
    <a href="https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers" target="_blank">
      <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
    </a>
    <details><summary>View Details</summary><br>
      <ul>
        <li>Explored modifications to Transformer architecture and developed a method called Non-Self-Referential Attention.</li>
        <li>Attenuated main diagonal attention scores to reduce self-referential bias and enhance translation accuracy.</li>
        <li>Achieved 2.12% BLEU score improvement on the en-pt opus_books dataset.</li>
      </ul>
    </details>

  - **Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search**  
    <a href="https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION" target="_blank">
      <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
    </a>
    <details><summary>View Details</summary><br>
      <ul>
        <li>Extracted and embedded PDF textbook content into dense vectors for semantic search.</li>
        <li>Implemented a retrieval mechanism to fetch context passages and used GEMMA-7B-it to generate answers.</li>
        <li>Built a scalable and context-aware Q&A pipeline using RAG principles.</li>
      </ul>
    </details>

  - **Multi-Label Learning from Single Positive Labels**  
    <a href="https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels" target="_blank">
      <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
    </a>
    <details><summary>View Details</summary><br>
      <ul>
        <li>Addressed multi-label classification using presence-only species data with SPMLL approach.</li>
        <li>Inferred full label sets using deep learning while trained on single positive labels per instance.</li>
        <li>Proposed and implemented UPL loss, improving performance by 72% over standard BCE loss.</li>
      </ul>
    </details>

  - **Evaluating the Robustness of Classical ML vs Deep Learning**  
    <a href="https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification" target="_blank">
      <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
    </a>
    <details><summary>View Details</summary><br>
      <ul>
        <li>Compared Random Forest, SVM, and AlexNet on the Sports Balls Image dataset from Kaggle.</li>
        <li>Trained on clean data, tested on perturbed images including noise, blur, occlusion, and brightness variations.</li>
        <li>AlexNet outperformed classical models under distortion, showing superior generalization.</li>
      </ul>
    </details>
</section>

---

<section id="skills">
  <h2 style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</h2>

  - **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
  - **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, SQL, OpenCV, spaCy, NLTK, Transformers (Hugging Face), LlamaIndex  
  - **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
  - **Machine Learning:** Deep Learning (Transformers, CNNs, RNNs, VAEs, GANs), Bayesian Inference, Supervised/Unsupervised Learning, Computer Vision, NLP, LLM Fine-Tuning (LoRA), Retrieval-Augmented Generation (RAG), LLM Compression
</section>

---

<section id="contact">
  <h2 style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Contact</h2>

  📧 **irfanhamid19@gmail.com**  
  📱 **+91 9789596664** | **+44 7471069088**  
  [LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)
</section>

