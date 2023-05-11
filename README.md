# Georgian Alphabet: Image Recognition & Trainers

The project collects the image dataset of Georgian printed letters and recognizes them using CV and CNN from keras and tensorflow. Also there are trainers for learning letters and numerals.

Libraries: cv2, keras, tensorflow, pandas, numpy, re, xml.etree.ElementTree, glob, os, shutil, google.colab, opendatasets, collections, matplotlib, BeautifulSoup4


## Table of contents
- [Dataset](#dataset)
- [Machine Learning problems](#machine-learning-problems)
- [Trainers](#trainers)



## Dataset

- The image dataset of Georgian signboards was created by myself during my living in Georgia. More than 4000 letters on these images were labeled with [makesense.ai](https://www.makesense.ai/). The result dataset was uploaded on [Kaggle](https://www.kaggle.com/datasets/alexandertropin/georgian-letters-photo-database). 

- The data about [Georgian alphabet](https://github.com/am-tropin/georgian-letters/blob/main/modern_georgian_alphabet.png) and frequency of letter occurence was scraped from Wikipedia. The [georgian_labels.txt](https://github.com/am-tropin/georgian-letters/blob/main/georgian_labels.txt) file is used for labeling. 


## Machine Learning problems

- The first problem is **Image Processing**. I created a new dataset of cropped images of singular letters in common design (32x32, black letter on the white background). The received dataset (~20MB) was saved as [cropped_images.zip](https://github.com/am-tropin/georgian-letters/blob/main/cropped_images.zip) archive.

- The second problem is **Image Classification**. I built the **CNN model** based on images of 7 most frequent occurring letters using **keras** and **tensorflow** and get the **accuracy of 99%**. All the samples of some of top-7 letters from external image were **classified correctly**. The code is in [Georgian_letters_recognition_TF.ipynb](https://github.com/am-tropin/georgian-letters/blob/main/Georgian_letters_recognition_TF.ipynb) file.


## Trainers 
### (in progress)

- The first trainer is **Letter Memorization**. It realizes the memorization technique of sequential replacement of letters in Russian or English texts. 

- The second trainer is **Numerals Constructor**. It generates a Georgian transcription of numerals by any number between 0 and 1 million. 




