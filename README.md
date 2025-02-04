# Causal-Clarity  

By identifying causal implications within research papers, this tool enhances understanding and analysis of scientific writing for causal inference.  
The models determine whether a sentence is **causal or non-causal** and further classify causal sentences into **correlational, conditional causal, or direct causal** categories.  

## 📁 Project Structure  

### 📂 Dataset Creation  
Contains code for generating **training, validation, and test splits** from **nine different data sources**.  

### 📂 Fine-Tuning  
Includes Jupyter notebooks for step-by-step fine-tuning of:  
- **BERT**  
- **SciBERT**  
- **GPT**  
- **LLaMA**  

### 📂 Tool  
This folder contains an **interactive interface** that applies the trained models to real research papers for causal analysis.  
![Causal Analysis Tool](assets/images/highlights.png)

## ⚡ GPU Usage  
The project utilizes **Kaggle** for training, leveraging its **GPU resources** for fine-tuning large models efficiently.  

## 🔗 Trained Models  
The final fine-tuned models are available on Kaggle:  
- **BERT (Final Model)**: [BERT Final](https://www.kaggle.com/models/tessaa/2_bert_final/)  
- **SciBERT**: [SciBERT Final](https://www.kaggle.com/models/tessaa/scibert_)  

## 📌 Fine-Tuning Notebooks  
- **LLaMA Fine-Tuning**: [LLaMA Fine-Tuning](https://www.kaggle.com/code/tessaa/llama)  
- **BERT Fine-Tuning**:  
  - **2-Class Classification**: [BERT Fine-Tuning (2 Classes)](https://www.kaggle.com/code/tessaa/bert-fine-tuning)  
  - **3-Class Classification**: [BERT Fine-Tuning (3 Classes)](https://www.kaggle.com/code/tessaa/3-classes-bert-finetuning)  

---

🚀 **Contributions & Issues**  
Feel free to **open issues** or **submit pull requests** if you find any improvements or have suggestions!  
