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

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

## <span id="education" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Education</span>

**The University of Edinburgh, Edinburgh, UK**  
*MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*

**Vellore Institute of Technology (VIT), Vellore, India**  
*BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

## <span id="experience" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</span>

**Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station**  
*Student Researcher – March 2024 to August 2024*

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Conducted an industry-partnered machine learning research with Forest Research for my MSc dissertation, focusing on the classification of tree species using high-resolution multispectral satellite imagery.</li>
  <li>Implemented and trained ResNet-34, DenseNet-40, and Vision Transformers (ViT) models. Used QGIS for geospatial preprocessing and visualization.</li>
  <li>Performed comparative evaluation and spectral analysis to interpret model predictions across different species.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

**Wipro Limited, Chennai, India**  
*SAP BW Consultant – July 2021 to June 2023*

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Designed and optimized SAP BW process chains for Nomad Foods Europe Limited, improving automation and data integration.</li>
  <li>Developed customized SAP BW queries aligned with business KPIs for accurate, actionable reporting.</li>
  <li>Implemented SAP BW/4HANA data provisioning and ETL processes, enhancing BI report performance and operational decision-making.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

## <span id="projects" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

### Non-Self-Referential Attention in Transformers  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Explored modifications to Transformer architecture by attenuating the main diagonal values in attention matrices, which correspond to self-referential attention.</li>
  <li>This adjustment reduces the overemphasis on tokens attending to themselves and promotes richer, more diverse contextual understanding.</li>
  <li>The method led to improved translation performance in benchmark tasks.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Extracted and chunked text from PDF textbooks and converted them into dense vector embeddings.</li>
  <li>Implemented a semantic search system to retrieve relevant context based on user queries.</li>
  <li>Used GEMMA-7B-it LLM to generate context-aware responses from retrieved information.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Multi-Label Learning from Single Positive Labels  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>This project explores the challenge of multi-label classification in settings where each training example is annotated with only a single positive label, despite the presence of multiple applicable labels.</li>
  <li>A practical example of this problem arises in species distribution modeling (SDM), where the goal is to predict the presence or absence of species across geographic regions based on limited field observations.</li>
  <li>A neural network was trained to perform accurate multi-label inference at test time despite being exposed to only a single positive label per instance during training.</li>
  <li>Introduced a custom loss function called UPL (Up-weighting Positive Label), which increases the contribution of observed labels while handling ambiguity in the unobserved ones.</li>
  <li>The UPL loss resulted in a 72% improvement in performance over standard binary cross-entropy loss across key evaluation metrics.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

### Evaluating the Robustness of Classical ML vs Deep Learning  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Investigated the robustness of classical machine learning models compared to deep learning architectures when exposed to real-world variations in image quality.</li>
  <li>Random Forest and Support Vector Machine (SVM) were used as classical baselines, while AlexNet, a convolutional neural network, represented the deep learning approach.</li>
  <li>All models were trained on the clean version of the Sports Balls Multiclass Image Classification dataset from Kaggle, containing over 9,000 images across 15 sports ball categories.</li>
  <li>Robustness testing involved introducing controlled perturbations, including Gaussian noise, blurring, contrast and brightness shifts, occlusion, and salt-and-pepper noise.</li>
  <li>Results showed that classical models deteriorated significantly under noisy conditions, while AlexNet maintained a higher level of performance, demonstrating stronger generalization to distorted inputs.</li>
</ul>
</details>

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

## <span id="skills" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</span>

- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, SQL, OpenCV, spaCy, NLTK, Transformers (Hugging Face), LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Deep Learning Architectures (Transformers, CNNs, RNNs, VAEs, GANs), Bayesian Inference, Approximate Inference, Supervised Learning, Unsupervised Learning, Computer Vision, Natural Language Processing (NLP), Large Language Models (LLMs), LLM Fine-Tuning (PEFT methods like LoRA), Retrieval-Augmented Generation (RAG), LLM Compression

<hr style="border: none; border-top: 2px solid #ccc; margin: 30px 0;">

## <span id="contact" style="scroll-margin-top: 80px; font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Contact</span>

📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)

<hr>
<footer style="text-align: center; font-size: 14px; color: #777; padding: 20px;">
  This portfolio is maintained by <a href="https://github.com/Irfan-Hamid" target="_blank">irfan-hamid</a> • Hosted on GitHub Pages
</footer>


