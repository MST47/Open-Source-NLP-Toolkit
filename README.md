# NLP Model Automation with Transformers
## Overview
This repository provides scripts and tools to automate multiple NLP models using the Hugging Face transformers library. It includes a comprehensive Jupyter notebook designed for Google Colab to demonstrate the use of various models for different NLP tasks such as text classification, named entity recognition, text generation, and more.

### Features
**Automated Scripts**: Easily automate the use of multiple NLP models. <br />
**Hugging Face Transformers**: Utilize state-of-the-art transformer models. <br />
**Colab Demonstration**: A ready-to-use Jupyter notebook for quick demonstrations on Google Colab.<br />
**Customizable**: Modify and extend the scripts for your specific needs.

### NLP Models
This repository includes multiple NLP models to automate different kinds of tasks. The list of Models and their descriptions are described as follows:
#### 1_Machine Translation
Open-source machine translation (MT) models enable translation between different languages without Google Translate. Many models have more than 1000 language pairs to the hugging face hub. 
Three models in our Machine Translation file translate different languages in one direction. These three models are:
 1. https://huggingface.co/Helsinki-NLP
 2. https://huggingface.co/models?search=facebook+m2m
 3. https://github.com/UKPLab/EasyNMT

####2_ Text Summarization and Named Entity Recognition
The repository file Text Summarization and Named Entity Recognition.ipynb contains two models such as:
**i. Text Summarization**:
Text summarization is the process of automatically generating a concise and coherent summary of a larger text document. This repository utilizes transformer models from Hugging Face to perform both extractive and abstractive summarization, allowing for quick and accurate distillation of information from lengthy documents.
**ii. Named Entity Recognition**:
Named Entity Recognition (NER) is a subtask of information extraction that aims to identify and classify key entities (such as names, organizations, locations, etc.) within text. Using state-of-the-art transformer models, this repository provides tools to accurately detect and categorize entities, enabling enhanced text analysis and understanding.

####3_Universal Models
The models described above are always tailored to one specific task from one dataset. The main advantage of these models is, that they are very good at this specific task and perform well on one specific dataset. In reality, however, he problems you will encounter in the real world will require a slightly different task, with different definitions of categories or on different types of texts.

Universal models can partly address this issue. They also only one task. But this one task is to general/universal, that many other tasks can be reformulated as this universal task. Two examples for universal tasks are:

**i. Natural Language Inference (NLI)**: A task that can solve any classification task.
**ii. Token generation**: An even more universal task that can solve any text-related task.

