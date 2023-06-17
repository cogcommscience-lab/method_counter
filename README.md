# Method Counter
Code for extracting various research methods discussed in journal articles

## How To Cite
Huskey, R. & Schmälzle, R. (2024). Missing The (Neurocognitive) Revolution: How Media Psychology Became Entangled By Mentalism and What To Do About It. In Shackleford, K. & Bowman, N. D. (Eds.), Oxford Handbook of Media Psychology. (2nd Edition). New York, NY: Oxford University Press.

## What does this code do?
This code reads in research pdfs, does a dictionary based word-count of methodological categories, and plots the results. It assumes:
- There is one research article per pdf
- The first four characters of the pdf file name encode the publication year
- pdfs are grouped by journal, and stored in a journal specific directory
