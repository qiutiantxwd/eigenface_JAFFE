# Computing eigenfaces from scratch in Python
Image analysis with PCA has been widely used over past 30 years.  
The fisrt article describing such idea was in 1991 by Turk and Pentland. [CVPR paper](https://sites.cs.ucsb.edu/~mturk/Papers/mturk-CVPR91.pdf)
, [Journal paper](https://www.face-rec.org/algorithms/PCA/jcn.pdf)  
They proposed a PCA-based face recognition algorithm. The method of applying PCA on an image was described in detail.  
In this notebook, I follow their description and compute eigenfaces on another widely used dataset, Japanese Female Facial Expression Dataset (JAFFE).  
## Data
Data can be downloaded from [Kaggle](https://www.kaggle.com/andrewmvd/japanese-female-facial-expression-dataset-jaffe).  
images/ contains all the face images, data.csv contains information on each image, such as person ID, and the expression. 
