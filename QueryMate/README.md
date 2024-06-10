<img src="https://github.com/PKhosravi-CityTech/BioMLScripts/raw/main/Images/QueryMate.png" alt="QueryMate" width="150" height="150" align="left" style="margin-bottom: 40px;">

# QueryMate

QueryMate is an AI-powered question-answering system built using the LlamaCpp model from the langchain library. This system is designed to provide precise answers to user questions and allows for adjustable response parameters based on user feedback.



## Getting Started

To get started with QueryMate, follow these steps:

### Prerequisites

- Python 3.6 or later
- Make sure you are on GPU or TPU as this program takes 15 minutes on CPU, 5 minutes on GPU, and just a few seconds on TPU in Colab.
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

### Download the QueryMate model
```bash

https://github.com/PKhosravi-CityTech/BioMLScripts/blob/main/QueryMate/QueryMate.ipynb
```
### Running the Notebook
After downloading the notebook, open it in Colab and run the cells sequentially to start using QueryMate.
