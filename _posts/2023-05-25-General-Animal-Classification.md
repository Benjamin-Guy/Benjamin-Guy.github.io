# Creating a Neural Network Model for Classifying Ten Different Animals

Today I applied the knowledge and skills I learnt from the bird classification model and created a new multiclass classification model for ten different animals. This task was relatively straightforward as the foundational steps taken to scrape the images, train the model, and make predictions was very similar to the bird classification model task. I was able to apply some of my prior understanding of neural networks to explain the layers and architecture of the model used. However, the evaluation of the model was something I needed to learn.

It was difficult to find resources online on what t-SNE is and how to use it, but I eventually found a resource that showed a simple implementation of t-SNE and applied it to my own model. This produced a very interesting visualisation:

![image](https://github.com/Benjamin-Guy/Benjamin-Guy.github.io/assets/132412391/aba2c129-3ea6-4bfe-8cac-78be69093057)

Seeing each cluster and the colour coding of the classifications is a very effective way of visualising the high dimensional data.

The confusion matrix was also very interesting as it gave a more exact evaluation than the t-SNE visualisation:

![image](https://github.com/Benjamin-Guy/Benjamin-Guy.github.io/assets/132412391/9d91d62d-88f2-45a2-a3a3-8aab6a665e2d)
