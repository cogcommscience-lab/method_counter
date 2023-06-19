# Method Counter
This repo contains code for:
- Extracting various research methods discussed in journal articles (method_extractor.ipynb)
- Calculating reliability between human and dictionary-based annotations (reliability_analysis.ipnyb)

## How To Cite
Huskey, R. & Schmälzle, R. (2024). Missing The (Neurocognitive) Revolution: How Media Psychology Became Entangled By Mentalism and What To Do About It. In Shackleford, K. & Bowman, N. D. (Eds.), Oxford Handbook of Media Psychology. (2nd Edition). New York, NY: Oxford University Press.

## What does method_extractor.ipynb do?
This code reads in research pdfs, does a dictionary based word-count of methodological categories, and plots the results. It assumes:
- There is one research article per pdf
- The first four characters of the pdf file name encode the publication year
- pdfs are grouped by journal, and stored in a journal specific directory

## What does reliability_analysis.ipnyb do?
This code calculates reliability (Cohen's Kappa) and confusion matrices for human/dictionary annotation. It assumes:
- It assumes there are two data files, one long and the other wide

## Show me an example

![Plot showing results of different methods discussed in three academic journals](https://github.com/cogcommscience-lab/method_counter/blob/main/combined_plot.jpg?raw=true)

![Plot showing confusion matrices for each type of ](https://github.com/cogcommscience-lab/method_counter/blob/main/confusion.jpg?raw=true)
