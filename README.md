<!-- Navigation Bar -->
<nav style="position: sticky; top: 0; background-color: #ffffff; padding: 12px 20px; font-family: sans-serif; font-size: 16px; z-index: 999; border-bottom: 1px solid #ccc; white-space: nowrap; overflow-x: auto; display: flex; min-width: 100%;">
  <a href="#education" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Education</a>
  <a href="#experience" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Experience</a>
  <a href="#projects" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Projects</a>
  <a href="#skills" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Skills</a>
  <a href="#contact" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Contact</a>
  <a href="/assets/resume/Irfan_Resume.pdf" download style="text-decoration: none; font-weight: bold; color: #333;">Resume</a>
</nav>

<!-- CSS for Animation & Scroll Fix -->
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

**The University of Edinburgh, Edinburgh, UK**  
*MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*

**Vellore Institute of Technology (VIT), Vellore, India**  
*BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

## <span id="experience" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</span>

**Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station**  
*Student Researcher – March 2024 to August 2024*

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Conducted industry-partnered machine learning research on tree species classification using high-resolution multispectral satellite imagery.</li>
  <li>Trained ResNet-34, DenseNet-40, and ViT models and utilized QGIS for preprocessing and geospatial analysis.</li>
  <li>Compared model performances and interpreted spectral patterns to evaluate accuracy across species.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

**Wipro Limited, Chennai, India**  
*SAP BW Consultant – July 2021 to June 2023*

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Built and automated SAP BW process chains for Nomad Foods Europe Ltd, enhancing data integration and reducing manual effort.</li>
  <li>Created customized reporting queries aligned to business KPIs, enabling better real-time decision making.</li>
  <li>Developed SAP BW/4HANA ETL pipelines, improving reliability and performance of BI reports.</li>
</ul>
</details>

## <span id="projects" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

### Non-Self-Referential Attention in Transformers  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Explored modifications to Transformer architecture by attenuating main diagonal attention values to reduce self-referential bias.</li>
  <li>Improved cross-token interaction and enhanced translation performance.</li>
  <li>Achieved a 2.12% BLEU score improvement on the 'en-pt' opus_books dataset.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Built a vector-based retrieval system by extracting and embedding textbook content.</li>
  <li>Implemented semantic search and RAG using GEMMA-7B-it to answer academic queries contextually.</li>
  <li>Enabled accurate, LLM-generated answers derived from PDF textbook passages.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Multi-Label Learning from Single Positive Labels  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Designed a learning framework for multi-label classification under single-label supervision.</li>
  <li>Applied to species distribution modeling where only positive observations exist.</li>
  <li>Introduced UPL loss, improving model accuracy by 72% over binary cross-entropy.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Evaluating the Robustness of Classical ML vs Deep Learning  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Compared classical models (Random Forest, SVM) and AlexNet under image perturbations.</li>
  <li>Used a clean sports image dataset and evaluated performance under noise, blur, occlusion, and brightness/contrast changes.</li>
  <li>Deep learning models outperformed classical ones in robustness across all transformations.</li>
</ul>
</details>

## <span id="skills" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</span>

- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, OpenCV, spaCy, NLTK, Transformers, LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Transformers, CNNs, RNNs, VAEs, GANs, Bayesian Inference, Supervised/Unsupervised Learning, Computer Vision, NLP, LLMs, LoRA, RAG, Compression

## <span id="contact" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Contact</span>

📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)
