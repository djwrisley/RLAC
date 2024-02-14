---
title: "Assignment #1: Cultural Heritage By the Numbers S24"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignments
  - Metadata
  - APIs
  - Harvard Art Museum
  - S24
---

## Guidelines for the Assignment: 


Cultural Heritage By the Numbers is an assignment in one step. It builds upon the work we did in class on February 6 and 8 using the Jupyter notebooks in posit.cloud. There are three parts to the assignment.

This assignment can be done alone or in pairs. If it is done in pairs, please compose a common markdown file which you place in both student sites. 

This exercise focuses on the ways that the metadata obtainable from the Harvard Art Museum API can tell us something about historical and present world cultures, as well as the way they are represented in the contemporary Western museum. You can think of this assignment a way of taking a look at the way that museums collect different kinds of art from around the world, as well as how we can use an API to understand better the entirety of collections of art museum, rather than only what is "on display", as well as its collection practices. 

**Part 1**: Exploring the HAM [website](https://harvardartmuseums.org/) and comparing it to the API-derived data. Explore the HAM website as well as the `All_Objects.csv` file (found in the posit.cloud project, as well as in the data folder of our shared drive). Choose a few pieces from the collections of interest to you. Was the website easy to use? What are you able to say about the art pieces from the metadata available to you in the web-based interface? What might you want to understand about these objects that is impractical to do from the interface alone that seems possible from the csv file? 

**Part 2**: Thinking about culture in museum terms:  Look at the 254 rows of `All_culture_information.csv` (found in the posit.cloud project, as well as in the data folder of our shared drive) and comment on what this says about how a contemporary US museum views the world. Use part 1 of the notebook `Harvard_API_All_objects` to determine for a given culture what are the most viewed items are in the HAM website? What about the least viewed? Go back to the HAM website and look up some of these objects, both highly viewed and less viewed. What are they? Can you speculate on why the most and least viewed objects are what they are? 


**Part 3**: Using a choice of three cultures and the notebook `Harvard_API_Compare_Cultures`, build word clouds based on the combined descriptions and titles of the objects from those cultures. Does this summary of the words tell us something about the way that cultures are important in a US art museum? Use the stop word function to remove certain words to "dig in" to the textual data a bit more? When you remove very high frequency words what do you discover? Compare your results across cultures. Using this same notebook, with the accession year data and the time series bar chart, what can you say about the acquisition of works by the Harvard Art Museum coming from these three cultures? Do they tell you something about the relative popularity of art in a university museum in the United States? Can you compare it to other museums you have visited or know about?


**Advanced optional extra steps:** 

If you complete one of the following steps, you can skip step one in the instructions above.

-Using the notebook `objects_with_places` choose one culture and try to make a map of the "creation place" of the art? Does the geography of the creation of the art pieces match the culture in question, or not? Why?

-If you are already good in Python, can you adapt the code to look for the most common colors? The most common techniques? Or any other value from the attributes? What are you able to say about the cultures from these other persepectives? 


Your assignment does not need to answer all the questions above, nor does it need to follow the steps one by one.  It should be about 1250 words long, with relevant images saved from the notebooks, embedded links, etc. Use a markdown cheatsheet such as this [one](https://www.markdownguide.org/cheat-sheet) to stylize your post, adding different layout features and embedded links if needed. You can refer to the readings if you want to, but this is not necessary for this assignment. 

**Assignment 1 Due date:** 22 February, 20% final grade.
{: .notice}
