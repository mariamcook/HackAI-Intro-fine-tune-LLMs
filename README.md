# HackAI-Intro-fine-tune-LLMs
HackAI-Intro-fine-tune-LLMs

Collection of materials to introduce Python programmers to fine-tuning, instruction tuning and working with contextual embeddings.

This repo was developed to support an afternoon training session with the following goals:

1. Fine-tune the BERT LLM on debate text labelled as being from UK Labour and Conservative Party politicians' contributions. (For completeness the notebook used to scrape parliamentary debates is also included in this repo).

a. Learn about the architecture behind Large Language Models (LLMs). 
b. Load some pre-labelled text examples from UK parliament debates, and split them into a training and test dataset
c. Fine-tune the BERT LLM to recognise whether each debate sample is from a Conservate or Labour party member (at this time the Labour party were in opposition)
d. Review the results from our BERT fine-tuned model, by comparing its predictions to the true labels in the test set
e. Save our fine-tuned model to Google Drive
f. Load the model into a new notebook and check it is working

2. Locally prompt the InstructABSA model for aspect term extraction and aspect-based sentiment analysis (already fine-tuned version of TK-instruct, an instruction-tuned version of the T5 LLM), using the InstructABSA prompt templates.

3. Use BERT embeddings to compare language used about policies in different year under different governments.

We will be working on Google Colab, if you are working in a different environment please see the requirements.txt and make the necessary adapatations to model saving. 



