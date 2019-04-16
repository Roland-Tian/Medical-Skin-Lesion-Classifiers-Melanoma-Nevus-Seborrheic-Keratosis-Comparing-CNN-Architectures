#### Skin Lesion Classifiers for Melanoma, Nevus, or Seborrheic Keratosis comparing SENet-154, SE-ResNext-101, Inception-ResNetV2 and NASNet Convolutional Neural Networks with Transfer Learning (only last linear layers trained)

Cross entropy loss, and Adam optimizer with default learning rate used for all models.

#### Overall test set accuracy (random guessing would be expected to yield ~33% accuracy):
- SENet-154:           
64%
- SE-ResNext-101:      
61%
- Inception-ResNetV2:  
56%
- NASNet Large:        
57%

SENet-154 appeared to generalize the best. 

SE-ResNext-101 reduced training error the most, but did not generalize as well. 

Inception-ResNetV2 generalized the worst. 

NASNet Large was the most resource intensive and took the longest to train. 
