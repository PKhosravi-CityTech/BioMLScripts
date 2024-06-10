# QueryMate

QueryMate is an AI-powered question-answering system built using the LlamaCpp model from the langchain library. This system is designed to provide precise answers to user questions and allows for adjustable response parameters based on user feedback.

## Getting Started

To get started with QueryMate, follow these steps:

### Prerequisites

- Python 3.6 or later
- Install the required libraries:
  ```bash

  pip install langchain-community
  pip install llama-cpp-python

  ```

### Download the Model

You need to download the SynthIA-7B-v2.0-16k model file from Hugging Face. 
Visit the following link and download the latest or the second latest version of the file 
named synthia-7b-v2.0-16k.Q3_K_S.gguf:

  ```bash

  https://huggingface.co/TheBloke/SynthIA-7B-v2.0-16k-GGUF

  ```

### Setup
1. Clone this repository:

```bash
# Install Git if not already installed
!apt-get install -qq git

# Clone the repository
!git clone https://github.com/PKhosravi-CityTech/BioMLScripts.git

# Navigate into the directory
%cd BioMLScripts/QueryMate

```

2. upload the model file in the appropriate notebook. Update the model_path in the code and follow the steps.

