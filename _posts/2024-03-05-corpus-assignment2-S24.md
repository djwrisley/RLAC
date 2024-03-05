---
title: "Assignment 2 Working with a Corpus S24"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignments
  - Corpora
  - S24
---

## Guidelines for the Assignment:  

The Corpus Assignment, otherwise known as Assignment 2, will be completed in one step. It builds on work we did in the textual portion of the class, particularly with Voyant Tools and possibly R Markdown file in Posit Cloud. This assignment can be done alone or in pairs.

This exercise has three main elements: (1) choosing a corpus of three texts (or three sets of texts) you would like to work with and (2) using some digital textual analysis tools to see what kind of exploratory data analysis (EDA) you can do using that corpus, (3) assembling the evidence in a piece of web-facing written work along with visuals. 

**Step 1**: You will need to pick your corpus. Here are some ideas for the corpus. 

- A. Three different books by the same author taken from Project Gutenberg (perhaps in different genres or at different times of their career).
- B. Chat conversations you have with three different human or non-human agents, or three different essays you generate with AI on three related, yet different prompts or using three different text generators. (if you choose this option, include your prompts).
- C. Three sets of articles from different publications or newspapers (perhaps of different political orientation or topic). 
- D. Three different sets of articles from a single class or multiple classes in your major. 

Alternatively, you can source your text files from anywhere else, but if you make a custom corpus, please consult with the instructor before beginning. The texts can be short stories or articles, but not less than 1000-2000 words. If you choose your own files, include them in your assets folder and create links to them for your readers to examine. 

For this exercise you can use both (1) Voyant Tools for all of your texts and (2) the R Markdown notebook in posit.cloud `Summarizing a text from Project Gutenberg in a wordcloud` for at least one of your texts. If you want to combine all three texts from Project Gutenberg into one, you can do so by creating a list of ID numbers like this: 

> gutenbergbook <- gutenberg_download(c(textID1, textID2, textID3, etc), mirror = "http://mirrors.xmission.com/gutenberg/")

_If you are not working with texts from Project Gutenberg, then you will need to follow the instructions in the notebook for uploading your files._ 

**Step 2**: You should do some general research about the authors, the text, the contents. You will want to justify briefly the selection of texts in your assignment. You might even browse them briefly to know generally what they are about. This is important so that you are not studying the corpus without a general idea of its contents. 

> You want to choose texts which have something in common, but also can be thought about as different. The more you know about the texts, the more meaningful the "distant reading" will be. 

**Step 3**: To do your analysis, use Voyant Tools. Remember that each method works with its own constraints. You are free to use whatever combination of forms of analysis you like. 

**Step 4**: Build a set of screenshots from your exploratory analysis. Please be sure to include at least two (2). 

**Step 5**: Use one iframe from Voyant Tools so that you have one interactive visualization. You can get an iframe from the export URL tab. It is called an html snippet. One example looks like this: 

```
<iframe style='width: 444px; height: 408px;' src='https://voyant-tools.org/tool/Cirrus/?corpus=8d8c7ce89087801d676ff4f77d5391fc'></iframe>
```

**Step 6**: Find two (2) of the readings/resources from this term and include references to them in your essay. Feel free to refer to external resources.


Consider the questions raised by Hind in her session on making Markdown posts legible: using [Markdown Live Preview](https://markdownlivepreview.com/) and [Hemingway App](https://hemingwayapp.com/) as you compose your response.  Keep the F-shape principle for web writing in mind too!


Guiding Questions (you do not need to answer all these questions):

- What did you know about the subject before you began your analysis? 
- What does computer-assisted analysis allow you to see that you wouldn't have seen in a linear read? Would a linear read have been possible in the time frame allotted? 
- Was the format in which the corpus reached you sufficient for your purposes? What are some of the shortcomings of the texts? 
- What is a trend you can identify in the materials? What are you able to learn by looking at the text the way you did? 
- Were there any surprises in your exploration? 
- Are there any differences in the ways the different wordclouds visualize the words?
- How well would this assignment work for a language other than English?


You assignment can be 1250-1500 words, or about a 6-8 minute read. Please publish it to your course site with a visible tab. 

**Due date: 21 March 2024**.

We will have a session soon after the deadline with Hind to tweak our posts. Date TBA. 

