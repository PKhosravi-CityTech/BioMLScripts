<img src="https://github.com/PKhosravi-CityTech/BioMLScripts/raw/main/Images/QueryMate.jpeg" alt="QueryMate" width="150" height="150" align="left" style="margin-bottom: 40px;">

# QueryMate

QueryMate is an AI-powered question-answering system built using the LlamaCpp model from the langchain library. This system is designed to provide precise answers to user questions and allows for adjustable response parameters based on user feedback.



## Getting Started

To get started with QueryMate, follow these steps:

### Prerequisites

- Python 3.6 or later
- Make sure you are on GPU or TPU as this program takes ten minutes on CPU, three minutes on GPU, and just a few seconds on TPU in Colab for each question.
- Install the required libraries in your Colab:

  ```bash

  !pip install langchain-community
  !pip install llama-cpp-python

  ```

### Download the SynthIA-7B-v2.0-16k model

You need to download the SynthIA-7B-v2.0-16k model file from Hugging Face. 
Visit the following link and download the latest or the second latest version of the file 
named synthia-7b-v2.0-16k.Q3_K_S.gguf and then upload it to your gdrive:

  ```bash
  https://huggingface.co/TheBloke/SynthIA-7B-v2.0-16k-GGUF
  ```
```diff
+ Update: QueryMate_V01 is the version with automated model downloading.
```
```diff
+ Update: QueryMate_V02 with parallel model downloading and improved model file.
```

### Download the QueryMate or QueryMate_V01 model
```bash
https://github.com/PKhosravi-CityTech/BioMLScripts/blob/main/QueryMate/QueryMate.ipynb
https://github.com/PKhosravi-CityTech/BioMLScripts/blob/main/QueryMate/QueryMate_V01.ipynb
```
### Running the Notebook
After downloading the notebook, open it in Colab and run the cells sequentially to start using QueryMate.
