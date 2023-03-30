# Birds classification

For training this model was used dataset from Kaggle. This datase includes images of 510 species of birds: 80,085 training images, 2500 test images(5 images per species) and 2500 validation images(5 images per species). All images are 224 X 224 X 3 color images in jpg format. 

While exploaring data, I found out that all sciesies have at least 130 images in train folder, I think it should be enough to train a model. 

For classification I used pretrained model ResNet50. I trained if on given data and reached accuracy 0.9835 on test data.
 <img width="683" alt="Снимок экрана 2023-03-30 в 17 26 05" src="https://user-images.githubusercontent.com/111921768/228886119-aa938f8e-e3fe-4bd5-ba97-3c7144a5557d.png">
