# 596 Final Project
Final Project for CSCI 596 Scientific Computing and Visualization

Our project aims to visualize ResNet and ViT layers to help understand how they work.

# Problem
ResNet and ViT analysis are deep learning algorithms used to identify and classify images.
However, it can be difficult to determine what the deep learning algorithm is actually doing.

# Methods
ResNet and ViT both work by feeding data through layers of nodes which calculate the result.
By performing feature extraction, we can represent Resnet's layers as feature maps and ViT's layers as attention maps.
Visualizing ResNet's feature maps and ViT's attention maps as heat maps can help us understand how the deep learning algorithms works.
ResNet processes images through layers of convolution filters. Each layer extracts patterns like edges, textures, and shapes. 
It uses shortcut connections to skip one or more layers, enabling the network to learn residual mappings rather than direct transformations. 
This architecture is excellent for tasks like image classification because it processes images locally, focusing on spatial hierarchies.

ViTs adopt a fundamentally different approach. They divide an image into fixed-size patches and process them as a sequence, like words in a sentence. 
Each patch is embedded into a feature vector, and self-attention layers enable the model to capture global relationships across the entire image. 
ResNet builds patterns hierarchically, layer by layer, focusing on local details first. In contrast, ViT captures relationships across the entire image from the start, allowing it to understand the global context. 

# Results
We made a simple tool with several options to analyze and visualize feature maps and attention maps.
Using this tool, we can turn a selected feature map and attention map into heat maps overlaid on top of each other and the original image.

This visualizes where the feature map and attention map are looking which can help use understand how each algorithm works.
