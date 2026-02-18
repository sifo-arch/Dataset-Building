## Overview
This dataset is created to train machine learning models to localize Human-AI
transitions in Arabic text. i.e., detecting the writing style change between human
and AI within the same document.
The complete version of the dataset is stored in the file "dataset.csv".

## Contents
Number of samples: 1000  
Columns:
- index: the index of the example.
- url: the url where the Arabic text is obtained (None).
- title: the title of the Arabic article.
- text: the Arabic article itself.
- origin: the source of the Arabic text.
- ai: the arabic text after inserting AI segments (sentences or phrases).
- generated_by: the LLM used to add the AI text.

## Source
This dataset is built from "ANAD-Arabic-News-Article-Dataset", it can be found in:
https://github.com/alaybaa/ANAD-Arabic-News-Article-Dataset
