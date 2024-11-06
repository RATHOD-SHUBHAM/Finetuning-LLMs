# Fine-Tuning LLMs: Experimental Repository
Welcome to this repository where I explore fine-tuning various Large Language Models (LLMs). This repository contains my experiments with fine-tuning LLMs for different use cases and tasks. The project is intended to help understand how different configurations and datasets affect model performance.

## Repository Structure
The repository is organized into multiple folders, each corresponding to a different fine-tuning experiment. Below is an overview of the directory structure:

```
/llama3                  # Llama 3 model fine-tuning notebooks
/llama3.1                # Llama 3.1 model fine-tuning notebooks
/gemma                   # Gemma model fine-tuning notebooks
/data_preprocessing      # Scripts and notebooks to format and preprocess data for fine-tuning
```

## Folders:
1. Llama:
* /llama3
  Contains notebooks focused on fine-tuning the Llama 3 model. Each notebook in this folder explores different techniques, hyperparameters, and strategies for improving the performance of the model.

* /llama3.1
  Contains experiments with the Llama 3.1 model. This folder might have updated methods or adjustments compared to Llama 3 fine-tuning strategies.

2. Gemma
Includes experiments involving the Gemma model. Here, I attempt fine-tuning with different datasets and configurations.

3. Data Preprocessing
This folder contains code for preparing and formatting the dataset to be compatible with the fine-tuning process. It includes scripts for data cleaning, tokenization, and ensuring the right format for the LLMs.

## Purpose
This repository is meant to document my experiments with LLM fine-tuning to better understand the nuances of model training and optimization. The primary goal is to experiment with different configurations and gain insights into how different models react to various training strategies.

## Getting Started
### Prerequisites
* Python 3.x
* Jupyter Notebook (for running the notebooks)

### Installation
Clone the repository to your local machine:
```
git clone https://github.com/your-username/llm-finetuning-experiments.git
```

Navigate to the repository directory:
```
cd llm-finetuning-experiments
```

Running the Notebooks
To explore the fine-tuning experiments, you can open the Jupyter Notebooks in each model-specific folder. For example:
```
jupyter notebook llama3/finetuning_notebook.ipynb
```

## Notes
This repository is intended for my personal understanding of LLM fine-tuning, and the experiments may not be fully optimized or production-ready.
Feel free to explore, adapt, and experiment further, though keep in mind this is an experimental setup.