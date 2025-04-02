# 🚀 Fine-Tuned LLaMA 2 (7B) & LLaMA 3.2 (3B) Notebook  

This repository contains Jupyter Notebooks for fine-tuning **LLaMA 2 (7B)** and **LLaMA 3.2 (3B)** on custom datasets. The notebooks provide a step-by-step workflow for preparing data, training the models, and evaluating their performance.  

## 💪 Features  
- **Preprocessing:** Data loading, tokenization, and formatting for fine-tuning.  
- **Fine-Tuning:**
  - **LLaMA 2 (7B):** Uses **LoRA** and **PEFT** for efficient model adaptation.  
  - **LLaMA 3.2 (3B):** Utilizes **Unsloth** and **QLoRA** for efficient and memory-optimized fine-tuning.  
- **Inference:** Generate responses from the fine-tuned models.  
- **Evaluation:** Assess model performance using qualitative and quantitative metrics.  

## 📎 File Structure  
- **`finetuned_llama_2_7b.ipynb`** – Notebook for fine-tuning and inference with LLaMA 2 (7B).  
- **`llama3_2_3b_finetuning.ipynb`** – Notebook for fine-tuning and inference with LLaMA 3.2 (3B) using Unsloth and QLoRA.  
- **`data/`** – *(Optional)* Directory for training datasets.  
- **`models/`** – *(Optional)* Directory for storing trained model checkpoints.  

## 📌 Requirements  
To run the notebooks, install the necessary dependencies:  
```bash
pip install torch transformers peft bitsandbytes accelerate datasets unsloth
```  

## 🏠 Usage  
### Clone the repository:  
```bash
git clone https://github.com/your-username/your-repo.git  
cd your-repo  
```  
### Open the notebooks:  
For **LLaMA 2 (7B)** fine-tuning:  
```bash
jupyter notebook finetuned_llama_2_7b.ipynb  
```  
For **LLaMA 3.2 (3B)** fine-tuning:  
```bash
jupyter notebook llama3_2_3b_finetuning.ipynb  
```  
Follow the notebook instructions to fine-tune the models.  

## ⚡ Results  
After training, you can test the fine-tuned models by running inference cells in the respective notebooks.  

## 🐝 License  
This project is open-source under the **MIT License**.

