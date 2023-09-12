---
title: "Assignment #1: Cultural Heritage By the Numbers"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - Assignments
  - Metadata
  - Harvard Art Museum
  - chatGPT
  - F23
  - Notice
---

## DRAFT Guidelines for the Assignment: 

# DRAFT Guidelines for the Assignment: 

The Cultural Heritage By the Numbers is an assignment in one step. It builds upon the work we did in class on September 12 and 14 using the Jupyter notebooks in posit.cloud. 

This assignment can be done alone or in pairs. If it is done in pairs, please compose one markdown file which you place in both student sites. 

This exercise focuses on exhibitions that have been documented at the Harvard Art Museum the information about which has been obtained via the museum API. You can think of this assignment a way of doing an "archeology" of past art exhibitions. 

**Section 1**: Explore the HAM [website](https://harvardartmuseums.org/) as well as the csv file included. Choose two favorite exhibitions and record their unique IDs. Was one method of finding the exhibitions easier than the other? What are you able to say about the exhibitions from the highest level metadata? 

**Section 2**: Filtering by exhibition ID, build a list of objects which are recorded as appearing in the same exhibition. What can you glean from this basic information? Build a word cloud based on the combined descriptions and titles. Does this summary of the words tell us something about the exhibition? Do you need to filter it to create a meaningful visualization? 

**Section 3**: What are the x most viewed items in the exhibition? The x least viewed? Do these count suggest something about the nature of exhibition ("greatest hits" or a discover of unknown objects?) Are these numbers suprising to you? Do they tell you something about the relative popularity of the exhibition? 

Repeat this process for another exhibition and compare. Are there noticeable data gaps? 

**Section 4:** How might we use the API to create "phygital" museums or exhibitions? Check out the [documentation] for sample projects and come up with one or two of your own. 

Advanced extra steps: 

1. Can you adapt the code to look for the most common colors? The most common techniques? Or any other value from the attributes? 

2. Include your affirmation or critique of chatGPT's answer to the prompt below about museum APIs. 

Your assignment does not need to answer all the questions above, nor does it need to follow the sections step by step.  It should be about 1250-1500 words long, with relevant images saved from the notebooks, embedded links, etc. Use a markdown cheatsheet such as this [one](https://www.markdownguide.org/cheat-sheet) to stylize your post, adding different layout features and embedded links if needed. You can refer to the readings if you want to, but this is not necessary for this assignment. 

**Assignment 1 Due date:** 28 September, 20% final grade.
{: .notice}


Here is what chatGPT says about the possibility of museum APIs. Feel free to critique or agree with it on some of the points it makes.  

> Prompt: What is the importance of metadata in museum APIs? How complete or accurate are they usually? What can we do using museum APIs in terms of analysis, critique and innovation? 

ChatGPT response (3 August version):

Metadata in museum APIs (Application Programming Interfaces) plays a crucial role in enhancing the accessibility, usability, and potential for innovation within the museum and cultural heritage sector. Here are some key points on the importance of metadata in museum APIs and their usual completeness and accuracy, as well as the possibilities they offer for analysis, critique, and innovation:

Importance of Metadata in Museum APIs:

Accessibility and Searchability: Metadata provides descriptive information about museum artifacts, such as title, artist, date, medium, and provenance. This information makes it easier for users to search and find specific items within a museum's collection through APIs.
Contextualization: Metadata helps provide context to artifacts, such as historical significance, cultural context, and curatorial notes. This contextualization is essential for understanding and interpreting the objects within the museum's collection.
Interoperability: Standardized metadata formats and controlled vocabularies within APIs enable interoperability with other cultural heritage institutions and platforms, making it possible to aggregate and share data across institutions.
Research and Scholarship: Researchers and scholars rely on accurate metadata to conduct in-depth studies, comparisons, and analyses of artworks and artifacts. Metadata aids in organizing and citing sources accurately.
Preservation: Metadata can include information about the conservation and preservation of objects, helping museums track the condition of their collections and plan for restoration efforts.
Completeness and Accuracy of Metadata:

The completeness and accuracy of metadata in museum APIs can vary widely based on several factors, including the institution's resources, priorities, and the specific goals of the API project. Some common considerations include:

Resource Constraints: Smaller museums or institutions with limited resources may have less comprehensive metadata compared to larger, well-funded institutions.
Metadata Standards: Institutions that adhere to recognized metadata standards, such as Dublin Core, METS, or VRA Core, tend to have more standardized and accurate metadata.
Data Entry Practices: The accuracy of metadata depends on the diligence of data entry practices, including the training of staff responsible for cataloging and metadata creation.
Updates and Revisions: Institutions that regularly update and revise their metadata are more likely to have accurate and complete records.
Analysis, Critique, and Innovation Using Museum APIs:

Museum APIs open up several possibilities for analysis, critique, and innovation:

Research: Researchers and scholars can use museum APIs to analyze trends in art history, track the provenance of artworks, and study the cultural impact of specific artists or movements.
Educational Tools: Developers can create educational tools and apps that use museum API data to provide historical context, interactive exhibits, and guided tours.
Artificial Intelligence and Machine Learning: Machine learning algorithms can analyze metadata to identify patterns and connections within museum collections, leading to new insights and recommendations for visitors.
Art Market Analysis: The art market can benefit from APIs by analyzing auction data, pricing trends, and the popularity of specific artists or genres.
Digital Storytelling: APIs enable storytellers and curators to craft engaging narratives that draw connections between different artworks or historical periods.
Exhibition Planning: Curators can use API data to plan exhibitions, identify gaps in the collection, and make decisions about acquisitions.
In conclusion, metadata in museum APIs is essential for improving accessibility, enabling research, and fostering innovation within the museum and cultural heritage sector. While completeness and accuracy can vary, efforts are being made to standardize metadata practices. The possibilities for analysis, critique, and innovation using museum APIs are vast, offering opportunities to engage audiences and advance scholarship in the field.