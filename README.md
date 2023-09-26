# Plant-Disease-Detector-Prototype



Plant diseases significantly impact global food security and the world's agricultural economy. Early detection and classification increase the chances of setting up effective control measures, which is why the search for automatic systems that allow this is of major interest to our society. 
In this project, we will build a prototype plant disease classifier using the Pytorch-wrapped library Fastai with Deep Learning architecture Residual Network (ResNet) to identify the diseases based on user-uploaded leave images. 
The dataset we use is the [Plant Village Dataset](https://github.com/spMohanty/PlantVillage-Dataset), which contains 162916 images across 14 different species, including 14 crop species: Apple, Blueberry, Cherry, Grape, Orange, Peach, Bell Pepper, Potato, Raspberry, Soybean, Squash, Strawberry, and Tomato.
We split the dataset into 80% training and 20% validation sets. The classifier reached 99.38% accuracy eventually. 


This project has everything of application setup; you can even click the GUI to upload the leaves images while running the notebook. Due to the size limitation, the export model will be considered to be placed in another repository. Here, we can use Voila, widget, and Binder to create a mini-application(guidance in another respository), while the more sophisticated deployment using Paperspace/container is coming soon (in another depository).

- Choice of Application: [Binder](https://mybinder.org/)
- Choice of GPU: Nvidia 8 core A6000 with 45 Gib RAM and 48 Gib GPU
  
