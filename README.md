# HackAI-Intro-fine-tune-LLMs

Collection of materials to introduce Python programmers to fine-tuning and prompting LLMs with few shot examples, and working with contextual embeddings.

This repo was developed to support an afternoon tutorial run by Mariam Cook as part of the University of Exeter Institute for Data Science and AI HACK AI Hackathon series with the following goals:

1. Fine-tune the BERT LLM on text labelled as being from UK Labour and Conservative Party politicians' contributions to 2023 UK governement debates. (For completeness the notebook used to scrape and filter this text is also included in this repo). Debates scraped from: https://www.theyworkforyou.com/

2. Locally prompt the InstructABSA model for aspect term extraction (ATE) and aspect-based sentiment analysis (ABSA) using the InstructABSA prompt templates. InstructABSA is a prior fine-tuned version of TK-instruct, in turn an instruction-tuned version of the T5 LLM. See here for more information about InstructABSA: https://github.com/kevinscaria/instructabsa

3. Use BERT embeddings to compare language used about policies in government news in different years (2024 and 2025) under different UK administrations (common crawl source files and subsets of this data from the Bristol Web Archives for Social Sciences Datathon https://www.urbaneconomies.co.uk/datathon.html also included in the data folder)

We will be working on Google Colab, if you are working in a different environment please see the requirements.txt and make the necessary adapatations to model saving. 



