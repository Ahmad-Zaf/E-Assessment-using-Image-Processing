# E-Assessment-using-Image-Processing

INTRODUCTION --

With the increasing demand for accurate and reliable identity authentication in modern society, 
traditional authentication methods such as passwords and magnetic cards are far from meeting 
the needs of society because they can be easily stolen and forged. Meanwhile, biometric 
identifiers (such as fingerprints, faces and iris patterns) are characterised by their uniqueness 
and stability, making biometric recognition technology more important in the identity 
authentication field. Unlike most biometric identifiers present on the body's surface, the finger 
veins are beneath the human skin, which makes them difficult to steal or be worn. Most 
importantly, finger vein verification has the unique characteristic of live-body detection, which 
ensures the advantages of finger vein technology and attracts more attentions into this area. 
Generally, a finger vein verification system consists of four parts: image acquisition, image 
preprocessing, feature extraction and matching, of which feature extraction is the most 
important step. With discriminative image features, the overall performance of the system can 
be significantly improved. According to the different feature extraction methods, they can be 
divided into three categories: finger vein pattern-based methods, finger vein texturebased 
methods and minutiae-based methods.


Objectives:-  

Constructing the Siamese network with MC loss learning can achieve the goal of finger 
vein verification which requires that the deep features extracted from the sample pairs 
maintain a closer distance for genuine pairs but a further distance for imposter pairs. facing 
the issue of insufficient training data, they adopt a heavy image augmentation strategy and 
develop a pretrained-weights based convolutional neural network (CNN). Second, focusing 
on the characteristics of finger vein verification, they construct a Siamese structure 
combining with a modified contrastive loss function for training the above CNN, which 
effectively improves the network's performance. Finally, considering the feasibility of 
deploying the above CNN on embedded devices, they construct a lightweight CNN with 
depthwise separable convolution and adopt a knowledge distillation method to learn the 
knowledge from the pretrained-weights based CNN, which makes it small but effective.
