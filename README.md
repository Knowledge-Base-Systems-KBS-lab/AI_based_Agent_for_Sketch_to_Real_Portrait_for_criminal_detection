# AI_based_Agent_for_Sketch_to_Real_Portrait_for_criminal_detection

# By Zain Ul Abedien & Abdullah Rafique

Advisor 
Dr Rabia Irfan

Purpose:

An robust and digital probable solution designed for converting sketches to real images.


![architecture](https://user-images.githubusercontent.com/20832374/155968399-663a523d-0db0-47e2-88b3-3d5600a05012.png)


Working of Sketch to Real Portrait For criminal detection

https://user-images.githubusercontent.com/20832374/155974510-82817cac-7d19-40ad-83fe-ffa1261d2671.mp4

# Motivation:

It is becoming increasingly difficult in forensic departments to catch the suspect, due to diversity in skin colors, facial outfits, and the range of other reasons. The process of actually going out to catch the suspect from the sketch being drawn by forensics is a very long and tiring process and often results in no one catched at all. So we are envisioning to create a system, that with the help of input sketch and the color mask will try to predict the original person’s face from the information given. Having a probable estimation of face, we can use that to search the government databases, and using latest tools to narrow down the search.

# Approach:

By training state of the art Generative Adversarial Networks in an end to end fashion can help us generate the results for our scenario. In the start we had two limitations.

How to input both sketch and color mask to the model, and do inference based on the both inputs.
How to create the dataset.


![image](https://user-images.githubusercontent.com/20832374/155975318-fa0a65d1-ecfb-4125-a460-c82383ce1d32.png)


# DataSets

Anime:
Anime faces of getchu
Human:
CelebA

# Preprocessing:

Edges:

 Edges are treated as the content of an image in our method. 
 
Color domain:

 Color domain corresponding to the style features is extracted in an explicit way. We apply a median filter algorithm followed by K-means algorithm to obtain the average color domain
 
 
 # Work Flow
 
 ![image](https://user-images.githubusercontent.com/20832374/155975874-03f7574f-57b8-4f6d-af64-79cd2ff5c060.png)

 
 # Architecture
 
 ![image](https://user-images.githubusercontent.com/20832374/155975913-a2be46c7-1d8e-42a4-b3bf-f96b946211f7.png)

 
 
 # Results
 
 ![image](https://user-images.githubusercontent.com/20832374/155975650-81656726-489f-41c6-9074-d62e52070187.png)


# Concluion:
We propose a novel universal image reconstruction architecture, where the progressive strategy used endows our model SRPCI with the ability of reconstructing high-fidelity images from sparse inputs.
 We improve the controllability and interpretability by using flat color domain as explicit style input instead of extracting latent style vector frequently used in I2I translation. 
This model architecture can be apply to every object dataset.
We have built this on edge level devices by extremely focus on model size and its memory requirements.


# Refrences

1. https://arxiv.org/pdf/1903.10146.pdf
2. Y. Choi, M. Choi, M. Kim, J.-W. Ha, S. Kim, and J. Choo. Stargan: Unified generative adversarial networks for multidomain image-to-image translation. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, pages 8789–8797, 2018. 3
3. Y. Cao, H. Wang, C. Wang, Z. Li, L. Zhang, and L. Zhang. Mindfinder: interactive sketch-based image search on millions of images. In Proceedings of the 18th ACM international conference on Multimedia, pages 1605–1608. ACM, 2010. 3
4. [I. Goodfellow, J. Pouget-Abadie, M. Mirza, B. Xu, D. Warde-Farley, S. Ozair, A. Courville, and Y. Bengio. Generative adversarial nets. In Advances in neural information processing systems, pages 2672–2680, 2014



