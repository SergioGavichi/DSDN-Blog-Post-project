# Data Scientist Nanodegree - Blog Post Project

This is the supporting repository and notebook for a blog post accessible [here](http://medium.com)

## Introduction
While there is a lot of excitement about AI research results and applications, a lot of ethical, fairness or inclusiveness issues are raised.
Indeed, no matter how fair algorithms might be, if the data they are learning from is biased, we still can't trust their results.
Can we create a future of AI that works for everyone?

These are deep questions investigating the more human side of technology and covering several domains (technology, philosophy, sociology, psychology, etc.).

My humble post is an attempt to explore and raise awareness about such issues looking at a fun data set from the Google game Quick, Draw!

## Content
The Quick, Draw! data set consists of over 50 million sketches belonging to 345 different categories. It is collected through the Quick, Draw! game where players
are given 20 seconds to draw a sketch belonging to a specified category. The drawings (or doodles) are stored as vectors containing the strokes in the order they were
drawn with additional information like timestamp, category, timing.

For this post, I have selected four categories: **sandwich**, **ice cream**, **cookie** and **cake**.
Note that there is no data stored in this repository due to the size limitations.

* Quick, Draw! data set can be downloaded [here](https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/simplified)
* I have used the simplified drawing files format(`.ndjson`) described [here](https://github.com/googlecreativelab/quickdraw-dataset#simplified-drawing-files-ndjson)
* Drawings from all categories can be browsed [here](https://quickdraw.withgoogle.com/data)

The libraries used were the typical pandas, numpy and matplotlib.pyplot. I also used the plotly library and seaborn for my visualizations.

## Results
