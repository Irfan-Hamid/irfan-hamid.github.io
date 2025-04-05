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

<!-- Education -->
## <span id="education" style="...">Education</span>
**The University of Edinburgh, Edinburgh, UK**  
*MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*

**Vellore Institute of Technology (VIT), Vellore, India**  
*BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

<!-- Experience -->
## <span id="experience" style="...">Experience</span>

**Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station**  
*Student Researcher – March 2024 to August 2024*
<details><summary>View Details</summary><br><ul>
  <li>Conducted industry-partnered ML research using multispectral satellite imagery for species classification.</li>
  <li>Trained ResNet-34, DenseNet-40, and ViT; performed preprocessing and geospatial analysis with QGIS.</li>
  <li>Evaluated model accuracy and interpreted spectral curves to explain results.</li>
</ul></details>

**Wipro Limited, Chennai, India**  
*SAP BW Consultant – July 2021 to June 2023*
<details><summary>View Details</summary><br><ul>
  <li>Designed and optimized SAP BW process chains to automate reporting for Nomad Foods Europe.</li>
  <li>Created BW queries for performance monitoring aligned with business KPIs.</li>
  <li>Implemented SAP BW/4HANA ETL pipelines to improve reliability and speed.</li>
</ul></details>

<!-- Projects -->
## <span id="projects" style="...">Projects</span>

<div style="margin-bottom: 30px;"><div style="display: flex;"><span style="min-width: 20px; font-weight: bold;">1.</span><div>
<strong>Non-Self-Referential Attention in Transformers</strong><br>
<a href="https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers" target="_blank">
  <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
</a>
<details><summary>View Details</summary><br><ul>
  <li>Explored modifications to Transformer architecture by attenuating the main diagonal values in attention matrices, which correspond to self-referential attention.</li>
  <li>This adjustment reduces the overemphasis on tokens attending to themselves and promotes richer, more diverse contextual understanding.</li>
  <li>The method led to improved translation performance in benchmark tasks.</li>
</ul></details></div></div></div>

<div style="margin-bottom: 30px;"><div style="display: flex;"><span style="min-width: 20px; font-weight: bold;">2.</span><div>
<strong>Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search</strong><br>
<a href="https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION" target="_blank">
  <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
</a>
<details><summary>View Details</summary><br><ul>
  <li>Extracted and chunked text from PDF textbooks and converted them into dense vector embeddings.</li>
  <li>Implemented a semantic search system to retrieve relevant context based on user queries.</li>
  <li>Used GEMMA-7B-it LLM to generate context-aware responses from retrieved information.</li>
</ul></details></div></div></div>

<div style="margin-bottom: 30px;"><div style="display: flex;"><span style="min-width: 20px; font-weight: bold;">3.</span><div>
<strong>Multi-Label Learning from Single Positive Labels</strong><br>
<a href="https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels" target="_blank">
  <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
</a>
<details><summary>View Details</summary><br><ul>
  <li>This project explores multi-label classification where only one positive label is available during training.</li>
  <li>Applied in species distribution modeling, which often lacks absence data for species.</li>
  <li>Designed a custom UPL loss function that significantly improved model performance over BCE loss.</li>
</ul></details></div></div></div>

<div style="margin-bottom: 30px;"><div style="display: flex;"><span style="min-width: 20px; font-weight: bold;">4.</span><div>
<strong>Evaluating the Robustness of Classical ML vs Deep Learning</strong><br>
<a href="https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification" target="_blank">
  <img src="https://img.shields.io/badge/View_on-GitHub-black?logo=github">
</a>
<details><summary>View Details</summary><br><ul>
  <li>Benchmarked Random Forest, SVM, and AlexNet against perturbations like blur, noise, occlusion.</li>
  <li>Used Kaggle’s Sports Balls dataset (~9k images across 15 classes).</li>
  <li>Found deep models (AlexNet) to be more robust than classical ML under noisy conditions.</li>
</ul></details></div></div></div>

<!-- Skills -->
## <span id="skills" style="...">Skills</span>
- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, OpenCV, spaCy, NLTK, Transformers, LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Transformers, CNNs, RNNs, VAEs, GANs, Bayesian & Approximate Inference, NLP, LLMs, LoRA, RAG, LLM Compression

<!-- Contact -->
## <span id="contact" style="...">Contact</span>
📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)

