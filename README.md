# ToonLyt | The Pastiche Creator

## About: 
ToonLyt | An Android application that helps you create pastiches and cartoonised images. Pastiche - is nothing but an artistic work in a style that imitates that of another work or an artist. There are over 15+ style images available in this applciation. It is available for all **Android Phones above** *Android 8.0 - Oreo*.  
## Download for Android
Download the ToonLyt APK from the  [latest release](https://github.com/sairpa/ToonLytV2/releases).

## Intro:
It uses one of the Machine Learning Techniques - *Neural Style Transfer* for Pastiche Creation. This works by selecting a Style image and Source Image, extracting these features separately and rendering them into a single stylized image. 

## Features:
- Has 15+ Style Images
- Save / Share Stylised Images
- Has a CPU/GPU switch for controlling time
- Has a Re Run Button to increase convenience 

## A glimpse of what's inside:

![App](/Images/ToonLyt.jpg)

### Process: Pastiche Creation
![Input -> Output](/Images/Process.png)

## Resources used:

*   [TensorFlow Lite](https://www.tensorflow.org/lite)
*   [Style Transfer model for mobile](https://www.tensorflow.org/lite/models/style_transfer/overview)
*   [Train the style transfer model and export to TensorFlow Lite](https://github.com/tensorflow/magenta/tree/master/magenta/models/arbitrary_image_stylization#train-a-model-on-a-large-dataset-with-data-augmentation-to-run-on-mobile)
*   [Neural Style Transfer with TensorFlow](https://www.tensorflow.org/tutorials/generative/style_transfer)
*   [CameraX](https://developer.android.com/training/camerax)
*   [TensorFlow Lite Neural Style Transfer Android App](https://github.com/tensorflow/examples/tree/master/lite/examples/style_transfer/android)
