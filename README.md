# Emoji Chatbot – OpenAI Fine-Tuning

This project demonstrates how to fine-tune an OpenAI language model to generate responses using emojis.  
The notebook walks through the full workflow of preparing training data, validating the dataset, fine-tuning a model using the OpenAI API, and testing the resulting chatbot.

The goal of the exercise was to better understand the **fine-tuning lifecycle for generative AI models**, including dataset preparation, model training, monitoring, and evaluation.

---

## Project Overview

Large language models can be customized to behave in specific ways through fine-tuning.  
In this project, a model is trained to respond using **emoji-based communication**, showing how model behavior can be modified using structured training examples.

The notebook demonstrates:

- Preparing JSONL training data
- Validating data formatting
- Uploading data to the OpenAI API
- Running a fine-tuning job
- Monitoring training progress
- Testing the fine-tuned model

---

## Technologies Used

- Python
- OpenAI API
- Jupyter Notebook
- JSONL training datasets
- Pandas (data preparation)

---

## Workflow

1. Prepare emoji conversation training examples  
2. Convert examples into OpenAI fine-tuning JSONL format  
3. Validate dataset formatting  
4. Upload training file to OpenAI  
5. Launch fine-tuning job  
6. Monitor training status  
7. Test the resulting chatbot

---

## Example Behavior

The fine-tuned model learns to respond to prompts using emoji-based communication, such as:

User prompt:
How are you today?


Model response:
😊👍✨


---

## What I Learned

This project helped me better understand:

- The workflow required to fine-tune generative AI models
- The importance of high-quality training data
- How prompt-response pairs influence model behavior
- How to manage and monitor training jobs through the OpenAI API

