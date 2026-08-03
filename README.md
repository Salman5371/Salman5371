<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:071A2B,50:0B3B5A,100:0077B6&height=210&section=header&text=MD.%20SAlMAN%20FARSHI&fontSize=48&fontColor=FFFFFF&fontAlignY=35&desc=Artificial%20Intelligence%20%7C%20Machine%20Learning%20%7C%20Research&descAlignY=56&descSize=17&animation=fadeIn"/>

# Hi, I'm Md. Salman Farshi 👋

### Computer Science & Engineering Student | AI/ML Researcher | IEEE Conference Author

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&pause=1200&color=00D9FF&center=true&vCenter=true&width=800&lines=Artificial+Intelligence+%26+Machine+Learning;Computer+Vision+%7C+Generative+AI+%7C+RAG;Explainable+AI+for+Real-World+Applications;Building+Reliable+and+Practical+AI+Systems"/>

<br>

<a href="https://github.com/Salman5371">
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
</a>
<a href="https://www.linkedin.com/in/salman-farshi65/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/>
</a>
<a href="https://scholar.google.com/citations?user=_iIuVRIAAAAJ&hl=en">
<img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white"/>
</a>
<a href="https://orcid.org/0009-0000-4653-767X">
<img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white"/>
</a>
<a href="mailto:salmanfarshi.sdk@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/>
</a>

</div>

---

## About Me

I am a **Computer Science and Engineering student** at the
**American International University–Bangladesh — AIUB**, with a research focus on **Artificial Intelligence and Machine Learning**.

My work explores reliable, explainable, and practical AI systems, particularly in computer vision, retrieval-augmented generation, generative AI, and smart agriculture.

I aim to pursue an **MSc in Artificial Intelligence or Machine Learning** and contribute to impactful academic and applied AI research.

---

# Featured Research

## 🌱 Multi-Crop Plant Disease Detection

An explainable deep-learning framework for detecting diseases across multiple crop categories from plant-leaf images.

### Research Objectives

* Develop an accurate multi-class crop disease classification system
* Compare efficient deep-learning architectures
* Generate explainable predictions using Grad-CAM
* Support AI-assisted crop disease diagnosis
* Build a practical smart agriculture application

### Key Features

* Multi-crop disease recognition
* Multi-class image classification
* Explainable prediction visualization
* Model confidence estimation
* User-friendly diagnostic interface
* Downloadable prediction reports
* Farmer-focused disease alerts and management guidance

### Core Technologies

<p>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/EfficientNetV2-005571?style=flat-square"/>
<img src="https://img.shields.io/badge/MobileNetV2-4285F4?style=flat-square"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/Grad--CAM-8A2BE2?style=flat-square"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
</p>

### Explainable Prediction

<p align="center">
  <img
    src="assets/multicrop-gradcam-result.png"
    alt="Multi-Crop Plant Disease Detection with Grad-CAM"
    width="850"
  />
</p>

<p align="center">
  <em>Example crop disease prediction with Grad-CAM-based visual explanation.</em>
</p>

### Project Links

