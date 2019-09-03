---
layout: post
title: The ultimate EDA visualization in R - Raincloud plot
subtitle: Clear the obstacles in making raincloud plot
bigimg: /img/tax.png
tags: [visualization, R, raincloud]
---

This is a by-product I worked on an academic project. 

My colleague introduced a plot to me called rain cloud plot. It is a combination of dot plot, box plot and kernel density (or you could think of it as a half violin plot), which really conveys a myriad of information yet in a visually pleasant way (thus a lot of times we mistakenly call it rainbow plot :) ). A sample of the plot can be seen from the cover photo:

I have written up a post and it, fortunately get published in [Towards Data Science](https://towardsdatascience.com/the-ultimate-eda-visualization-in-r-e6aff6afe5c1). 

In the post, I mainly introduces two improvements to the default code you may find online. The first is that you may have more groups than the default color palette affords. The code will complain and the error message is not that evident ...

The second problem is more subtle in that the default setting of the plot may not generate good visulization utility if your dataset distribution is highly skewed. Thus a careful evaluation of the plottin argument should be on your rader. 

I think the post is pretty self-explanatory. And I do like raincloud plot and plan to use it more often in EDA in my future projects.


Please feel free to let me know should you have any further question related to the rain cloud plot! 

