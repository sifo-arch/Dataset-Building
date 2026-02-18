## Overview
This dataset is created to train machine learning models to localize Human-AI
transitions in Arabic text. i.e., detecting the writing style change between human
and AI within the same document.  
The dataset has been carefully investigated and the content within it is consistent and well structured.  
The complete version of the dataset is stored in the file "dataset.csv".

## Contents of the dataset
Number of samples: 7000  
Columns:
- index: the index of the example.
- url: the url where the Arabic text is obtained (None).
- text: the Arabic article.
- origin: the source of the Arabic text.
- ai: the arabic text after inserting AI segments (sentences or phrases).
- generated_by: the LLM used to add the AI text.

## LLMs used to expanded articles
GPT-oss (3500 samples)
Cogito v2.1 (3500 samples)
Note: I did not use Gemeini because google is no more providing 250 RPD, it provides only 20 RPD. However, Gemeini 3 flash preview is not expensive, I can expand the dataset to 10000 samples by adding another 3000 articles edited by Gemini.

## Source
This dataset is built from "ANAD-Arabic-News-Article-Dataset", it can be found in:
https://github.com/alaybaa/ANAD-Arabic-News-Article-Dataset
