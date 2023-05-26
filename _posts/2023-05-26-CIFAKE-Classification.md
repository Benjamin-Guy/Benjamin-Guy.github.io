# CIFAKE Classification Dataset

I was able to download the CIFAKE dataset, which consists of 60,000 real images and 60,000 AI-generated images. The task was to create a deep neural network model that could accurately classify an image as either real or AI-generated. This task was very research-focuses and new so it was quite exciting to be able to work on a relevant and current problem.

My approach to this problem was similar to the multiclass-classification of the ten animals that I had done prior. I would use two classification labels of real or fake on each of the images. Then train a model on these labels and hope for a good classification accuracy. The optimal accuracy was stated to be 92.98% in the research paper containing the CIFAKE dataset. My first attempt was able to achieve 96.745% classification accuracy which was quite impressive. I decided to further improve by using a more complex model architecture (RESNET152 as opposed to RESNET18) and was able to increase the classification accuracy to 97.865%. I was very pleased with achieving this classification accuracy. Here was the confusion matrix for this model's predicted labels verse the actual labels:

![image](https://github.com/Benjamin-Guy/Benjamin-Guy.github.io/assets/132412391/01c0b564-d616-4936-964a-a03bb8a75075)
