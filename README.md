[![Python app test](https://github.com/mxm32/aipi561-project1/actions/workflows/main.yml/badge.svg)](https://github.com/mxm32/aipi561-project1/actions/workflows/main.yml)

# Project 1
## AIPI 561: Operationalizing AI | Summer 2022
### Miranda X. Morris | MD/MEng Candidate at Duke

This is a CLI tool that uses a pre-trained model from HuggingFace used to translate text from English to Mandarin.
[HuggingFace Reference](https://huggingface.co/Helsinki-NLP/opus-mt-en-zh)

## General Overview
 1. Input URL of target website to translate
 2. Load the pre-trained model from HuggingFace 
 3. Generate the translation

## Getting Started

Create a virtual environment. Example:

`python3 -m venv venv`

Activate the virtual environment:
`source venv/bin/activate`

Run the make file:
`make all`

## Usage
Generate a translation from target article: 
```
python3 main.py --url "https://en.wikipedia.org/wiki/Artificial_intelligence_industry_in_China"
```
<img width="650" alt="wiki-article" src="https://user-images.githubusercontent.com/88257891/182968735-56a61ec6-13f6-47c1-8fda-a610c2386cee.png">


## Sample Demo

Input:
```
The artificial intelligence (AI) industry in China is a rapidly developing multi-billion dollar industry
```

Translated Output:
```
中国的人工智能(AI)工业是一个迅速发展的数十亿美元的工业
```
Testing translation accuracy by cross-checking with Google Translate:
<img width="600" alt="sample-translation" src="https://user-images.githubusercontent.com/88257891/182968367-04e958aa-d5f1-4a52-9095-fca6f44b6eb2.png">

