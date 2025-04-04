<!-- Navigation Bar -->
<nav style="position: sticky; top: 0; background-color: #ffffff; padding: 12px 20px; font-family: sans-serif; font-size: 16px; z-index: 999; border-bottom: 1px solid #ccc;">
  <a href="#education" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Education</a>
  <a href="#experience" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Experience</a>
  <a href="#projects" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Projects</a>
  <a href="#skills" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: #333;">Skills</a>
  <a href="/assets/resume/Irfan_Resume.pdf" download style="text-decoration: none; font-weight: bold; color: #333;">Download Resume</a>
</nav>

<!-- CSS for Animation -->
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

# Hi, I'm Irfan Hamid

*Exploring the frontiers of Artificial Intelligence, driven by curiosity and precision. I thrive on turning complex theories into powerful real-world applications — from satellite-based tree classification to novel Transformer architectures and model robustness research. I bring a hybrid background across AI, deep learning, and scalable data engineering solutions.*

📧 **irfanhamid19@gmail.com**  
📱 **+91 9789596664** | **+44 7471069088**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)

---

## <span id="education" style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Education</span>

**The University of Edinburgh, Edinburgh, UK**  
*MSc in Artificial Intelligence (Sep 2023 – Nov 2024)*

**Vellore Institute of Technology (VIT), Vellore, India**  
*BTech in Electrical and Electronics Engineering (Jun 2017 – Jun 2021)*

---

## <span id="experience" style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Experience</span>

**Forest Research (The research agency of the Forestry Commission, UK government), Northern Research Station**  
*Student Researcher – March 2024 to August 2024*

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Conducted an industry-partnered machine learning research with Forest Research for my MSc dissertation, focusing on the classification of tree species in the Forest of Dean using high-resolution multispectral satellite imagery from Planet Labs’ SuperDove 8 satellites.</li>
  <li>Implemented and trained deep learning models, including ResNet-34, DenseNet-40 and Vision Transformers (ViT) to perform species classification. Utilized QGIS for geospatial preprocessing, spatial analysis, and visualization of labelled tree data.</li>
  <li>Performed a comparative evaluation of the models and analyzed classification accuracy across various tree species. Additionally, examined species spectral curves to explain predictions, contributing to precision forestry and remote sensing applications.</li>
</ul>
</details>

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

---

## <span id="projects" style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

**Non-Self-Referential Attention in Transformers**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers)

Proposed a novel attention mechanism to reduce self-referential focus in Transformers for improved translation accuracy.

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Explored modifications to Transformer architecture and developed a method called Non-Self-Referential Attention.</li>
  <li>Driven by the observation that self-attention values (main diagonal of the attention matrix) were often disproportionately high yet minimally informative, this method attenuated those values by a tunable factor to diversify attention distributions and improve performance on tasks like machine translation.</li>
  <li>Applied this approach to the 'en-pt' translation subset of the opus_books dataset, achieving a 2.12% BLEU score improvement.</li>
</ul>
</details>

**Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)

Designed a custom LLM pipeline that performs semantic textbook search and question answering using retrieval-augmented generation.

<details>
<summary>View Details</summary>
<br>
<ul>
  <li>Extracted and preprocessed text from PDF textbooks, formatted it into chunks and converted them into numerical embeddings.</li>
  <li>Designed a vector-based retrieval system to identify and extract relevant text chunks based on user queries.</li>
  <li>Generated context-aware prompts using retrieved passages and utilized LLM (Google/GEMMA-7B-it) to produce accurate, context-driven responses to queries derived from textbook content.</li>
</ul>
</details>

**Multi-Label Learning from Single Positive Labels**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)

Developed a novel learning framework to infer multiple labels from datasets where only one positive label is provided per sample.

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

**Evaluating the Robustness of Classical ML vs Deep Learning**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)

Analyzed how classical ML and deep learning models perform under real-world image distortions using Kaggle sports dataset.

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

---

## <span id="skills" style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Skills</span>

- **Programming Languages & Databases:** Python, SQL, PostgreSQL, MongoDB  
- **Frameworks & Libraries:** PyTorch, NumPy, Pandas, scikit-learn, SQL, OpenCV, spaCy, NLTK, Transformers (Hugging Face), LlamaIndex  
- **Cloud Platforms & MLOps:** AWS, Docker, Git, GitHub Actions, DVC  
- **Machine Learning:** Deep Learning Architectures (Transformers, CNNs, RNNs, VAEs, GANs), Bayesian Inference, Approximate Inference, Supervised Learning, Unsupervised Learning, Computer Vision, Natural Language Processing (NLP), Large Language Models (LLMs), LLM Fine-Tuning (PEFT methods like LoRA), Retrieval-Augmented Generation (RAG), LLM Compression
