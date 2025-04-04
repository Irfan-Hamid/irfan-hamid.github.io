<!-- Sticky Dark Navigation Bar -->
<nav style="position: sticky; top: 0; background-color: #1e1e1e; padding: 12px 20px; font-family: sans-serif; font-size: 16px; z-index: 999; border-bottom: 1px solid #444;">
  <a href="#education" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: white;">Education</a>
  <a href="#work-experience" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: white;">Experience</a>
  <a href="#projects" style="margin-right: 20px; text-decoration: none; font-weight: bold; color: white;">Projects</a>
  <a href="/assets/resume/Irfan_Hamid_Resume.pdf" download style="margin-right: 20px; text-decoration: none; font-weight: bold; color: white;">Download Resume</a>
  <a href="mailto:irfanhamid19@gmail.com" style="text-decoration: none; font-weight: bold; color: white;">Contact</a>
</nav>

# Hi, I'm Irfan Hamid

*Exploring the frontiers of Artificial Intelligence, driven by curiosity and precision. I thrive on turning complex theories into powerful real-world applications — from satellite-based tree classification to novel Transformer architectures and model robustness research. I bring a hybrid background across AI, deep learning, and scalable data engineering solutions.*

📫 **irfanhamid19@gmail.com** | 📱 **+91 9789596664**  
[LinkedIn](https://www.linkedin.com/in/irfan-hamid/) • [GitHub](https://github.com/Irfan-Hamid)

---

## Education {#education}

### The University of Edinburgh, UK _(Sep 2023 - Nov 2024)_
**MSc in Artificial Intelligence**

### Vellore Institute of Technology, India _(Jun 2017 - Jun 2021)_
**BTech in Electrical and Electronics Engineering**  
**Award:** Ranked 4th in the Electrical and Electronics Engineering cohort for the academic year 2018–2019 at VIT Vellore

---

## Work Experience {#work-experience}

### Forest Research, Student Researcher _(Mar 2024 – Aug 2024)_  
*(The research agency of the Forestry Commission, UK government)*  
• Conducted an industry-partnered machine learning research with Forest Research for my MSc dissertation, focusing on the classification of tree species in the Forest of Dean using high-resolution multispectral satellite imagery from Planet Labs’ SuperDove 8 satellites  
• Implemented and trained deep learning models, including ResNet-34, DenseNet-40 and Vision Transformers (ViT) to perform species classification. Utilized QGIS for geospatial preprocessing, spatial analysis, and visualization of labelled tree data  
• Performed a comparative evaluation of the models and analyzed classification accuracy across various tree species. Additionally, examined species spectral curves to explain predictions, contributing to precision forestry and remote sensing applications

### Wipro Limited, SAP BW Consultant, Chennai, India _(Jul 2021 – Jun 2023)_  
• Designed and optimized SAP BW process chains for Nomad Foods Europe Limited, improving automation and data integration  
• Developed customized SAP BW queries aligned with business KPIs for accurate, actionable reporting  
• Implemented SAP BW/4HANA data provisioning and ETL processes, enhancing BI report performance and operational decision-making

---

## Projects {#projects}

### Non-Self-Referential Attention in Transformers  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers)  
![Last Commit](https://img.shields.io/github/last-commit/Irfan-Hamid/Rethinking-Attention-for-Transformers)
![Top Language](https://img.shields.io/github/languages/top/Irfan-Hamid/Rethinking-Attention-for-Transformers)

- Explored modifications to Transformer architecture and developed a method called Non-Self-Referential Attention  
- Driven by the observation that self-attention values (main diagonal of the attention matrix) were often disproportionately high yet minimally informative, this method attenuated those values by a tunable factor to diversify attention distributions and improve performance on tasks like machine translation  
- Applied this approach to the 'en-pt' translation subset of the opus_books dataset, achieving a 2.12% BLEU score improvement

---

### Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)  
![Last Commit](https://img.shields.io/github/last-commit/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)
![Top Language](https://img.shields.io/github/languages/top/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)

- Extracted and preprocessed text from PDF textbooks, formatted it into chunks and converted them into numerical embeddings  
- Designed a vector-based retrieval system to identify and extract relevant text chunks based on user queries  
- Generated context-aware prompts using retrieved passages and utilized LLM (Google/GEMMA-7B-it) to produce accurate, context-driven responses to queries derived from textbook content

---

### Multi-Label Learning from Single Positive Labels  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)  
![Last Commit](https://img.shields.io/github/last-commit/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)
![Top Language](https://img.shields.io/github/languages/top/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)

- This project explores the challenge of multi-label classification in settings where each training example is annotated with only a single positive label, despite the presence of multiple applicable labels. In real-world scenarios, especially when the number of potential labels is large, it becomes impractical for human annotators to exhaustively list all relevant labels for each instance. This results in sparsely labeled data that is difficult to learn from using conventional techniques.  
- A practical example of this problem arises in species distribution modeling (SDM), where the goal is to predict the presence or absence of species across geographic regions based on limited field observations. In such datasets, only the locations where a species has been observed are recorded, and absence information is typically unavailable, making the task more complex and imbalanced.  
- A neural network was trained to perform accurate multi-label inference at test time despite being exposed to only a single positive label per instance during training.  
- Introduced a custom loss function called **UPL (Up-weighting Positive Label)**, which increases the contribution of observed labels while handling ambiguity in the unobserved ones.  
- The UPL loss resulted in a **72% improvement in performance** over standard binary cross-entropy loss across key evaluation metrics.

---

### Evaluating the Robustness of Classical ML vs Deep Learning for Image Classification  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)  
![Last Commit](https://img.shields.io/github/last-commit/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)
![Top Language](https://img.shields.io/github/languages/top/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)

- Investigated the robustness of classical machine learning models compared to deep learning architectures when exposed to real-world variations in image quality  
- Random Forest and Support Vector Machine (SVM) were used as classical baselines, while AlexNet, a convolutional neural network, represented the deep learning approach  
- All models were trained on the clean version of the **Sports Balls Multiclass Image Classification** dataset from Kaggle, containing over 9,000 images across 15 sports ball categories  
- Robustness testing involved introducing controlled perturbations, including Gaussian noise, blurring, contrast and brightness shifts, occlusion, and salt-and-pepper noise  
- Results showed that classical models deteriorated significantly under noisy conditions, while AlexNet maintained a higher level of performance, demonstrating stronger generalization to distorted inputs

