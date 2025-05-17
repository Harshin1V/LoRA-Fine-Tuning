
# LoRA Fine Tuning

This repository demonstrates fine-tuning [TinyLlama](https://huggingface.co/cognitionai/TinyLlama-1.1B-Chat-v1.0) models using Low-Rank Adaptation (LoRA), a parameter-efficient technique for adapting pre-trained language models to downstream tasks with reduced computational cost.

---

## 🧠 What is LoRA?

LoRA (Low-Rank Adaptation) is a training technique that allows you to insert trainable low-rank matrices into the attention layers of a Transformer model while keeping the original pre-trained weights frozen. This significantly reduces the number of trainable parameters and allows efficient fine-tuning even on low-resource hardware.

---

## 🗂️ Repository Structure

```bash
├── Fine-Tuning_TinyLlama_Frobinate.ipynb      # Fine-tuning on the "Frobinate" dataset
├── Fine-Tuning_TinyLlama_Math.ipynb           # Fine-tuning on the "Math" dataset
├── Evaluation_TinyLlama_Frobinate.ipynb       # Evaluation for "Frobinate" fine-tuned model
├── Evaluation_TinyLlama_Math.ipynb            # Evaluation for "Math" fine-tuned model
├── frobinate.jsonl                            # Training data for "Frobinate"
├── frobinate_test.jsonl                       # Test data for "Frobinate"
└── README.md
```
