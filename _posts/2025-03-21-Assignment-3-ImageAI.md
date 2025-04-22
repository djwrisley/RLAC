---
title: "Assignment 3 Visual AI and Culture S 25"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignments
  - Corpora
  - F25
  - images
---


## DRAFT Guidelines for the Assignment:  

In this assignment we will continue to work with materials and algorithms discussed in class. We will use Orange Data Mining and DV Explorer to carry out this task and to write a small critical essay. This can be worked on in pairs, or alone. 

### Part One: 

The very first thing you have to do is to build an image dataset, a corpus. 

You should choose a corpus of images (you should have at least 75).

## Guidelines for the Corpus building exercise: 

- a dataset of images from a cultural domain is required, one about which you know a little *or a lot* is welcome. 
- it does not have to be "high" cultural or from the GLAM sector. 
- it does not have to be designed with computation in mind.
- it should address something that you suspect is not close to Microsoft COCO or Google's Inception. 
- its collection can be automated, but does not have to be.
- it should not have faces of people in them.  

Tips on automating the collection. 


### Part Two: 

The first computational exercise is a clustering exercise. Some prior knowledge of the subject is important since in the second part you will classify the images into subtypes. Choosing a dataset of images you are not very interested in, or a dataset that you do not have enough knowledge to categorize will make it difficult.  

I suggest you use this part of the assignment to do some exploratory data analysis (EDA). Using the pre-set Orange Data Mining workflow I distributed (images2.ows), you can address the following questions: 

- How does one built-in algorithm such as Inceptionv3 in ODM cluster the data? 
- Do other algorithms give you different results? 
- What features seem to be most characteristic of the different quadrants of the image plot? 
- Using hierarchical clustering, isolate specific clusters to look more closely.
- How "in reading a corpus of visual culture through a neural network, [are you] always also doing the reverse?" (Impett and Offert, 2024)

Make screenshots of the main image plot you generate and annotate it with labels (just typed on manually with a program like Preview) which illustrate in your opinion what combination of features are represented in each of the four quadrants of the plot. Caption the image with the relevant information (i.e. Image Plot generated with Orange Data Mining and the algorithm of your choice). Also include image plot of specific clusters that can help you to understand how the out-of-the-box algorithms (think of the [Monet/Manet video](https://orangedatamining.com/blog/clustering-of-monet-and-manet/) here)

Be sure to comment on how differently you see the images. 

### Part Three:

In the second computaitonal exercise you will categorize the images into at least two different groupings. The categorization is carried out by placing them into folders (bearing a descriptive title). This means that for the purposes of your assignment, you should have two or three copies of the same images, but with specific file names and organized in different folders according to categories you have chosen (e.g. size, shape, color OR origin, quantity, size). For best results, your classification system should be sure to have a somewhat equal number of images in every category. 

For each of the sets of images, please generate a confusion matrix and assess the ability of the algorithm to predict the categories you have chosen. Remember that you can click on the box where there has been misclassification and visualize the misclassified objects in the viewer. 

Guiding questions for this part of the assignment: 

- How well did any of the built-in algorithms you chose predict the categories you established?
- Did you go back and adjust any of your categories? 
- When you isolate the cases of "false positives", i.e. mis-predictions, can you understand why the algorithm got them wrong? (Think about the Monet/Manet mis-prediction case we saw in class).
- If you could train your own algorithm what would you aim to teach it? 

In your write up, you should include insights and ideas from the new book Distant Viewing (Arnold & Tilton), linked to on the syllabus. 

Make sure that you include images from your analysis. 

### Part Three:

In the third computational exercise, I want you to work with multimodal models and your image corpus. 

Generate captions. Use CLIP and or search. 

Here I suspect the idea of "in reading a corpus of visual culture through a neural network, we are always also doing the reverse" will be very obvious. 

What is the relationship of language and your images? 
How does CLIP or the DV explorer organize your materials?




Due:  May 2024, 1500 words maximum. 
