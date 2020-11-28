# Weapon Detection project
 
 Hi and welcome to my Github repository . i offer you my project witch is about machine learning  .

 
 
 Real time weapon detection is one of the pivotal things to improve the survelliance methods. Previosuly, infrared rays were used to detect the concealed weapons which slows down the weapon detection process. I used a Tensorflow-based implementation of VGG-16 network & YOLOv3 to train. I used 3 types of weapons to train my network:  Rifle , Knife , Handgun.

# Preprocessing-
 In the preprocessing step, I scaled the images using standard deviation which was caculated from the sample data. Also, I zero sampled the images using the mean calculated from the sample data. These pre-processing methods were used both during the training and testing time.
 
# Database-
 I implemented a web crawler to download relevant images from the Internet Movie Firearms Database. I used around 60000 images in total for training and validation purposes in the ratio of 4:1 respectively.
 
# Results-
 The model achieved promising results having 80% as training accuracy and 85% validation accuracy.
check out the link below to see more results:
https://drive.google.com/drive/folders/1e4KpsYIscDFb5GLiyU9TAKFZBkx_yoz8?usp=sharing


