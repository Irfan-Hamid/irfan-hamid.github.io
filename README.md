## <span id="projects" style="font-size: 26px; font-style: italic; text-decoration: underline; color: #2c3e50;">Projects</span>

**Non-Self-Referential Attention in Transformers**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Rethinking-Attention-for-Transformers)  

Proposed a novel attention mechanism to reduce self-referential focus in Transformers for improved translation accuracy.

<details>
<summary>View Details</summary>

• Explored modifications to Transformer architecture and developed a method called Non-Self-Referential Attention  
• Driven by the observation that self-attention values (main diagonal of the attention matrix) were often disproportionately high yet minimally informative, this method attenuated those values by a tunable factor to diversify attention distributions and improve performance on tasks like machine translation  
• Applied this approach to the 'en-pt' translation subset of the opus_books dataset, achieving a 2.12% BLEU score improvement

</details>

---

**Retrieval-Augmented Generation (RAG) Pipeline for Textbook Search**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/LLM_RAG_IMPLEMENTATION)  

Built a textbook-aware RAG system combining PDF extraction, embedding-based search, and LLM question answering.

<details>
<summary>View Details</summary>

• Extracted and preprocessed text from PDF textbooks, formatted it into chunks and converted them into numerical embeddings  
• Designed a vector-based retrieval system to identify and extract relevant text chunks based on user queries  
• Generated context-aware prompts using retrieved passages and utilized LLM (Google/GEMMA-7B-it) to produce accurate, context-driven responses to queries derived from textbook content

</details>

---

**Multi-Label Learning from Single Positive Labels**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Multi-Label-Learning-from-Single-Positive-Labels)  

Developed a method for learning multi-label predictions using only a single annotated label per training example.

<details>
<summary>View Details</summary>

• This project explores the challenge of multi-label classification in settings where each training example is annotated with only a single positive label, despite the presence of multiple applicable labels. In real-world scenarios, especially when the number of potential labels is large, it becomes impractical for human annotators to exhaustively list all relevant labels for each instance. This results in sparsely labeled data that is difficult to learn from using conventional techniques.  
• A practical example of this problem arises in species distribution modeling (SDM), where the goal is to predict the presence or absence of species across geographic regions based on limited field observations. In such datasets, only the locations where a species has been observed are recorded, and absence information is typically unavailable, making the task more complex and imbalanced.  
• A neural network was trained to perform accurate multi-label inference at test time despite being exposed to only a single positive label per instance during training.  
• Introduced a custom loss function called UPL (Up-weighting Positive Label), which increases the contribution of observed labels while handling ambiguity in the unobserved ones.  
• The UPL loss resulted in a 72% improvement in performance over standard binary cross-entropy loss across key evaluation metrics.

</details>

---

**Evaluating the Robustness of Classical ML vs Deep Learning**  
[![View on GitHub](https://img.shields.io/badge/View_on-GitHub-black?logo=github)](https://github.com/Irfan-Hamid/Robustness-Comparison-Classical-machine-learning-vs.-Deep-Learning-in-Image-Classification)  

Benchmarked ML vs DL models under real-world image perturbations using Kaggle’s Sports Balls image dataset.

<details>
<summary>View Details</summary>

• Investigated the robustness of classical machine learning models compared to deep learning architectures when exposed to real-world variations in image quality  
• Random Forest and Support Vector Machine (SVM) were used as classical baselines, while AlexNet, a convolutional neural network, represented the deep learning approach  
• All models were trained on the clean version of the Sports Balls Multiclass Image Classification dataset from Kaggle, containing over 9,000 images across 15 sports ball categories  
• Robustness testing involved introducing controlled perturbations, including Gaussian noise, blurring, contrast and brightness shifts, occlusion, and salt-and-pepper noise  
• Results showed that classical models deteriorated significantly under noisy conditions, while AlexNet maintained a higher level of performance, demonstrating stronger generalization to distorted inputs

</details>




