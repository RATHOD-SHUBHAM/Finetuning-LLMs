# 🧠 Gemma 3 4B – Financial QA Fine-Tuning & Inference
This repository contains two core scripts demonstrating how to fine-tune and perform inference on the Gemma 3 4B language model for financial question answering tasks.

## 📂 Repository Structure
* finetune.ipynb – Fine-tunes the Gemma 3 4B model using financial QA data with the Unsloth framework.

* inference.ipynb – Loads the fine-tuned model using the Transformers library and performs inference on.

## 🧾 Dataset
* Source: TheFinAI/Fino1_Reasoning_Path_FinQA

* Focused on complex financial reasoning and multi-step question answering.

## 🧰 Model & Framework
* Model: Gemma 3 4B

* Fine-Tuning Framework: Unsloth

## 🖥️ System Specs
* GPU: RTX 6000 Ada (48GB VRAM)

* CPU: 16 vCPUs

* RAM: 62GB

## 🚀 How to Use
* Fine-tune the model
```
FT.ipynb
```
* Run inference
```
inference.ipynb
```
