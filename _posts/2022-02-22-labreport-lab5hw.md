---
layout: post
title: Lab 5 Post
subtitle: Python
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---
## The Python Experience

When I lived near my parents, I remember how many times I only had time for a quick visit but ended up staying for hours, just because I had been caught by a scene of a crime investigation TV show. I would sit, my father would make us popcorn, and time flew. Although not very socially skilled, the csi hacker has a charm of its own, right? I may have never been ambitious enough to take a course on digital skills and expect to become the next digital Jesus, Matrix-style, but I cannot say I'm not guilty of picturing myself at least as the csi nerd everytime I open a dark-screened Athom in my computer.

The prospect of learning to work with Python feeds such feelings. But *actually* learning it is more like a humility exercise. Besides the constant realization that I have nothing to say in class (exactly because we wordlessly are forced to admit we know nothing), a mistaken and exaggerated critical sense I'm not able to turn off reminds me that I also have no idea what I'm going to use all of that for. At the same time, deep inside, I know that is the best it could be: I think no thoughtful Professor would choose to increase the burden of their own and of the students with endless explanations. And in this affirmation I find solace.
:)

In order to ground and materialize these essential things for this specific part of the process, I present here my answers to the homework questions.

**Question 1 answer**: The function did not work properly because it separated the 's from the word it was connected, undoing the purpose of contraction (i.e.: make two words one). That happened because there was a command in the algorithm staying that every term on the list must be a letter, so that any non-alphabetical character will be read as a separation of words. This was stated in the function by the code "\W+".

**Question 2** Well, it didn't print correctly. At first, I just went straight to the part of the questions in the notebook, without running all the previous functions above. Following the instructions below the cell, I went back and ran all the functions until the Beyoncé verse worked as in class (this one wasn't working either). Even so, running the cell right above question 2 did not work well: I got a "SyntaxError". The Professor saw that coming and helpfully provided a reason for the problem: I hadn't deleted anything. But I was afraid to, since I didn't know which string we were talking about or how should I split it. My quest finishes here for today. :/

[ pause for breathing, the break of a new day ]

I learned some important things:
1. The hashtag tells python to skip some information, so we use to include human language in the code;
2. I didn't need to go over the whole document and run all the cells; I just needed to run the ones on the same section I'm working at to run it correctly.
3. I was erasing the wrong content; I should have erased only the second line marked by a hashtag;
4. *THE ACTUAL ANSWER FOR THE QUESTION*: Now I was able to run the function correctly because the only thing I did was erase the second hashtaged line and write "I just want to finish before I forget it". The algorithm had been programmed to display a list of the words that made up the sentence I wrote, and, since there was no graphic accent or punctuation (any non-alphabetical character), it ran the list of words perfectly.

**Question 3**: After running the cell, it generated a spreadsheet that organized the contents of the folder called "eebo-test", displaying in different columns the filename, the author, the title, the date (year of publication) and the numer of times the word "virtu" or "vertu" appeared in each document.

**Question 4**: According to google, the character ""ˆ"" in a regular expression, marks the beginning of something. However, I still couldn't figure out what this reg is doing here.

## Readings vs Lab

I think the main text from the ones assigned was Schmidt's *Do Digital Humanists Need to Understand Algorithms?*. That reading prepared ourselves for the lab since it foregrounded the actual role of programming in our field. We discussed the different expectations from computational scientists *versus* digital humanists when dealing with programming. While the former is engaged with creating, sophisticating, and simplifying algorithms, the latter will be more focused on finding suitable algorithms according to their research needs (or even creating one, if necessary), and ultimately, understanding what these codes are doing or can do in practice.

Given the difference in the approach of algorithms, Schmidt proposes, for the digital humanities, the use of the term *transformations* instead, in order to emphasize the focus on producing certain results, or modifications, instead of the engineering of making and polishing the algorithms themselves. Transformations, therefore, points to a more instrumental and pragmatical use of programming. That also means, as Schmidt states in the end of his text,

*It is good and useful for humanists to be able to push and prod at algorithmic black boxes when the underlying algorithms are inaccessible or overly complex. But when they are reduced to doing so, the first job of digital humanists should be to understand the goals and agendas of the transformations and systems that algorithms serve so that we can be creative users of new ideas, rather than users of tools the purposes of which we decline to know.*

In other words, we should not only use algorithms according to our needs, but also be able to move the next step in case we need different transformations, even if it means creating new ones, so that we can use existent ideas creatively as well as devising new ones.
