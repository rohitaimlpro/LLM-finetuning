Fine-tuning LLM with LoRA (Low-Rank Adaptation) on Google Colab (T4 GPU)
LoRA (Low-Rank Adaptation) is one of the most widely used parameter-efficient fine-tuning (PEFT) methods today.

This project demonstrates LoRA (Low-Rank Adaptation) implementation from scratch — without using the peft package — in a step-by-step IPython notebook format. The goal is to provide a clear, conceptual understanding of how LoRA works and how to apply it to LLMs using PyTorch.

✅ Tested and run on Google Colab with free Tesla T4 GPU.
No special local setup is required — just open the notebooks and run them.

📘 Examples Included
Notebook	Description
01-finetune-opt-with-lora.ipynb	Fine-tuning Meta's OPT-125M with LoRA
(Explains LoRA mechanism)
02-finetune-gpt2-with-lora.ipynb	Fine-tuning OpenAI's GPT-2 Small (124M) with LoRA

Unlike the examples in the official Microsoft LoRA repository, this implementation directly downloads pre-trained models using the Hugging Face API and uses a manual PyTorch training loop (instead of the Hugging Face Trainer).

🛠 Setup (for Google Colab)
To run this project, simply:

Open the notebook in Google Colab

Select Runtime > Change Runtime Type > Set GPU (T4) as hardware accelerator

Run the following in the first cell to install the necessary packages:

python
Copy
Edit
!pip install torch transformers pandas matplotlib
That’s it — you’re ready to fine-tune LLMs using LoRA on Colab!

🚀 Quick Start (in Colab)
To get started:

bash
Copy
Edit
!git clone https://github.com/rohitaimlpro/LLM-finetuning.git
Then open and run the .ipynb notebooks to begin training.

