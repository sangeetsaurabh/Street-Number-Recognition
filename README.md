# Street Number Recognition

Nowadays object recognition on images is a very challenging area. While some problems like single character recognition are easy to solve, the others like recognizing particular person in a crowd or recognizing a sequence if characters still might be difficult. Last years huge amount of open data was published which pushed progress in this area forward.


This project focused on a number recognition problem, which is basically a sequence ofsymbols. In particular, we are going to implement algorithm which will recognize house number from images. Application will take as input a bunch of images and provide a house number which is presented on each image. One of the difficulties here might be that sometimes house numbers are written in some specific order. It might be written vertical or diagonal or something else. However, at the end solid application which recognizes numbers from images with high accuracy will be presented.


In this project we will use Street View House Numbers(SVHN)[1] dataset to train our application recognize numbers on images. SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with minimal requirement on data preprocessing and formatting. The dataset is obtained from house numbers in Google Street View images. Image below represents several samples from this dataset.
