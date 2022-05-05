---
layout: post
title: Magic, witchcraft, and sorcery in ESTC  
subtitle: A critical introduction to my own dataset
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
### Critical introduction to _Magic, witchcraft, and sorcery in ESTC_

Early Modern studies have received significant contributions from Digital Humanities (DH henceforth), which have provided wider access to old texts and manuscripts through digitization. That made stories that were for a long time nothing but tales to become more objectively visible since now that we can trace the places, the people, and the processes that colored even the most tragic chapters of History, including the waves of witch persecutions in Early Modern Europe. In this sense, a good example is the [Survey of Scottish Witchcraft Database](https://witches.shca.ed.ac.uk/index.cfm?fuseaction=home.main), the result of a DH project from the University of Edinburgh. It contains almost 4,000 records of people accused of witchcraft in Scotland, as well as documentation of witchcraft beliefs, witches’ executions, and even their defenses. Additionally, in 2019, an extension of this project gave origin to a platform entitled [Places of Residence for Accused Witches](https://witches.is.ed.ac.uk/), using the retrieved data to support a mapping visualization tool that reunited more than 3000 locations of people persecuted for witchcraft all over Scotland. A similar project, run by Kirsten C. Uszkalo, [The Witches in Early Modern England](ttp://witching.org/) used witchcraft and magic vocabulary to organize the structure of data visualization of cases of accused people in England and the possible relations between these cases. Those projects undoubtedly presented remarkable contributions to both literary and historical studies of witchcraft. However, both of them would benefit from further research and regular technical updates as online resources quickly become outdated and consequently do not function properly without maintenance - not rarely for lack of constant and steady funding.

Besides, both aforementioned platforms focus majorly on the information about the people accused of witchcraft, collecting biographical and legal information related to the reunited cases, leaving the role of material print and book culture aside. The [English Short Title Catalog](http://estc.bl.uk/F/?func=file&file_name=login-bl-estc, henceforth referred to as ESTC), on the other hand, collects data about a vast amount of Early Modern Print texts in English, including details such as the number of pages, size, printers, authors of books - and much more. Yet while ESTC focuses on Early Modern texts in general, it offers few options for sorting out specific themes, except for the keyword search tool.

But what if we could visualize the texts from ESTC specifically about witchcraft, providing a panorama of writers, themes, and the timing of print discourses at the time? This is exactly what I attempted to do in the dataset _Magic, witch and sorcery in ESTC_ (available [HERE](https://docs.google.com/spreadsheets/d/13GizQQfnYoX8mUWyaxI8vih2bAp40yvsGDxJD2gdsjM/edit?usp=sharing)). The dataset aims at collecting the books discussing witchcraft and sorcery present in the ESTC database. It is therefore composed of the results of a search performed on the platform after the key terms “magic”, “witch”, and “sorcer” in the form of word roots, so all derivatives of such keywords could be captured as well by adding an asterisk symbol (*) right after each key term. It was important to search for terms other than “witchcraft” (and similarly rooted words) because the labeling of witchcraft has not been a stable one (Durrant and Bailey);  although authors sometimes resorted to other terms to refer to specific notions of occult practitioners, they frequently used synonyms almost interchangeably.

While searching ESTC, I looked for answers to questions such as: who was writing about witchcraft and magic from the 16th to the 18th centuries? Which years saw the most relevant number of publications on the topic? What was the main site for publication and the most relevant printers at the time? Can we find any possible patterns in the answers to these questions?

After obtaining and collecting the search results using Zotero, I gathered all the data in a single spreadsheet, relating all  titles that mentioned magic, witchcraft, or sorcery. Thus, I could find possible ways to understand and picture, for example, how frequent texts about witchcraft in the Anglophone world were (from the earliest work retrieved, Richard Whitford’s A dayly exercice and experience of dethe, published in 1534 up to the latest publications, dated back to 1800). Furthermore, by generating pivot tables, it was possible to observe that, in the ESTC collection, most books on witchcraft were published in London (equivalent to 75% of the books in the dataset Magic, witch and sorcery in ESTC). There’s also an interesting peak in the number of publications in 1785, with 18 titles in the same year, while 1682, 1712, and 1800 saw the greatest number of different authors writing about witchcraft, with 13 people authoring books about it. More details about the process of creation of the dataset can be found in the appendix at the end of this post.

The year of publication of these texts is certainly interesting, because most of them came up exactly during the decline of witch trials and executions, which, according to Goodare (2016), started to fade after the 1620s in Europe. However, we must take note that witch persecution waves were anything but even; it is not realistic to attribute tendencies to whole countries when there was so much difference in each region’s communities. Crossing the time of publications and actual trials and executions, as well as the site of publishing might lead to fruitful research that can reveal novel information about the realities at community level that influenced and triggered witch trials. The data also shows that, differently from what was believed, conversations about witchcraft did not fade after the dawn of Illuminism in the 18th century. Indeed, though the data obtained goes up to 1800, the presence of a peak in publications in this very year suggests ongoing publishing at the time, as can be noticed in the chart below.


![Number of books about Witchcraft per year](https://vanessabcs.github.io/assets/img/chart_blue.png)



Using the dataset as a starting point, I explored one of the authors in order to trace texts that responded to him. Reginald Scot, famous for writing the first encyclopedic book in English about witchcraft in a blatant skeptical tone (_The Discoverie of Witchcraft_), could easily have become targeted by many other authors for his boldness, either positively or negatively, the reason why I looked for other publications that directly mentioned him. To do so, I used the [Early English Books Online](https://quod.lib.umich.edu/e/eebogroup/)’s database (henceforth EEBO) since it contains full texts, instead of general information about the publication, as in ESTC. I then used the basic search tool to look up the name “Reginald Scot”. I collected all the search results with Zotero once again and consulted each text that came up manually to find how Scot was mentioned, either favorably, unfavorably, or neutrally. Inside each text, I searched not only “Reginald Scot”, but also other possibilities, such as “Scot”, “Reginald”, or “Mr. Scot”. The results of this research can be found on the spreadsheet [HERE](https://docs.google.com/spreadsheets/d/1ldxzjm6IOFyqRNi5SWSDheUfeepqmkKCm-7E_TCbXgs/edit?usp=sharing).

This process helped me to understand in a concrete way the responses to Reginald Scot, which were overwhelmingly negative, as can be observed in the chart below, which represents by “null” official records that mentioned Scot’s address, for example; “TRUE” indicating the authors/texts that mentioned him in a flattering way; and “FALSE” representing the texts in which I found direct negative remarks to _Discoverie of Witchcraft_. The data collected prompted me to reflect on why it seems to have taken so long for other texts to be published in response to him since most texts that do so were published long after Scot’s death. Scholars of witchcraft (Almond, Davies, Levack) have mostly reported the opposing responses to Discoverie of Witchcraft (1584), but how negative were they actually when they mentioned Reginald no more than three times in the whole book? Acknowledging and close reading these mentions might reveal that Discoverie might have been more “influential” than usually thought or patterns between opposing and/or favorable texts and their authors that might help us understand better why they might have responded the way they did, and even point to authors apparent refusal to discuss Scot’s hypothesis. In “What gets counted counts” Catherine D'Ignazio and Lauren Klein illustrate the impact of analyzing in detail ignored manifestations of gender diversity, and the principle of zooming and giving voice to the ignored could be as well applied here.


![Responses to Reginald Scot's _Discoverie_](https://vanessabcs.github.io/assets/img/chart_orange.png)



This research has, obviously, many limitations. First of all, data is not the same as facts. As well pointed out by Rosenberg, it can be understood as simply “a constellation of information”, a fragment of reality, no matter how big the database. In terms of this research, a window has been provided to the particular collections of ESTC and EEBO, consequently not encompassing other important texts published in languages other than English, or even in England, if not present in the sources. Therefore, we cannot assume that this was exactly what the discussion about magic looked like in the Early Modern period, but we can definitely see a huge amount of information coming from such comprehensive sources as ESTC and EEBO, at least regarding England and parts of the Anglophone world.  

Dealing with such limitations gave me the opportunity of witnessing how wrong it is to assume that data, especially in its visualization forms, does not represent an incontestable, neutral manifestation of truth. As well said in “On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints” by Catherine D'Ignazio and Lauren Klein, the mythical appearance of objectivity and lack of affect or emotion that one feels while reading a chart might hide not only researcher’s goals and motivation when creating the dataset, but also the very limitations of any dataset.  In addition, collecting the data required me to polish my spreadsheet skills and reflect on concerns about data cleaning, thinking about when to clean and why to do it in the first place, as discussed by Rawson and Muñoz. But the most significant lesson learned is that scholars in the humanities can develop digital skills if the necessary resources are available and we persist until we see the fruits of a repetitive and sometimes boring (though rewarding) job.

I think of the present dataset as a sort of the first step into an investigation of the discourses of witchcraft in the Early Modern era. Expanding its coverage, including manually collecting data from a more varied number of sources, may shed light on the discursive dynamics in ways never seen before. For example,  I would be able to trace connections between these authors, investigating the conversations in print culture about witchcraft. That would allow me to understand the responses to these texts and even assess more accurately the actual impact of each book on following publishings. Which texts were written in response to each other, and in what tone? It would be interesting in such a database, for instance, to examine the boundaries of belief and skepticism on magic by collecting all the texts and examining their key terms and topics using a tool like Voyant to guide to the most relevant texts for close reading of those which have clear connections and references to each other. We would be able to trace the waves and tendencies in the discourses of witchcraft, depending on the setting and the publishers’ personal and political interests as well.

The main takeaway from my dataset is, at this stage, displaying who was invested in publishing about witchcraft, when, and where, as a way of highlighting primary patterns for further research. Scholars in the field of History and English literature of the Early Modern period might benefit from it, while I would, ideally, make it open for the public in general, given that whoever downloaded the data gave some personal information and the reasons for interest in it. Although witchcraft and magic have been ignored by many scholars as a topic not worthy of extensive research, exploring the actual discourses and the relations between them might unlock important insights for studies of popular politics, especially by making us aware of rhetorical strategies at play among Early Modern writers and book professionals.



#### Appendix

*Step-by-step of the dataset creation*

*Spreadsheet 1 - searching ESTC under the roots “Witch”, “magic”, and “sorcer”*

1. Collected the search results using Zotero, making a separate spreadsheet for each keyword's respective results;
2. Checked for duplicates and merged them to avoid losing any piece of information;
3. Cleaned all the blank columns it gave me;
4. Checked the spreadsheet for possible mistakes (such as incomplete dates, different writing for the same value, e.g. “[London” instead of simply “London”);
5. Gathered all the results in one single spreadsheet, and, using Excel, identified all duplicates and cleaned them;
6. Copied and pasted the resulting spreadsheet into a google sheets file, for easier sharing;
7. Created the codebook and added it to the google sheet as a new tab;
8. Created three other tabs with pivot tables and visualization charts: one to know how many places were publishing about witchcraft each year and another to know how many titles were published each year, yet another to describe the number of books published per site (city).

*Spreadsheet 2 - searching EEBO for texts mentioning “Reginald Scot”, using his name as a keyword search term*
1. I searched EEBO using “Reginald Scot” as a keyword search term.
2. Collected the search results using Zotero;
3. Checked for duplicates and merged them to avoid losing any piece of information;
4. Checked the spreadsheet for possible mistakes;
5. Had to rewrite the years of publication manually. For some reason, Zotero gave me modern-day years (possibly the year the value was inserted in EEBO), and I checked the link for each publication to correct these dates to the registered early modern year.
6. I went back to EEBO to search each of the records given for a more detailed search, now looking for “Reginald”, “Scot”, and “Mr. Scot”, in order to retrieve all possible mentions to him besides the full form of his name.
7. Added a column to the spreadsheet entitled “Mention to Scot”, to which I copied and pasted the extract where each entry from EEBO mentions Reginald Scot, followed by the number of the page as provided in EEBO.  
8. Added another column entitled “Favorable to Scot?”, which I filled out with the values: True, False, or Null, depending on the tone and message of the extracts (considering their wide context) where “Reginald Scot”, “Scot”, or “Mr. Scot” was found in the EEBO basic search. “True” refers to texts I could identify agreeing with Scot’s proposal, or simply citing him in a positive perspective, “False describes books that exposed their author’s disagreement with Scot’s claim, or referred to him in a negative tone, and “null” was assigned for texts that did not express any agreement or disagreement with Scot, usually books of records.
Made a pivot table and a chart comparing the number of books that presented a favorable, unfavorable, or neutral position to Scot’s _Discoverie_.


—---------


*Works cited*

Almond, Phillip C. "Doubt and demonology: Reginald Scot’s The Discoverie of Witchcraft." The Science of Demons: Early Modern Authors Facing Witchcraft and the Devil. Edited by Jan Machielsen, Routledge, 2020, pp. 133-148

Davies, S. F. “The Reception of Reginald Scot's Discovery of Witchcraft: Witchcraft, Magic, and Radical Religion.” Journal of the History of Ideas, vol. 74, no. 3, University of Pennsylvania Press, 2013, pp. 381–401, https://doi.org/10.1353/jhi.2013.0021.

D’Ignazio, C., & Klein, L. (2020). 3. On Rational, Scientific, Objective Viewpoints from Mythical, Imaginary, Impossible Standpoints. In Data Feminism. Retrieved from https://data-feminism.mitpress.mit.edu/pub/5evfe9yd

Durrant, Jonathan, and Michael D Bailey. Historical Dictionary of Witchcraft. Lanham, MD: Scarecrow Press, 2012.

Goodare, Julian. The European Witch-Hunt. Routledge, 2016.

Levack, Brian P. The Oxford Handbook of Witchcraft in Early Modern Europe and Colonial America. Oxford University Press, 2013.

Katie Rawson, and Trevor Muñoz. “Against Cleaning.” Debates in the Digital Humanities 2019. University of Minnesota Press, 2019. 279. Web.
