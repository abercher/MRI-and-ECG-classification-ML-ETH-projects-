# MRI-and-ECG-classification-ML-ETH-projects-
This repository contains the final notebooks I created for the second projects of the course Machine Learning given by Pr. Buhman from ETH, in fall 2017. The aim was to classify some MRI images. It was my first project in data science, and the first time I used Python. I learned a lot but it is far from being an example to follow.

There were two main difficulties:
1) The big dimensions of the data (each image had more than 6 MIO entries)
2) The labels were not given under the form of a number indicating to which of the four categories the associated image belonged but as a vector of probabilities of belonging to each one of the categories.

On a theoretical ground, the most important lesson I gained from this, is the importance of data exploration, and in particular data visualization, because it helps processing the data in a way which makes it easier to analyze. In this specific case, taking only slices (selected carefully) of the MRI greatly reduced the dimension (and the noise I guess).

The most efficient algorithm was Random Forest.
