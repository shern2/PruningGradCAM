This project is about analyzing what goes under the hood for pruning.

Dataset: PASCAL-VOC2012 (cat,dog,horse,person)
Image preprocessing: Resized to 128x128
Model: VGG16-variant

Model training & pruning performed on Google Colaboratory.
Pruning is performed using a corrected version of [Keras Surgeon](https://github.com/BenWhetton/keras-surgeon/).
Grad-CAM from [Keras-GradCAM](https://github.com/eclique/keras-gradcam).
Code to read PASCAL-VOC data using modified version of [pascal-voc-python]{https://github.com/mprat/pascal-voc-python}.

Dataset images and GradCAM images (incl. GIFs) can be found here: [GDrive link]{https://drive.google.com/file/d/1s5R1RCXftkhtJjjt2isPxawafVIu-GAQ/view?usp=sharing}
