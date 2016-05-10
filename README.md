# SceneClassificationOpenCV
Scene Classification algorithm I built at Data Science Retreat. Classifiys images into night, sunny/bright, rainy/dull and snowy images. 
The algorithm has several parts that create feature vectors based on existence/levels of haze in an image, color channel distribution present in the sky, and contrast distribution. These feature vectors are then combined and used to train several binary Random Forest classifiers [Night or not, Snowy or not etc].
