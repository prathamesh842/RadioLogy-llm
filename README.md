# RadioLogy-llm
LLaMA 3.2 - 11B Vision Instruct Fine-Tuning on Unsloth Radiology Mini Dataset

Overview

This repository contains the fine-tuning process of unsloth/Llama-3.2-11B-Vision-Instruct on the Unsloth Radiology Mini dataset from Hugging Face. The goal is to enhance the model's ability to interpret and analyze radiology-related instructions, improving its performance in medical imaging tasks.

Model & Dataset

Model: unsloth/Llama-3.2-11B-Vision-Instruct

Dataset: Unsloth Radiology Mini

Fine-Tuning Approach
Framework: PyTorch with Unsloth

Optimization: LoRA (Low-Rank Adaptation) for efficient fine-tuning

Training Strategy:

Mixed precision for faster training

AdamW optimizer with cosine learning rate schedule

Training on multiple GPUs for efficiency
# Clone the repository
git clone https://github.com/yourusername/yourrepo.git
cd yourrepo

# Install dependencies
pip install torch transformers unsloth datasets

Acknowledgments

Thanks to Unsloth for providing efficient fine-tuning tools.

Special mention to the creators of the Unsloth Radiology Mini dataset.

License

This project is licensed under the MIT License.
