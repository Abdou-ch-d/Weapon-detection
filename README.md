# Weapon Detection project
 
 hi and welcome to my Github repository . i offer you my project witch is about machine learning .
 So the first thing you have to knaw 
 
 
 Real time gun detection is one of the pivotal things to improve the survelliance methods. Previosuly, infrared rays were used to detect the concealed weapons which slows down the gun detection process. I used a Tensorflow-based implementation of VGGNet network to train. I used 5 types of guns to train my network: Assault Rifle, Battle Rifle, Bullpup, Pistols and Revolver.

# Preprocessing-
 In the preprocessing step, I scaled the images using standard deviation which was caculated from the sample data. Also, I zero sampled the images using the mean calculated from the sample data. These pre-processing methods were used both during the training and testing time.
 
# Database-
 I implemented a web crawler to download relevant images from the Internet Movie Firearms Database. I used around 5200 images in total for training and validation purposes in the ratio of 4:1 respectively.
 
# Results-
 The model achieved promising results having 80% as training accuracy and 78% validation accuracy.
