--- 
title: "Dataset creation, publishing and maintenance"
author: "Niko Partanen"
date: "2021-08-24"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  These are course materials, or resources into which the lecture slides 
  are based on, in the workshop Niko Partanen taught in Baltic Summer 
  School of Digital Humanities 2021: "Digital Methods in Humanities 
  and Social Sciences"
biblio-style: apalike
csl: chicago-fullnote-bibliography.csl
---

# Introduction

This document accompanies the workshop *Dataset creation, publishing and maintenance: Practices, solutions and open questions*, taught by me, Niko Partanen, in Baltic Summer School of Digital Humanities 2021: "Digital Methods in Humanities and Social Sciences". 

The goal is to discuss the current situation and best practices of research data management and publishing, with the practical portion where we go through with examples how to publish research data in Zenodo through GitHub integration. 

These materials may be eventually turned into something that has more emphasis on linguistic work, as that's what I still know the best, but I'm also very happy to get comments that would help make it more suited for digital humanists and others. 

## Slides

The workshop taught based on these materials is currently split into three lecture modules, which are:

1. [Introduction, FAIR & Open Access](https://docs.google.com/presentation/d/1ZRmQT3W_-KqQqy63MvjoY1TKBVwOrN4pX1tpErai-D0/edit?usp=sharing)
2. [Zenodo, GitHub & different publishing methods](https://docs.google.com/presentation/d/1bpaIHR9PF2diJrhze9GZQojnyhCCGp9dzbj_iLDrLuU/edit?usp=sharing)
3. [Creating and maintaining a dataset](https://docs.google.com/presentation/d/1KyJuUQcI_QNL4xzGLXelJn79xO34ThfeOJWRvHQHXKs/edit?usp=sharing)

These slides are more less continuously living until the workshop, and will be saved when it is over. 

## Instructors background

I'm a doctoral student in the University of Helsinki in the Department of Finnish, Finno-Ugrian and Scandinavian Studies. In my PhD my research topic is grammatical, geographic and sociolinguistic variation in Komi language. Komi is an endangered Uralic language spoken in Russia. It is distantly related to languages such as Finnish and Estonian. I'm planning to defend my PhD in March / April 2022. This has been a moving window, but now it is time to close it. 

Besides my PhD I've engaged in various different activities. I have worked for a long period in Germany and France, mainly in research related positions, but at times in more research or research infrastructure oriented tasks. I've also worked and collaborated with various archives, and have used various archival materials in my research. I know particularly well the Tape Archive of the Finnish Language, located in the Institute for Languages of Finland. 

These earlier works have led to various research tracks that aren't directly connected to my PhD. In my earlier project our team focused to integrating language technology better into language documentation workflows, and there are currently multiple collaborations where I continue this work. Our project also worked with archiving various linguistic datasets. I know text recognition technologies very well, and have participated to projects where different linguistic publications or manuscripts have been converted into searchable materials. I've also worked extensively with speech recognition technologies, and most recently with keyword spotting from audio. Since 2017 I've been actively contributing to the Universal Dependencies project, and remain responsible for two Komi treebanks. 

I have fairly strong programming background in both R and Python. I like to use them in data analysis and visualization, but I've learned that I don't want to be responsible of system critical software infrastructure.

## Instructors limitations

From this point of departure I have good experience in managing linguistic datasets, both written and spoken, and including audio and video. I have been negotiating the re-publishing permissions for some old materials, and also collaborated with archives to clarify whether various resources can be made available or not. In the same vein, I have not personally collected new spoken data since 2016, and I have not worked with data that is collected for purposes of social sciences, for example. I have very limited experience from survey data. 

So I consider myself mainly a linguist who likes to integrate the existing materials into our contemporary resources, mainly because it feels useless and disrespectful to collect new research materials as if tons of work would had not been done before us. At the same time, if I argue that this is a good approach, I also consider that I have to make my own materials accessible in a particularly suitable way. Besides linguistic research I'm also interested more widely how language is used in communication and interaction, and about the social processes related to the language, especially in endangered language context. In my MA studies I worked with the language shift in Komi and Karelia, and do plan to return to these topics eventually as well. I also find large historical text corpora very promising for further research, and have been extending my scope also to that direction. 

Additionally, my point of departure in this workshop material is that we have to get these things done. It is important to store and share research data appropriately, and lots of things are still in flux. As will be discussed, we often operate with relatively abstract notions and concepts, and if you really want to get a clear answer, nobody is there to provide that. So we have to navigate somehow in this unclear space. And we can do it. But I think the mindset we need for this is also pretty specific. At times when one reads about metadata and data reuse a picture inevitably emerges where we describe and build these things for some machine to monch away automatically. Automatization, machine readability, reproducibility, these are all terms commonly discussed. 

However, I don't think this is not really the point. We are experts of our own fields, doing very specific research datasets as parts of wider research communities. Research datasets are not only automatic targets of metadata harvesters, but actively used research artefacts in our professional community, and widely discussed also at this level. The goal is not to make some technical apparatus run perfectly, but to advance our scientific work, and together move toward better practices and conventions. And because most likely new users of our research datasets are also researchers themselves, it can be much more useful not to try to cater some needs we think there are, but to provide bit rough and messy data that worked for us, and let others build upon it. 


