---
layout: post
title: Lab 4 Post
subtitle: Voyant
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
## The Voyant Exercise

**Question 1: How does this change the word cloud, and what are these changes telling you? Write down a short answer in your notes document.**

Taking off the filter for stopwords makes the word cloud completely different. That happens because such stopwords start to take over basically all word occurrences, since they are usually the most common words in English language, being also the most frequent words in *any* text. Therefore, looking at a word cloud like this wouldn't give us much distinctive information, unless the focus of our research are exactly words like prepositions, articles and other terms considered "non-content".

**Question 2: Why is relative frequency sometimes a more useful or accurate measure of a term’s importance than raw frequency? Write down a short answer in your notes document.**

For me, the relative frequency can be more useful sometimes because it indicates the frequency of a term per million, in one document, instead of all the documents available in the database.

**Question 3: What is this document? And, more importantly, what have you learned about the term “mcas” in our corpus overall, and/or the utility or value of “significance” metrics like TF-IDF?**

The present document is an obituary and mcas is a title abbreviation many people in the document share. Therefore, there's not much useful information contained in this word here, so it could be discarded the same way a stopword would be.

**Question 4: Looking through this list of terms and their “Comparison” values, what observations can you make about terms that are more likely to occur in the humanities corpus vs. terms that are more likely to occur in the science corpus? How are these terms different? Write down short answers to these questions in your notes document.**

Considering that the larger the value, the stronger its association with a certain corpus, the terms I found to have the highest values were, in this order: 1) students (0.00630), 2) humanities, 3) faculties. On the other hand, science, research and researchers (respectively) were the most science corpus' related words, followed by scientists, health, cancer, data, climate, computer and brain). Interestingly, the top 10 most mentioned words in the humanities were education-related (faculty, studies, courses, major, college), signaling that in the human sciences there seems to be a much more present concern on educational (both pedagogical and institutional) issues.

**Question 5: What tool(s) did you explore? What did this tool(s) help you to observe about this data and/or what did you learn about this data using this tool(s)? Alternatively, what did you hope to learn about this data using this tool and how (or why) did reality seem to fall short of that expectation? Write down short answers to these questions in your notes document.**

I decided to explore the "phrases" tool, not only because it can be useful for ESL teaching/learning purposes, but mainly because it allowed me to have a brief overview of the way students are represented in science vs humanities articles. There seems to be a tendency, for example, of using much more action verbs in the sciences' side whereas in the humanities there are many linking verbs. Maybe it points out to a tendency to talk about who these students are, about defining them much more than in sciences, where they are mentioned in terms of what they do, or might/will do.

I think the tool can be really useful, especially if one is dealing with huge amounts of information. However, I often felt frustrated when trying to load the website and it just wouldn't work. I can see how this tool could be used with linguistics research, for example. But I'm curious to see how I could actually use in my future classes.

## Lab 4 vs. Sarah Allison's text

Grounded by Sarah Allison excellent text, we had an important discussion last class over the use of "other people's data", considering the implications that might have. Voyant is a tool that can work wonders with datasets somebody else made, but first of all, should we be making such use of other people's work?

To answer this question, we need to keep in mind that there is no point in simply copying and pasting raw data. The bare minimum to be data is to read this data in terms of understanding what it is made of, and most importantly, understanding why it is framed the way it is. What concerns rely on its own structure and information? This is already *some* work. Beyond that, we can think of the importance of collaboration given its capacity to explore the potential datasets have when explored by another researcher, who carries other concerns and maybe has other resources available. The more we ethically assume the position of collaborating with each other's databases can also build on more transparent data manipulation. As Allison pointed out well, it is not merely about "replicating data". Before anything, we must take other people's databases as opportunities to "reconsider what it means to build on other people's work. (6)"
