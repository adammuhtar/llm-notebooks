# Large Language Models in Notebooks
The development of large language models (LLMs) have been nothing short of remarkable, revolutionising the field of natural language processing (NLP) and potentially moving humanity slightly closer towards building an artificial general intelligence. With the advent of large pre-trained models such as GPT-3 and GPT-4, these models are becoming increasingly sophisticated, with the latest models leveraging on billions of parameters and demonstrating impressive language processing capabilities. Equally as exciting is the growing trend towards making these models more accessible to researchers and developers alike, with many pre-trained models becoming freely available.

This repository contains Jupyter/Colab notebooks that runs LLMs on consumer-grade hardware, utilising off-the-shelf models and techniques to deploy LLMs which avoids the high computational cost associated with fine-tuning LLMs.

## Models
This repository contains notebooks running the following models:
* [Alpaca](https://github.com/adammuhtar/llm-notebooks/blob/main/notebooks/alpaca-lora-7b.ipynb)
* [Koala](https://github.com/adammuhtar/llm-notebooks/blob/main/notebooks/koala-lora-7b.ipynb)
* [Dolly 2.0](https://github.com/adammuhtar/llm-notebooks/blob/main/notebooks/dolly-v2-3b.ipynb)

## Getting Started
To get started, simply clone this repository to your local machine or open the notebooks directly in Google Colab (click on the "Open in Colab" icons at the start of the notebooks). The notebooks contain detailed instructions on how to use the models and how to modify the code to suit your specific needs.

## Requirements
This notebook is run using Google Colaboratory (Colab) - Google's implementation of [Jupyter Notebooks](https://jupyter.org/). While each notebook, has its own individual requirements, the overall libraries used in this repo are:
* `python==3.9.16`
* `accelerate==0.18.0`
* `bitsandbytes==0.38.1`
* `datasets==2.11.0`
* `loralib==0.1.1`
* `peft==0.3.0.dev0`
* `sentencepiece==0.1.98`
* `torch==2.0.0+cu118`
* `transformers==4.28.1`

## References
Key references that provides useful contextual information are as follows:
* Berkeley Artificial Intelligence Research. (2023, April 3). Koala: A Dialogue Model for Academic Research *BAIR Blog*. https://bair.berkeley.edu/blog/2023/04/03/koala/
* Conover, M., Hayes, M., Mathur, A., Meng, X. Xie, J., Wan, J., Shah, S., Ghodsi, A., Wendell, P. Zaharia, M., and Xin, R. (2023, April 12). Free Dolly: Introducing the World's First Truly Open Instruction-Tuned LLM. *Databricks Blog*. https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm
* Hu, E. J., Shen, Y., Wallis, P., Allen-Zhu, Z., Li, Y., Wang, S., Wang, L., & Chen, W. (2021). LoRA: Low-Rank Adaptation of Large Language Models. *arXiv* preprint arXiv:2106.09690.
* Mangrulkar, S. & Paul. S. (2023, February 10). 🤗 PEFT: Parameter-Efficient Fine-Tuning of Billion-Scale Models on Low-Resource Hardware. *Hugging Face Blog*. https://huggingface.co/blog/peft
* Meta AI. (2023, February 23). Introducing LLaMA: A foundational, 65-billion-parameter large language model. *Meta AI Blog*. https://ai.facebook.com/blog/large-language-model-llama-meta-ai/