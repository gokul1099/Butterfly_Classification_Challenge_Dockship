## Butterfly Classification AI Challenge
## The aim of this challenge is to classify given images into 50 categories of butterflies.

link to challenge : https://dockship.io/challenges/5f7418d6fbaa7b0393ff1a05/butterfly-classification-ai-challenge/overview


This is an AI challenge by Doship where we have to train a deep learning model to classify 50 categories of butterfly. This is an image classification with small dataset which has about maximum of 120 image per class and minimum of 60. 
# Frist aproach
Here i used transfer learning for traning the model. Here I used Resnet50v2 and got an test accuracy of 81.2

# second approach

Here i trained two pre trained model namely Xception and Resnet101v2 both has training accuracy of 83 and 86 respectively. I sum up the prediction probabilities of both model and applied argmax on the final result. So the test accuracy increased from 81.2 to 89.400

# Final approach
