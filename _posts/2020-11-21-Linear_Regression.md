---
layout: post
title: Linear Regression
categories:
- General
---

Recently, I've have been learning about linear regressions in my statistics class as well as in my data science work. My instructor and I thought it would be a great idea to take advantage of this opportunity to use this math topic in my programming practice. First, I worked on making sure my data was loaded in properly for the project and then I started out by using the linear regression calculation that I could use with seaborn. When I first saw the line, I wasn't quire sure if that was correct. I thought it would look different with the point on the graph, but how could I not believe the code? This is a function that probably has been used frequenty by other data scientists. It had to be accurate. With these uncertainties on my mind, my instructor challenged me to write my own linear regression without using all the shortcuts. I thought this would be much more difficult than it actually was. Luckily, I found a great website that explains linear regression (which I will link somewhere on this page) to help me break down each part of the formula. Once I had come up with all my variables and completed the math in my code, I showed it to my instructor and it worked! I felt extremely happy that I was able to code something that I actually learned about in my stats class! The only downside of my finished work was that it was very long, so my instructor helped me to narrow down some of the longer pieces of code I had into a cleaner version. I then used my new function with my precipitation and water level data. It turned out that the computer was right and the line that it had graphed earlier with seaborn was at the exact same location as the line that had been created on the graph with my code. This was exciting because that meant that my math was correct, but this also meant my intial uncertainty about the original graph had been false. The seaborn function was right (my bad). Overall, this was a great learning experience and challenged me to use previous knowledge to consruct something that was practical and helped me to remember the topic of linear regressions better. Below this explanation I have my two graphs. The one with the blue line was the original calculation with the seaborn function and the one with the orange line is the line that was calculated from the linear regression function that I wrote. 


{% include figure.html image = "https://raw.githubusercontent.com/olivia1117/LakeWaterLevelData/gh-pages/Water%20Level%20vs.%20Precipitation%20with%20computer%20made%20linreg.png" %}






{% include figure.html image = "https://raw.githubusercontent.com/olivia1117/LakeWaterLevelData/gh-pages/Water%20Level%20vs.%20Precipitation%20with%20lin%20reg.png" %}


Link to helpful website about linear regression: 
<https://towardsdatascience.com/linear-regression-by-hand-ee7fe5a751bf>
