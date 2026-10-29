# llm-prompt-engineering-political-interviews-clarity-classification

##  Assignment Description

Response clarity classification of political interviews (Clear Reply, Ambivalent, Clear Non-Reply), based on SemEval 2026 Task 6 (CLARITY), 
using prompt engineering with three instruction-tuned language models (Qwen3.5-0.8B, Qwen3.5-2B, Qwen3.5-4B) from the Hugging Face Transformers 
library, without any fine tuning. The project compares zero-shot, few-shot, chain-of-thought (CoT), persona, persona + few-shot and 
persona + CoT prompting strategies across all three models.

##  Dataset

The dataset used in this project is available on Hugging Face: [ailsntua/QEvasion](https://huggingface.co/datasets/ailsntua/QEvasion)

Backup copy of the dataset, in case the above original link is no longer available: [EmilBa122/QEvasion-backup](https://huggingface.co/datasets/EmilBa122/QEvasion-backup)
