# HackAI-Intro-fine-tune-LLMs

Collection of materials to introduce Python programmers to fine-tuning, instruction tuning and working with contextual embeddings.

This repo was developed to support an afternoon tutorial run by Mariam Cook as part of the University of Exeter Institute for Data Science and AI HACK AI Hackathon series with the following goals:

1. Fine-tune the BERT LLM on debate text labelled as being from UK Labour and Conservative Party politicians' contributions. (For completeness the notebook used to scrape parliamentary debates is also included in this repo).

2. Locally prompt the InstructABSA model for aspect term extraction and aspect-based sentiment analysis (already fine-tuned version of TK-instruct, an instruction-tuned version of the T5 LLM), using the InstructABSA prompt templates.

3. Use BERT embeddings to compare language used about policies in different year under different governments (common crawl source files and subsets of this data from the Bristol Web Archives for Social Sciences Datathon https://www.urbaneconomies.co.uk/datathon.html also included in the data folder)

We will be working on Google Colab, if you are working in a different environment please see the requirements.txt and make the necessary adapatations to model saving. 



