# DB16
Bird Species Classification
## Team Members
N.Bhargava Raju (19471A05N3)
Ch.Shanmukha Chakravarthy (19471A05K6)
D.Balaji (19471A05K9)
## ABSTRACT
Nowadays, Birdwatching is a common hobby but to identify their species requires the
assistance of bird books. To provide birdwatchers a handy tool to admire the beauty of birds, we
developed a deep learning platform to assist users in recognizing 27 species of birds endemic to Taiwan
using a mobile app named the Internet of Birds (IoB). Bird images were learned by a convolutional
neural network (CNN) to localize prominent features in the images. First, we established and generated
a bounded region of interest to refine the shapes and colors of the object granularities and subsequently
balanced the distribution of bird species. Then, a skip connection method was used to linearly combine
the outputs of the previous and current layers to improve feature extraction.
Finally, we applied the softmax function to obtain a probability distribution of bird
features. The learned parameters of bird features were used to identify pictures uploaded by mobile
users. The proposed CNN model with skip connections achieved higher accuracy of 99.00 % compared
with the 93.98% from a CNN and 89.00% from the SVM for the training images. As for the test
dataset, the average sensitivity, specificity, and accuracy were 93.79%, 96.11%, and 95.37%,
respectively
