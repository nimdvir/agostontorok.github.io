---
layout: post
title: Senior Data Science competition on Drivendata
date: 2016-08-04
tags: science data statistics
---

Our team, YetAnotherDirtyCelticGod, finished at [28th place](https://www.drivendata.org/competitions/42/leaderboard/) in a very strong field of data enthousiasts at the Senior Data Science challenge on [drivendata.org](https://www.drivendata.org/). 
The challenge was a rather tricky one, the participants had to predict what the person is doing based on accelerometer, infrared camera, video annotations. Given the structure and status of the raw data, here a substantial amount of time was invested in data cleaning, feature extraction and engineering. After that, we very experimenting with several methods and ended up using only [Extremely Randomized Trees](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.65.7485&rep=rep1&type=pdf) for the task. This choice was motivated by the empirical S/N ratio in this task, and because ERT made us able to do extremely fast prototyping and parameter search. 
We hope, that soon we have time to clean the code and make it available for those who are interested on github, just like with the [Rossmann challenge](https://github.com/agostontorok/KaggleRossmannChallenge). Stay tuned!
