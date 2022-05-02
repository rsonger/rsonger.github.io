---
layout: page
title: NLP for literature reviews
description: Using Python with NLTK to search paper abstracts
img: assets/img/projects/reviews.jpg
importance: 1
category: research
---

One of my first projects using the Python language was for collaborative research with the **Kanazawa University Practical Pharmacology Laboratory**. The goal was to automate the literature review process using natural language processing (NLP).

This project used a lot of resources:
- [Cosmetic ingredient database (Cosing) - Ingredients and Fragrance inventory](https://data.europa.eu/data/datasets/cosmetic-ingredient-database-ingredients-and-fragrance-inventory) for an inclusive list of cosmetic ingredients
- [PubChem PUG View web service](https://pubchemdocs.ncbi.nlm.nih.gov/pug-view) to collect data on each ingredient's therapeutic uses and toxicity
- [PubMed E-utilities](https://www.ncbi.nlm.nih.gov/books/NBK25497/) to search research papers for adverse effects on skin related to each compound
- [Natural Language Toolkit (NLTK)](https://www.nltk.org/) to process the acquired paper abstracts for relevance

I published my work for this research in the school's bulletin. Here are the slides and abstract below.

**<a href="//www.slideshare.net/RobertSonger/a-natural-language-processing-approach-to-reviewing-research-abstracts" title="A Natural Language Processing Approach to Reviewing Research Abstracts" target="_blank">A Natural Language Processing Approach to Reviewing Research Abstracts</a>** from **<a href="//www.slideshare.net/RobertSonger" target="_blank">Robert Songer</a>**

<iframe src="//www.slideshare.net/slideshow/embed_code/key/FpoWHwwEJrLlvZ" width="595" height="450" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> 

> Research literature reviews have largely moved online and researchers must search through large quantities of digital documents to find research related to their academic pursuits. With recent developments in Natural Language Processing (NLP), computers can perform most of the searching and reduce the amount of time it takes researchers to find the papers they need. In this report, we introduce three basic NLP techniques (tokenization, frequency distributions, and in-sentence collocations) for searching the written texts of research abstracts downloaded from an online database. Real examples written in the Python programming language are provided along with a discussion of their efficacy in a project at Kanazawa University where an online research database was searched for research related to the adverse effects of hundreds of pharmaceutical compounds.

The source code used for this project is also available on [GitHub](https://github.com/rsonger/CosIng-Toxicity), but be warned! It is just a basic repository without a README or even source code comments. I'm sure I could tidy up the code if I ever have the time to go back and apply all the best practices I've learned since completing this project in 2020.