🔗 **Repository:**
[Multi-Crop Plant Disease Detection](https://github.com/Salman5371/Multi-crop-plant-disease-detection)

🌐 **Live Application:**
[Open the Streamlit Application](https://multi-crop-plant-disease-detection.streamlit.app/)

---

## 🤖 Adaptive Corrective RAG — AC-RAG

A research-oriented Retrieval-Augmented Generation framework designed to improve retrieval relevance, context quality, and generated-response reliability.

> 🚧 **Current Status: Under Active Research and Development**

### Research Objectives

* Improve the relevance of retrieved documents
* Combine sparse and dense retrieval methods
* Reduce irrelevant context supplied to the language model
* Adapt retrieval strategies to different query types
* Generate answers grounded in retrieved evidence
* Evaluate retrieval and generation performance

### Proposed Architecture

<p align="center">
  <img
    src="assets/ac-rag-architecture.png"
    alt="Adaptive Corrective RAG Architecture"
    width="900"
  />
</p>

<p align="center">
  <em>
    AC-RAG pipeline combining hybrid retrieval, cross-encoder reranking,
    adaptive context selection, and grounded generation.
  </em>
</p>

### Pipeline

```text
User Query
    ↓
Query Analysis and Classification
    ↓
Hybrid Retrieval
    ├── BM25 Sparse Retrieval
    └── FAISS Dense Retrieval with BGE Embeddings
    ↓
Candidate Fusion
    ↓
Cross-Encoder Reranking
    ↓
Adaptive Context Selection
    ↓
Qwen2.5-Based Grounded Generation
    ↓
Final Response
```

### Core Components

* Hybrid sparse and dense retrieval
* BM25 keyword-based retrieval
* FAISS vector similarity search
* BGE text embeddings
* Cross-encoder reranking
* Adaptive query classification
* Context selection
* Qwen2.5-based response generation
* Retrieval and generation evaluation

### Technology Stack

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square"/>
<img src="https://img.shields.io/badge/BM25-343434?style=flat-square"/>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21F?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/BGE_Embeddings-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Cross--Encoder-8A2BE2?style=flat-square"/>
<img src="https://img.shields.io/badge/Qwen2.5-5A67D8?style=flat-square"/>
</p>

### Research Direction

The project investigates whether adaptive retrieval and reranking can improve:

* Document relevance
* Context precision
* Answer faithfulness
* Response quality
* Retrieval efficiency
* Robustness across different query types

<!-- Add the AC-RAG repository link here when the public repository is ready. -->

---

# Publication

## IEEE Conference Paper

### A Machine Learning Approach for Evaluating District-Level Agricultural Performance, Instability, and Resilience in Bangladesh

*2026 5th International Conference on Electrical, Computer & Telecommunication Engineering — ICECTE*

### Research Areas

* Machine Learning
* Agricultural Analytics
* District-Level Performance Assessment
* Agricultural Instability Analysis
* Resilience Evaluation
* Data-Driven Decision Systems

<a href="https://doi.org/10.1109/ICECTE69292.2026.11429268">
<img src="https://img.shields.io/badge/DOI-10.1109%2FICECTE69292.2026.11429268-0072B1?style=flat-square&logo=doi&logoColor=white"/>
</a>

---

# Research Interests

* Artificial Intelligence and Machine Learning
* Computer Vision and Explainable AI
* Retrieval-Augmented Generation
* Large Language Models and Generative AI
* AI for Agriculture
* Trustworthy and Practical AI Systems

---

# Current Research Focus

* Developing adaptive and corrective RAG pipelines
* Evaluating hybrid retrieval and cross-encoder reranking
* Improving explainability in computer-vision systems
* Exploring GraphRAG and agentic AI
* Studying reproducible machine-learning experimentation
* Building practical AI solutions for smart agriculture

---

# Research Timeline

## 2026

* ✅ Published an IEEE conference paper on agricultural performance, instability, and resilience
* ✅ Developed an explainable multi-crop disease detection framework
* ✅ Deployed a smart agriculture application using Streamlit
* 🚧 Developing the Adaptive Corrective RAG framework
* 🔬 Evaluating hybrid retrieval, reranking, and grounded generation strategies

## Next Research Goals

* Complete the implementation and evaluation of AC-RAG
* Publish the AC-RAG source code and technical documentation
* Prepare research work for journal submission
* Explore multimodal and agentic RAG systems
* Pursue MSc opportunities in Artificial Intelligence and Machine Learning

---

# Technical Skills

## Programming Languages

<p>
<img src="https://skillicons.dev/icons?i=python,cpp,javascript"/>
</p>

## AI and Deep-Learning Frameworks

<p>
<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn"/>
</p>

## AI and Data Libraries

<p>
<img src="https://img.shields.io/badge/Hugging_Face-FFD21F?style=flat-square&logo=huggingface&logoColor=black"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square"/>
<img src="https://img.shields.io/badge/BM25-343434?style=flat-square"/>
</p>

## Development and Research Tools

<p>
<img src="https://skillicons.dev/icons?i=git,github,linux,vscode"/>
</p>

<p>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
</p>

---

# Research Competencies

* Literature review and research problem formulation
* Deep-learning model development
* Model evaluation and comparative analysis
* Explainable Artificial Intelligence
* Retrieval-Augmented Generation systems
* Academic writing and technical documentation
* Research presentation and communication

---

# Currently Exploring

<p>
<img src="https://img.shields.io/badge/Agentic_AI-6C63FF?style=flat-square"/>
<img src="https://img.shields.io/badge/GraphRAG-00897B?style=flat-square"/>
<img src="https://img.shields.io/badge/AI_Agents-FF6F00?style=flat-square"/>
<img src="https://img.shields.io/badge/Multimodal_AI-8A2BE2?style=flat-square"/>
<img src="https://img.shields.io/badge/Trustworthy_AI-2E8B57?style=flat-square"/>
<img src="https://img.shields.io/badge/MLOps-007ACC?style=flat-square"/>
</p>

---

# Research Profiles

<div align="center">

<a href="https://github.com/Salman5371">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/salman-farshi65/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://scholar.google.com/citations?user=_iIuVRIAAAAJ&hl=en">
<img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"/>
</a>

<a href="https://orcid.org/0009-0000-4653-767X">
<img src="https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white"/>
</a>

<a href="https://www.researchgate.net/profile/Md-Farshi-2">
<img src="https://img.shields.io/badge/ResearchGate-00CCBB?style=for-the-badge&logo=researchgate&logoColor=white"/>
</a>

</div>

---

# GitHub Statistics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Salman5371&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Salman5371&layout=compact&theme=github_dark&hide_border=true&langs_count=8"/>

</div>

<br>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Salman5371&theme=github-dark-blue&hide_border=true"/>

</div>

---

# Research Philosophy

> **Building trustworthy, explainable, and impactful AI systems through research, innovation, and open science.**

I aim to develop artificial intelligence systems that are:

* Scientifically grounded
* Reliable and explainable
* Reproducible
* Computationally efficient
* Practically applicable
* Socially responsible

---

# Open to Collaboration

I am interested in collaborating on:

* Artificial Intelligence and Machine Learning research
* Computer Vision projects
* Retrieval-Augmented Generation systems
* Large Language Model applications
* Explainable AI research
* Agricultural AI solutions
* Open-source AI development

I am also open to discussing:

* Research internships
* MSc research opportunities
* Academic collaborations
* Joint research publications
* Open-source project development

---

# Contact

<div align="center">

### Let's connect and build meaningful AI systems.

<a href="mailto:salmanfarshi.sdk@gmail.com">
<img src="https://img.shields.io/badge/Email-salmanfarshi.sdk%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br><br>

<a href="https://www.linkedin.com/in/salman-farshi65/">
<img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>

---

<div align="center">

### ⭐ Thank you for visiting my GitHub profile.

**Let's build reliable AI that creates real-world impact.**

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:071A2B,50:0B3B5A,100:0077B6&height=120&section=footer"/>

</div>
