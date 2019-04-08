# Human-Image-Binary-Classifier

### Given a 256x256 image, write a binary classifier to differentiate the given image has a human or not

#### The images for the classifier was obtained from http://www-old.emt.tugraz.at/~pinz/data/GRAZ_01/ 
And the pixel values were stored in the python 'pickle' format
this can be viewed from : https://drive.google.com/file/d/1x6UpWiwGglvdOHXCNOgcqncFEMNjbvjZ/view?usp=sharing
#### Three different models/ approaches were used for the cassifier

1) MLP
2) CNN with less epochs
3) CNN with more number of epochs


### MLP Approach :
  All the images were reduced to 256x256 Gray scale
  and were fed through a 2 hidden layered MLP
  Optimizer used: RMS PROP
  
### CNN Approach 
  Gray scale images were fed to a conv network consisting of 3 layers with alternating pairs of conv and maxpool with conv kernel size as 16 ,32 and 64 followed  by 2 MLPs 
  

