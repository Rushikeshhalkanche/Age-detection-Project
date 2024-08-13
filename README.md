# Age-detection-Project

##Description-
Automatic age classification has become relevant to an increasing amount of applications, particularly since the rise of social platforms and social media. Nevertheless, performance of existing methods on real-world images is still significantly lacking, especially when compared to the tremendous leaps in performance recently reported for the related task of face recognition. In this project I showed that by learning representations through the use of deep convolutional neural networks (CNN), a significant increase in performance can be obtained on these tasks. To this end, I used a simple convolutional net architecture that can be used even when the amount of learning data is limited. I evaluated my model on the recent UTKFace dataset for age estimation and show how it dramatically outperforms current state-of-the-art methods.

###Dataset used-
I have used a dataset called downsampled. downsampled dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. This dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance.

The labels of each face image is embedded in the file name, formated like [age][gender][date&time].jpg

--> [age] is an integer from 0 to 116, indicating the age

https://miro.medium.com/v2/resize:fit:1024/0*mlkFwDiAsSmV2o8i.jpg
