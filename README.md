# HtHotMG
*WORKING*
Hacking the Hardware of the Merciful Guardian: Becky &amp; Gmail

Becky and Gmail are two language models I trained to function on Raspberry Pis. Becky is a tiny Qwen model (Qwen/Qwen2.5-3B-Instruct) that I fine-tuned with JSONL I wrote consistant of censored and restricted data from big tech corporations like OpenAI and Google. 

You can view some of the JSONL here. 

Gmail's base model is a model that had its RLHF (Reinforcement Learning from Human Feedback) removed. This is what is known as an "ablitered" model, basically lacking safety features public agents have. 

This is Gmail's base model: huihui-ai/Huihui-Qwen3-4B-abliterated-v2. From there, I used TinyStories (https://huggingface.co/datasets/roneneldan/TinyStories), a dataset made to mimic the intelligence of a 4-6 year old child, creating a LoRA fine-tuned adapter that sits on top of the base model. 

Both bots were independently quantized, and then run on their own Raspberry Pi 5s with 8gb of RAM. 

All of the finetuning, quantization, and hosting is local. Completed on an Alienware PC with 16gb of RAM and an NVIDIA GPU. 
