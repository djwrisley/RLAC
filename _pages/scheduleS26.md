---
title: Schedule
permalink: /schedule/
toc: true
toc_label: "Spring 2025 Schedule"
toc_sticky: true
toc_icon: "calendar"
---

<div style="background-color: #57068C; padding: 40px 20px; margin: 0 0 30px 0; text-align: center; border-radius: 0;">
  <h1 style="color: white; margin: 0; font-size: 2.5em; font-weight: 300; letter-spacing: 2px;">Reading Like a Computer</h1>
</div>

## Spring 2026 Course Schedule

This schedule is organized by week. Reading and assignment details will be posted on the course site as we progress through the semester. All material is subject to change at the instructor's discretion based on our progress in the course. 

Materials: 

The course learning materials are composed of numerous online articles & tutorials, interdisciplinary writing from the web, videos, digital projects in addition to traditional academic readings.  **There will be no books for purchase.**  Students will have access to ebook chapters available through NYU Libraries. Readings & other materials will be listed here a few weeks in advance of the courses. 

For this course you will need to make some accounts and download some software. We will make use of [Visual Studio Code](https://code.visualstudio.com/download), as well as a number of web-based tools. You will also be assigned access to [Posit Cloud](https://posit.cloud/) within a few weeks.  If you are familiar with [RStudio](https://posit.co/downloads/) and already have it downloaded, you can download the notebooks and use them on your own machine. For beginners, I recommend the cloud based version.  These resources are all at no cost to you. 

---

## Important Dates from [NYUAD Registrar](https://nyuad.nyu.edu/en/about/administration-and-governance/undergraduate-academic-calendar/2025-2026-academic-calendar.html)

| Date | Event |
|------|-------|
| Tuesday, January 20 | **First Day of Classes** |
| Monday, February 2 | Add/Drop Deadline (14-week courses) |
| Sunday, February 16 – Wednesday, March 18 | Ramadan |
| Tuesday, March 10-15 | **Reading Day & Finals for 7 week courses (no classes)** |
| Monday-Friday, March 16-20 | **Spring Break / Eid Al-Fitr Holiday (no classes)** |
| Monday, March 23 | Classes Resume (14-week courses) |
| Friday, April 3 | Withdrawal Deadline (14-week courses) |
| Friday, May 8 | **Last Day of Classes** |
| Saturday, May 9 | All work due |

---

## Part 1: Digital Textual Analysis — Thinking with Corpora

### Week 1 (Jan 20, 22)
**Topic:** Beginnings, a.k.a. "So Many Books, So Little Time"

What does it mean to read like a computer? What does it mean to write for a non-human audience?

| Date | Preparation | Activity | 
| :--- | :--- | :--- |
| 20 Jan | none | Introduction to course, expectations, syllabus | 
| 22 Jan | <br> -[Speed Reading](https://www.youtube.com/watch?v=oLgBDHhV-xM) (Tonight Show) (6 mins) <br> -[How to Speed Read](https://www.youtube.com/watch?v=ZwEquW_Yij0) (Ferriss) (9 mins) <br> -"[How Many Books Will You Read Before You Die](https://lithub.com/how-many-books-will-you-read-before-you-die/)?" <br> -"[The beginning of silent reading](https://qz.com/quartzy/1118580/the-beginning-of-silent-reading-was-also-the-beginning-of-an-interior-life)" <br> -[People Don't Read But LLMs do](https://blog.glyndarkin.co.uk/ai/people-dont-read-but-ll-ms-do/) | <br> -Discussion of Readings<br> -[Introduction to static sites](https://djwrisley.github.io/RLAC/blog/introduction-to-static-sites/) | 


### Week 2 (Jan 27, 29)
**Topic:** Reading, Fast and Slow, Close and Distant  / Reading All of Anything 

What are different reading strategies available to us: close reading vs. distant reading, slow reading vs. fast reading, summarizing with an LLM? What can each approach tell us? What do they miss? How do we work with large amounts of text? What are corpora?

| Date | Preparation | Activity | 
| :--- | :--- | :--- |
| 27 Jan | <br> -Create a [GitHub account](https://github.com) (if you don't have one alredy) <br> -Provide your Github username [here](https://docs.google.com/spreadsheets/d/1QA7GWYJ9SY4m7BmJBrMBXQXl-nKB_VfLCZqnSWSU0Tc/edit?usp=sharing) <br> -Install a [text editor](https://code.visualstudio.com/download) (e.g. VSCode) <br> -Install [Github Desktop](https://desktop.github.com/download/) <br> -[Can Computers Read (Literature)?](http://doi.org/10.6092/issn.2532-8816/8511) (Kestemont / Herman)  <br> -[The Pitfalls of Using Google Ngram](https://archive.ph/8kDTp) and the PLOSOne [article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0137041) mentioned here<br> -[Google n-gram](https://books.google.com/ngrams/) vs. [BookWorm](https://bookworm.htrc.illinois.edu/develop/) <br> -"[My Secret Editing Weapon](https://medium.com/the-greengrocers-style-guide/my-secret-editing-weapon-the-google-ngram-viewer-2006d20411c6)" | <br>-Discussion of Readings <br> -[Gentle Introduction to Static Sites](https://djwrisley.github.io/RLAC/blog/introduction-to-static-sites/) |  
| 29 Jan | <br> -[What is Fan Fiction?](https://en.wikipedia.org/wiki/Fan_fiction) <br> -[Harry Potter fandom](https://en.wikipedia.org/wiki/Harry_Potter_fandom) <br> - [What is AOOO?](https://en.wikipedia.org/wiki/Archive_of_Our_Own) <br> -Listen: [Distant Reading](https://newbooksnetwork.com/distant-reading) (a conversation with [Ama Bemma Adwetewa_Badu](https://artsci.washu.edu/faculty-staff/ama-bemma-adwetewa-badu)) - 14 mins <br> - [What is Markdown? Why Use it?](https://www.markdownguide.org/getting-started/) | <br> -[Setting Up a Site for Coursework](https://djwrisley.github.io/RLAC/blog/creating-a-static-siteS26/) <br> -Discussion of openness in the age of AI <br> -Explore Harry Potter fan fiction with [Voyant Tools](https://voyant-tools.org) (source: AOOO) with a small selection of the 390K+ fan fiction in Drive. | 

### Week 3 (Feb 3, 5)
**Topic:**  Voyant and Project Gutenberg  

Hands-on with Voyant Tools for text analysis and visualization. Exploring public domain texts from Project Gutenberg and PLOSOne journals. Introduction to R and RStudio for text analysis. Basic programming concepts and statistical approaches to text.

| Date | Preparation | Activity | 
| :--- | :--- | :--- |
| 3 Feb | <br> -[Introduction to Voyant Tools: Basic Distant Reading](https://www.youtube.com/watch?v=rQbf6V77ScA&t=1s) <br> -[About Plos One Open Access Journal](https://journals.plos.org/plosone/s/journal-information) <br> -Building the Invisible College (Crymble, in Drive) <br> -[A Beginner's Guide to Using Voyant Tools for Thematic Analysis](https://works.hcommons.org/records/9rxyc-c7729) <br> -|  <br> -Harry Potter fan fiction in Voyant <br> -specialized fields of knowledge from PLOSOne journals in Voyant <br> -Discussion: What is your invisible college?  <br> -[Go further in Voyant Tools with Spyral Notebooks](https://voyant-tools.org/spyral/learnspyral@gh/Tutorials/)| 
| 5 Feb |  <br> -Make an account at [posit.cloud](https://posit.cloud/) <br> -Skim-watch [RStudio for Beginners with PositCloud and chatGPT](https://www.youtube.com/watch?v=YUGnQQ_hyNI&t=3721s) <br> -[Humanities Data Essentials in R](https://hdf.benschmidt.org/R/) check out the section "Working in a Programming Language" | <br> -Discussion <br> -Making sure our GitHub pages are working <br> -some Rmd notebooks for working with Harry Potter fan fiction and PLOSOne journal articles | 

**First Assignment Due: Wednesday, Feb 25** Choosing a corpus and critically analyzing some of its contents by frequency. Full Instructions [here](https://djwrisley.github.io/RLAC/blog/assignment-1-corpus-analysisS26/).
{: .notice}

### Week 4 (Feb 10, 12)
**Topic:** More Text Analysis with R. The Anatomy of a Word Cloud. Creating and interpreting visualizations.

| Date | Preparation | Activity | 
| :--- | :--- | :--- |
| 10 Feb | <br> -Listen to [Distant Reading: A Conversation with Ama Bemma Adwetewa-Badu](https://newbooksnetwork.com/distant-reading) <br> -[ch 2 of Hermeneutica, "How Computers Measure Words"](https://direct.mit.edu/books/monograph/3494/HermeneuticaComputer-Assisted-Interpretation-in) |   <br> -Continued work with Rmd notebooks <br> -Discussion of podcast  <br> -Building a HeatMap visualization |
| 12 Feb | <br> -Exploring A Corpus of South Asian Fiction |  <br> -more Rmd notebooks  | 

_Ramadan begins. There will be no change in class timings for Ramadan._
{: .notice}

### Week 5 (Feb 17, 19)

Instructor away at a conference. Work on Assignment 1 and Response 1. 

> Extra credit opportunity: Attend an event at Love Data Week at NYU online in NYC or in person in AD and write it up. Worth up to 2 points on Assignment 1.

### Week 6 (Feb 24, 26)

**Topic:** More Text Analysis with R — Most Distinctive Words / TF-IDF. Techniques for identifying key vocabulary in texts. 

| Date | Preparation | Activity | 
| :--- | :--- | :--- |
| 24 Feb | <br> -Most Distinctive Words in a Corpus |  <br> -Rmd notebook:  |
| 26 Feb | <br> -TF/IDF  |  <br> -Rmd notebook:  | 

**First Response Due: Friday, Feb 26** Asking an LLM to interpret a visualization without context. Full Instructions here.
{: .notice}

### Week 7 (Mar 3, 5)
**Topic:**  Sentiment Analysis and Wrap-Up  
Introduction to sentiment analysis for different kinds of texts.
Reflection on Part 1 on working with corpora. and preparation for Part 2.

List of key concepts for Part 1 of the course

Oral Exam week of Mar 2. Sign ups available [here](https://docs.google.com/spreadsheets/d/1m90mbN0lPIxWyw2xtDToG8Fbz4P9jb4xzy_p-NZ5dlI/edit?gid=0#gid=0). 

---

## Part 2: Digital Text Analysis (+ Creating Digital Text) — Project-Based Learning

### Week 8 Approaches to Text Creation from Digitized Sources (Mar 24, 26)
**Topic:** OCR and HTR  
Optical Character Recognition and Handwritten Text Recognition. Working with digitized documents from archives and special collections.  

### Week 9 (Mar 31, Apr 2)
**Topic:** Approaches to analyzing OCR'd or HTR'd text. More sentiment analysis, TF/IDF and Distinctive Words. Integrating CoPilot into our Analysis (benefits, drawbacks and ethics)

**Second Assignment Due: Friday, April 3**
{: .notice}

### Week 10 (Apr 7, 9)
**Topic:** Stylometry  
Computational stylistic analysis. Author identification, authorship attribution, and style analysis. Work with class writings. 

### Week 11 (Apr 14, 16)
**Topic:** Word Embeddings 1  
Introduction to word embeddings and semantic relationships. Understanding distributed representations of meaning.

**Second Response Due: Friday, April 18**
{: .notice} 

### Week 12 (Apr 21, 23)
**Topic:** Word Embeddings 2 / Topic Modeling 
More with word embeddings. Visualization and interpretation of semantic spaces.

### Week 13 (Apr 28, 30)
**Topic:** Comparison of Approaches & Lab Time  
Hands-on work on final projects. Individual and small group consultations with instructor.

### Week 14 (May 5, 7)
**Topic:** Lab Time / Final Presentations Preparation  
Continued project work. Preparing presentations and written components.

### Week 15 (May 12, 14)
**Topic:** Final Presentations and Wrap-Up  
Student presentations of final projects. Course reflection and synthesis.

**Third Assignment Due: Friday, May 15**
{: .notice}

---

## Course Components

The semester is structured around two main pedagogical phases:

### Phase 1: Foundations in Digital Textual Analysis (Weeks 1-7)
Focus on understanding computational approaches to text and developing practical skills with tools and methods. Weekly classroom sessions combine lectures, discussions, guided exercises, and lab work.

### Phase 2: Project-Based Application (Weeks 8-15)  
Application of learned methods to new texts and contexts. Greater emphasis on independent work, student-directed projects, and peer learning. Lab sessions provide support and flexibility for diverse project approaches.

---

## Course Structure and Meeting Format

Classes are structured with the following components:

- **Synchronous sessions (TuTh 11:20-12:45)** — Lectures, discussions, workshops, and lab time
- **Asynchronous materials** — Recorded tutorials, readings, and supplementary resources posted online
- **Office hours (Tu 2:15-3:15 PM in person; Th 7-8 PM virtual)** — Individual consultation and project support

The course emphasizes active engagement and experimentation. Students are expected to attend classes regularly, participate in discussions, and engage with assigned materials and tools.

