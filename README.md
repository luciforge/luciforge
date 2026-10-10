<h1 align="center">Hi there 👋, I'm Prashant Vashisht</h1>

<h3 align="center">AI &amp; ML Engineer · Computer Vision · Interpretable Machine Learning</h3>

<p align="center">
  M.Sc. Artificial Intelligence @ BTU Cottbus · Berlin, Germany
</p>

<p align="center">
  <a href="mailto:pprashant341@gmail.com"><img src="https://img.shields.io/badge/Gmail-pprashant341%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>&nbsp;
  <a href="https://www.linkedin.com/in/v-prashant"><img src="https://img.shields.io/badge/LinkedIn-Prashant%20Vashisht-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

I build ML systems from experimentation to deployment. At **Fresenius Medical Care**, I work on production AI and enterprise document intelligence. My current master’s thesis explores **interpretable multiclass learning through quantum logic decision trees**.

---

## 🔬 Current Research: Interpretable Multiclass Learning

**How can a model learn complex decision boundaries while keeping its decisions understandable?**

For my master’s thesis, I’m exploring multiclass extensions of **Quantum Logic Decision Trees (QLDT/QLDT+)**. The research investigates how a shared tree can represent evidence for several classes and express its decisions through logical rules.

### What I’m exploring

- **Multiclass reasoning:** how to extend binary QLDT learning to several classes, comparing a shared native model with one-vs-rest, one-vs-one, and error-correcting output codes.
- **Readable explanations:** how tree paths and class evidence can help explain why a model chooses one class over another.
- **Performance and complexity:** how stopping rules and model size affect predictive quality, readability, and how closely a simplified tree matches the exact reference model.
- **Generalisation and class imbalance:** how these methods behave across datasets with different characteristics, including medical classification problems.

### The goal

To understand **when QLDT-based models offer a useful balance between predictive performance, computational cost, and interpretability**—and where their limitations lie.

I’m particularly interested in whether a shared multiclass structure can produce coherent explanations without requiring a separate model for every class.

### Why this matters

In applications such as healthcare, a prediction is only part of the picture. People also need to inspect the reasoning behind it, understand its limitations, and assess whether it is appropriate for the decision at hand.

This research examines how logical model structure can support that inspection, while evaluating predictive performance and explanation complexity together.

---

- 🧠 &nbsp;Interests: **Computer Vision · MLOps · GenAI / RAG · Explainable AI**
- ☕ &nbsp;Fun fact: I optimize models before I optimize my coffee order

---

## 🚀 Some of my work:

- 🔧 **[Predictive Maintenance & Engine RUL](https://github.com/luciforge/Engine-RUL-ML)**  
  Turbofan failure-risk and remaining useful life modeling on NASA CMAPSS, examining generalisation to unseen engines and shifts in operating conditions. Combines uncertainty estimation, cost-sensitive maintenance decisions, SHAP explanations, FastAPI serving, MLflow, and drift monitoring.

- 🚗 **[AeroShapeOpt — Generative Aerodynamic Design](https://github.com/luciforge/AeroShapeOpt)**  
  Exploring low-drag car silhouettes on DrivAerNet++ through a β-VAE latent space, a ResNet-18 ensemble surrogate with uncertainty estimates, and Bayesian optimisation. Includes CMA-ES as an optimisation baseline.

- 🔍 **[Semantic E-Commerce Search](https://github.com/luciforge/NLPSearchEngine)**  
  Product retrieval using Sentence Transformers and FAISS, refined through cross-encoder re-ranking, price constraints, and review sentiment. Integrates Gemini for product summaries and recommendations.

- 😷 **[Real-Time Face Mask Detection](https://github.com/luciforge/FaceMaskDetection)**  
  A MobileNetV2 and OpenCV pipeline for detecting faces and classifying mask usage into three categories, with training, evaluation, and webcam inference.

- 🏥 **[Patient Education Bot](https://github.com/luciforge/Patient-Education-Bot)**  
  A RAG chatbot for plain-language explanations of lab results and medical terminology, with a focus on kidney health. Combines biomedical embeddings, FAISS retrieval, MedlinePlus source attribution, and a Gradio interface.

---
<table>
<tr>
<td width="45%">
  <img src="https://github.com/user-attachments/assets/a82b7155-a215-44bf-b2b6-97a7a610f392" width="100%"/>
</td>
<td valign="top">

**🧠 Things I care about deeply:**
- **I build systems that survive contact with reality on scale.**
- Evaluating generalisation, calibration, and uncertainty alongside accuracy.
- Building AI systems with deployment and monitoring in mind.
- RAG pipelines that don't hallucinate — retrieval quality, re-ranking, grounding

<br/>

</td>
</tr>
</table>

## 🛠️ Tools & Technologies

### Modeling & Computer Vision

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-4C8CBF?style=flat)
![BoTorch](https://img.shields.io/badge/BoTorch-EE4C2C?style=flat)

### GenAI & Retrieval

![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-4051B5?style=flat)
![Gemini API](https://img.shields.io/badge/Gemini%20API-4285F4?style=flat)
![LoRA / QLoRA](https://img.shields.io/badge/LoRA%20%2F%20QLoRA-8A2BE2?style=flat)

### Engineering & Deployment

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-F97316?style=flat&logo=gradio&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

### Additional Languages & Frontend

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Svelte](https://img.shields.io/badge/Svelte-FF3E00?style=flat&logo=svelte&logoColor=white)

💬 &nbsp;**A few soft skills:** product ownership & stakeholder communication · cross-functional collaboration · agile delivery · finding the real problem · bringing clarity to messy discussions · keeping momentum when plans change

---
