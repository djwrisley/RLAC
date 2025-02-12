---
title: "Assignment 1 Working with a Corpus S25"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignments
  - Corpora
  - S25
---

## DRAFT Guidelines for the Assignment:  

The Corpus Assignment, otherwise known as Assignment 1, will be completed in one step. It builds on work we did in the textual portion of the class, particularly with Voyant Tools and the RMarkdown files in posit.cloud. This assignment can be done alone or in pairs.

This exercise has three main elements: (1) choosing a corpus of three texts (or three sets of texts) you would like to work with and (2) using digital textual analysis tools to see what kind of exploratory data analysis (EDA) you can do using that corpus, (3) assembling the evidence in a piece of web-facing written work along with visuals. 

**Step 1**: You will need to pick your corpus from the choices below. 

- A. Three different books by the same author taken from [Project Gutenberg](https://gutenberg.org) (perhaps in different genres or at different times of their career).
 
For example, if you use the search function and look for `science fiction` you will find more than 4000 science fiction novel(la)s, many of which are written by the same authors. You could do some research on any of the authors in Wikipedia or in the [Internet Speculative Fiction Database](https://isfdb.org/), and choose three texts by one author. If you know French, there is a large [selection](https://gutenberg.org/ebooks/bookshelf/321) of science fiction too. 

Here are some other ideas in PG: 

- Arthur Conan Doyle, famous for having written the Adventures of Sherlock Holmes, is the author of more than 150 books in PG and in many genres. Pick three. 

- B. Three books on a similar topic from Project Gutenberg.

For example, if you use the search function and look for `artificial intelligence` you will find 20 science fiction novel(la)s on the topic. You could also look for terms such as `alien` or `abduction` or ``

- PG has a number of different "bookshelves", or topical groupings of its books on issues like religion or technology. Explore them and pick three related books. 

- If you would like to look into books separated by [geographical region](https://gutenberg.org/ebooks/bookshelves/search/?query=africa.%7CAnthropology%7CArgentina.%7CAustralia%7CBulgaria%7Ccamp%7Ccanada%7CCIA%7CCzech%7CEgypt%7CFolklore%7CFrance%7Cgermany%7Cindia%7Cgreece%7Citatly%7Czealand%7CMaps%20and%20Cartography%20.%7Cnorway%7Csouth%20america%7Cunited%20states%7C%20united%20kingdom%7CWomen%27s%20Travel%20Journals), try those bookshelves.

- The bookshelf for [India](https://gutenberg.org/ebooks/bookshelf/45) and the date of the books will give you an interesting vantage point for looking at colonial south Asia. You could combine that with a corpus created by a colleague found [here](https://github.com/amardeepmsingh/Colonial-South-Asian-Literature/tree/master).  

- You can also use keywords to find subject headings. For example, "women" will give you many hundreds of [groupings](https://gutenberg.org/ebooks/subjects/search/?query=women).

- C. You could also choose three texts in a language other than English. NB: This will pose certain challenges in the analysis that you can write about in your assignment.  Check here for books in [Chinese](https://gutenberg.org/browse/languages/zh) [Dutch](https://gutenberg.org/browse/languages/nl) [Finnish](https://gutenberg.org/browse/languages/fi) [French](https://gutenberg.org/browse/languages/fr) [Italian](https://gutenberg.org/browse/languages/it) [Japanese](https://gutenberg.org/browse/languages/ja) [Portuguese](https://gutenberg.org/browse/languages/pt) [Russian](https://gutenberg.org/browse/languages/ru) [Serbian](https://gutenberg.org/browse/languages/sr) [Spanish](https://gutenberg.org/browse/languages/es) [Tagalog](https://gutenberg.org/browse/languages/tl) [Telugu](https://gutenberg.org/browse/languages/te).  There are other languages, but coverage is not uniform.  

- D. Three different sets of articles from a single class or multiple classes in your major. 

Whatever your choice may be, you have the option of using three legitimate files, or substituting one of the files with a fake genAI created one, as we did in the case of the science fiction texts. Generating a text of equivalent length with genAI may take considerable extra effort. 

Alternatively, you can source your text files from anywhere else, but if you make a custom corpus, please consult with the instructor before beginning this process. The texts can be short stories or articles, but not less than 1000-2000 words. If you choose your own files, include a copy of all three of them in your assets folder and create links to them for your readers to examine. _If you are not working with texts from Project Gutenberg, then you will need to follow the instructions in the notebook for uploading your own files._ 

**Step 2**: You should do some general research about the authors, the text, the contents. You will want to justify briefly the selection of texts in your assignment. You might even browse them briefly to know generally what they are about. This will help you to contextualize your findings. _This is important so that you are not studying the corpus without a general idea of its contents._ 

> You want to choose texts which have something in common, but also can be thought about as different. The more you know about the texts, the more meaningful the "distant reading" will be. 

**Step 3**: For this exercise you must use both (1) Voyant Tools and (2) the RMarkdown notebook in posit.cloud `Identifying the Most Distinctive Words in Three (Sets of) Texts`. The RMarkdown notebook in posit.cloud `Summarizing a text from Project Gutenberg in a wordcloud` is optional. 

If you want to combine sets of texts from Project Gutenberg into one, you can do so by creating a list of ID numbers like this: 

> gutenbergbook <- gutenberg_download(c(textID1, textID2, textID3, etc))

**Step 4**: Build a set of screenshots from your exploratory analysis. Please be sure to include at least two (2) of them. 

**Step 5**: Use one iframe from Voyant Tools so that you have one interactive visualization. You can get an iframe from the export URL tab. It is called an html snippet. One example looks like this: 

```
<iframe style='width: 444px; height: 408px;' src='https://voyant-tools.org/tool/Cirrus/?corpus=8d8c7ce89087801d676ff4f77d5391fc'></iframe>
```

**Step 6**: Find two (2) of the readings/resources from this term and include references to them in your essay. Feel free to refer to external resources.

Consider the questions raised in class on making Markdown posts legible: using [Markdown Live Preview](https://markdownlivepreview.com/) and [Hemingway App](https://hemingwayapp.com/) as you compose your response.  Keep the F-shape principle for web writing in mind too!

Guiding Questions (you do not need to answer all these questions):

- What did you know about the subject before you began your analysis? 
- What does computer-assisted analysis allow you to see that you wouldn't have seen in a linear read? Would a linear read of all the texts have been possible in the time frame allotted? 
- What is a trend you can identify in the materials? What are you able to learn by looking at the text the way you did? 
- Were there any surprises in your exploration? 
- If you reran the code or redid your Voyant Tools exploration did you get the same results every time? If not, why do you think?  
- Are there any differences in the ways the different wordclouds visualize the words?
- How limiting (if at all) was the notebook that required you to compare three texts, i.e. to compare one text to two others? Was there something else you would like to do? 
- How well would this assignment work for a language other than English? If you worked on texts not in English, what challenges did you face?


You assignment should be about 1500 words, or about a 8 minute read. Please publish it to your course site with a visible tab. 

**Due date: 28 February 2025**. 

