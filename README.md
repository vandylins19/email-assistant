# Email Assistant via GPT-3

![python](https://img.shields.io/badge/Python-3.9.0%2B-brightgreen)
![openai](https://img.shields.io/badge/openai-0.15.0%2B-blue)
![streamlit](https://img.shields.io/badge/StreamLit-1.2.0%2B-purple)
![license](https://img.shields.io/badge/license-MIT-green)

A project for DS5899 Transformer

### Timeline

2022/03/16 - Demo created

2022/04/18 - :hugs: Hugging Face Deployed

### Web App

Deployed on [Hugging Face](https://huggingface.co/spaces/HayashiShio/email-assistant-special-course)

### Notebook Tutorial

Click [here](https://colab.research.google.com/github/vandylins19/email-assistant/blob/main/Tutorial.ipynb) to see the descriptive notebook.

### How to Run the Demo:

* [Sign up](https://beta.openai.com/) for an OpenAI account
* Clone this repo to local
* Install streamlit and openai by running commands:
  * pip install streamlit
  * pip install openai
* Run the frontend locally by running the command in the project path:
  * streamlit run frontend.py
* Copy the [API key](https://beta.openai.com/account/api-keys) and input it.

### Critical Analysis

+ The apparence of the front end remains a lot of space for improvement.
+ The app didn't customize the training of the model. A better published example is InstructGPT.
+ Bug testings are insufficient. Input errors are not caught and handled manually.

### Resource Links

+ [OpenAI tutorial](https://beta.openai.com/docs/quickstart)
+ [Streamlit documents](https://docs.streamlit.io/)
+ [Aligning Language Models to Follow Instructions](https://openai.com/blog/instruction-following/)
