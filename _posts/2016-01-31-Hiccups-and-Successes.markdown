---
layout: post
title: "Hiccups and Successes"
categories: weekly-post
---

![Keith Gibson](/images/Keith-Gibson-at-Mozarts-to-Aspect.jpg "Keith Gibson")

As before, the three questions:

> 1. What did you do this past week?
>
> 2. What's in your way?
>
> 3. What will you do next week?

##The week in review

This was the first full week of classes, and it provided much more insight into the structure of the course. I neglected the readings to my own detriment, suffering on the in-class quizzes as a consequence. It's become increasingly more apparent that this course demands much more attention than initially expected. 

On the other hand, lectures were interesting. Each lecture provided another avenue of thought regarding the Collatz project, such as other avenues of optimization. For example, we can question how to best compute a solution, what the essential values to compute over are, how to store values, and what specific values to store.

Finally, I've become more familiar with Python's philosophy, which has helped bring some of its syntax decisions into focus. As practice, I've been playing with writing scripts to handle some of the repetitive, mutil-step tasks of Collatz; see the tip at the end for a verbal description of one such script.

##Issues

Forgetfulness, for one. It's obvious that I need to pay more attention to my calendar, and to get the readings done on time. While reading after the fact is helpful (I am here to learn), it's useful to know the material for the quizzes.

There's also the matter of some of my goals for last week, which went forgotten until just now, such as revamping this site. If things look better by the time this post is read, then I've managed to do somthing about it.

##Down the road

 - Read the materials, and finish Collatz.
 - Find a scheduling system to keep things in order.

##Helpful tip of the week

Learn to write small, simple scripts to automate repetitive tasks. As an example, I wrote a script that would read `stdin` line by line, and when it finds a special comment, it begins to write to `stdout` until encountering another special comment. Combine this with piping and an extra makefile command, and the creation of SphereCollatz.py can be simplified to a single command, such as `make sphere`.
