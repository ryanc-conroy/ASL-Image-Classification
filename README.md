# ASL-Image-Classification


Motivation:

American Sign Language (ASL) is the leading minority language in the United States (following Spanish, Italian, German, and French), so having a visual recognition model that can recognise these hand signals could help the deaf/hard of hearing to better communicate using computer vision applications. The dataset is also an MNIST image dataset which we can use to create a model that can identify the ASL letters of the alphabet (excluding ‘J’ and ‘Z’, which include motion with their sign). We will look to compare the results of a tree classifier with a PCA vs deep learning such as CNN, RNN, and neural networks with RBM applied.
  
Data: 

The American Sign Language letter database can be found at (https://www.kaggle.com/datamunge/sign-language-mnist). The data includes images of American Sign Language letters and class labels. The images are 27 x 27 pixel images with grayscale values between 0-225. The dataset features around 35,000 images. The images are classified into 26 categories, one for each letter of the alphabet (A=0, B=1...Z=25). The letters J=9 and Z=25, have zero instances as they are motion based symbols. The images feature different hands performing American Sign Language letters against different backgrounds.

