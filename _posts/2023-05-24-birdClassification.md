# Bird Classification Example

Reading this has shown me that it is much more simpler to use deep learning to recognise a bird than I had originally thought. However, when trying to run the example code I ran into many issues. First was that I was unable to run the code in the kaggle environment. After, I then created a Jupyter Notebook using Anaconda and I was able to import and use libraries necessary. However I ran into another issue where I was unable to use duckduckgo_search. This was fixed after adjusting the code. Now that it is working I am much more confident in applying deep learning to recognise birds!

The Duck Duck Go scraper is really interesting and seems quite effective at getting images. However, I did notice that there was some quality issues with the images:

![image](https://github.com/Benjamin-Guy/Benjamin-Guy.github.io/assets/132412391/117bda93-2361-4634-8b0d-ef4fc6f297de)

Some of the bird images were not actually of birds but of some objects with bird artwork/painting on it. And a forest image did not look anything like a forest! This suggests that I need to work out how to phrase my search term when using Duck Duck Go to get better image results. Despite this, the model was able to be trained very easily and achieved a good error rate:

![image](https://github.com/Benjamin-Guy/Benjamin-Guy.github.io/assets/132412391/f81e948c-6f57-43a8-ad81-2bca7bfba266)

Overall, this example was great to learn from and it will form the foundation to build upon for creating a classification model for ten different animals. I will have to learn about various model evaluation methods such as confusion matrices and t-SNE.
