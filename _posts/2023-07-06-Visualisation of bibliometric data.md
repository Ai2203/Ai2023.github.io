---
layout: post
title: Visualisation of journal articles' themes
categories: [category 1, category 2]
---

# The goal of the project
I am going to write an essay about the psychology of religious rituals, and I wanted to look into how this field has been approached by scholars in the last decade. The question at hand is rather broad,
so I decided that I need to understand the themes that have been raised and analysed in psychology of rituals. From my previous acquaintance with the field I knew that scholars can focus on the discussion of 
health and psychological benefits of rituals, on the explanation of cognitive and emotional mechanisms of rituals, as well as psychological effects of rituals. 
But in order to get a more general overview of how the field has been developing I needed to look at more data and summarise it, which would take me a lot of time if I were to do it manually. 

# The idea 
So I decided to look into scientific journals on psychology of religion and analyse what themes the articles in the journals have been covering in the last decade. 
I found "The International Journal for the Psychology of Religion"  which is devoted to psychological studies of religion: religious processes and phenomena in various religious traditions. 
The journal was first published in 2003 and since then produces 4 issues each year. 
To analyze the publications of the journal, I decided to focus on its meta-data: titles and abstracts. From my point of view, that data could provide relevant information to answer my question, namely, key words relating to the subject of articles. 

# The process
## Retrieving the meta-data
The [web-site](https://www.tandfonline.com/loi/hjpr20) of the publisher of the Journal allows for the option to download citations for journal articles. 

<img width="787" alt="1" src="https://github.com/Ai2203/Ai2203.github.io/assets/131348177/f1408fac-0cd6-4ec5-9fe7-ddd041200106">


## Adding the meta-data into citation manager

![1](https://github.com/Ai2203/Ai2203.github.io/assets/131348177/25b3cb45-9931-4fa4-ba8a-b731a6dccf79")


## Analysing the data
To do the analysis of the data, I used VOS viewer [tool](https://www.vosviewer.com). It is a tool that visualises bibliometric networks.
VOS Viewer can use various types of data for analysis. I chose to analyse text data, which I uploaded to VOS viewer from the citation manager. 
The tool offers different configurations for the analysis. Since I wanted to analyse themes and topics emerging in the journal articles, I chose to look at titles and abstracts and to see co-occurence of items. 
Later, the application offers a list of items (words) that appear in the titles and abstracts more than once (that configuration can be changed, as a result of which it is possible to have more or fewer items). Not all the items appear meaningful,
so it is needed to go through them and un-check the ones that are particularly irrelevant. For instance, I had a result of 437 items, which I went through manually and deleted the ones related to methodology, such as "female"; "item responce theory"; "age group"; etc. 

Then the application runs the analysis and produces a map (see examples). 
### Example 1. 
In this case I chose to see all the terms appearing in titles and abstracts, which resulted in a huge amount of items, many of which are not helpful.
![3](https://github.com/Ai2203/Ai2203.github.io/assets/131348177/3a4ed0f1-9c5e-49d6-bd58-e05afe1b95ee)

### Example 2.
So I saturated the amount of items further (choosing to show only the items that occur more than once).

![4](https://github.com/Ai2203/Ai2203.github.io/assets/131348177/65bc3162-0738-45d4-86e6-6406a1742a24)

![5](https://github.com/Ai2203/Ai2203.github.io/assets/131348177/b3378844-2d7f-4982-952e-c528bf31c19b)

This example shows clusters of topics: one of them is circled around affiliation, another around coping. There is also a cluster of topics dealing with motivation, existence, and transcendence; and some smaller clusters such as the one about religious identity in adolescents.
The overlay visualisation also shows years in which certain themes appear. For instance, topics of religiousity of adolescents have emerged in more recent years, while the analysis of religious affiliation and its relation to other spheres of life has been going on for a few years.

# Possible alterations and future developments of the process
1. VOS viewer can download data using Crossref API, which could be useful to make the process more automated to retrieve larger bullks of meta-data. I tried to use the option, but the number of retrieved items was smaller. 
2. With VOS viewer it is also possible to analyse co-authorship, which could be helpful with a different set of data (e.g. across several journals).
3. A more precise selection of items could be done in collaboration with others (for now I was only relying on my own knowledge and intuition). 
