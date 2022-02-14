---
layout: post
title: Exploring Post45 HathiTrust data's spreadsheet
subtitle: Creating pivot tables
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
**A reading exercise**

Woking with databases described in spreadsheets is, first of all, a reading exercise, especially at the level of decoding. For example, [Post-45 Hathi’s website](https://view.data.post45.org/index) provides a short though clarifying description for each metadata field, so that we can come up with pivot tables to separate specific sets of data that might be transformed (or simply, read) as relevant information for different purposes. Here I played with three metadata fields to offer an example of what information can be read from them: the authors, the geographies, and the subjects.


**Pivot Table 1: Authors**


As illustrated in the picture above, by making up a pivot table out of the names of the authors, we can clearly see the ones most widely represented (by the number of available titles, copies or editions) in the repository. In this case, we can not only read that Trollope, Dickens and James make up the top three popular authors in the archive, but also that no women reached similar representation since Jane Austen is the only woman in the top ten authors in the library.


**Pivot table 2**

In the next pivot table, it is possible to understand that mostly accounted places the works come and speak from are either the USA or European countries. However, there's a problem to be solved: how come it separates equally countries and states? For example, we see that New York is equally compared to other countries. Even so, it is still possible to interpret that the top geographical regions represented in the archives are exact representatives of the global North.


**Pivot table 3**

The final pivot table, the one generated on the metadata field of subjects, allows one to see which topics readers of that particular archive are going to have more access to. However, at the same time we can conclude that the collection is strongly focused on works dealing with WWII, we don't have further information about whether the war is the main theme or one of the themes in the accounted books. At the same time, "lesbians" seems to be on the top ten subjects represented in the archive, but we cannot have a clear picture of what is understood as a book about lesbians or simply mentions them.

**Late updates:** I really wanted to add some pictures to illustrate the pivot tables, but I failed. I read in online forums that HTML language would work fine within a md sheet, but maybe it doesn't. Maybe I wrote the incorrect path for the image file. I'm sure by next week I'll be able to insert images and make this a little bit more fun, though. I also just realized my link code also did not work. I tried to clean it up but so far, nothing has changed on my wsite.