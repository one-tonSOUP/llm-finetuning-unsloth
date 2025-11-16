# LLM Fine-Tuning

This repository contains a complete walkthrough of fine-tuning the **Llama 3.2 3B Instruct** model using **QLoRA** and the **Unsloth** training framework. The tutorial is designed for learners who want to understand practical, efficient large-language-model fine-tuning on limited hardware (such as Google Colab).

## What This Project Covers
- Loading and preparing the base Llama 3.2 model  
- Applying QLoRA (4-bit quantization + LoRA adapters)  
- Formatting datasets using chat templates  
- Training with `SFTTrainer` from Hugging Face TRL  
- Evaluating the fine-tuned model with custom prompts  
- Running inference on the final checkpoint  

## Dataset
This project uses the **FineTome-100k** dataset, a curated collection of high-quality instruction-style conversations.

Dataset link: https://huggingface.co/datasets/mlabonne/FineTome-100k

## Requirements
Key libraries used:
- `unsloth`
- `transformers`
- `trl`
- `datasets`
- `torch`

All installation steps are included in the notebook.

## Files in This Repository
- `llama3_qlora_finetune_tutorial.ipynb` – Main Colab notebook containing the full code and explanations  
- `README.md` – Project overview and setup instructions  

## Usage
Open the notebook, run each section sequentially, and follow the step-by-step explanations. You can replace the dataset or prompts to fine-tune the model for your own tasks.

## License
This project is open-source and available for educational and research use.
