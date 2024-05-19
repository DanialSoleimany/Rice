# Rice Varieties Classification Using Convolutional Neural Networks (CNN) and AlexNet

## How are Convolutional Neural Networks (CNN) and AlexNet used in classifying rice varieties?
This work uses Convolutional Neural Networks (CNN) to classify five different rice varieties based on their images. By analyzing 75,000 grain images, the CNN model achieved a 99% and AlexNet model achieved a 95% success rate in distinguishing between the varieties.

## Connect with Me
[Kaggle](https://www.kaggle.com/dankok)  
[LinkedIn](https://www.linkedin.com/in/danial-soleimany-30abb4220/)  
[GitHub](https://github.com/DanialSoleimany)  

## Table of Contents
<div style="border: 3px solid none; background-color:#FBFFED;padding:20px;">
  <a href="#conf" style="text-decoration: none"><button class="button">Step 1 | Configuration & Libraries</button></a>
  <a href="#load-data" style="text-decoration: none"><button class="button">Step 2 | Load Dataset</button></a>
  <a href="#dataset-overview" style="text-decoration: none"><button class="button">Step 3 | Dataset Overview</button></a>
  <a href="#prepare" style="text-decoration: none"><button class="button">Step 4 | Prepare Data</button></a>
  <a href="#integrate" style="text-decoration: none"><button class="button">Step 4.1 | Integrate Data</button></a>
  <a href="#split" style="text-decoration: none"><button class="button">Step 4.2 | Splitting Data</button></a>
  <a href="#gen-norm" style="text-decoration: none"><button class="button">Step 4.3 | Data Generator & Normalization</button></a>
  <a href="#modeling" style="text-decoration: none"><button class="button">Step 5 | Modeling</button></a>
  <a href="#cnn" style="text-decoration: none"><button class="button">Step 5.1 | CNN</button></a>
  <a href="#alexnet" style="text-decoration: none"><button class="button">Step 5.2 | AlexNet</button></a>
  <a href="#evaluation" style="text-decoration: none"><button class="button">Step 6 | Evaluation Of Models</button></a>
  <a href="#best-model" style="text-decoration: none"><button class="button">Step 7 | Best Model's Performance</button></a>
  <a href="#future" style="text-decoration: none"><button class="button">Future Works</button></a>
</div>

## What are the different varieties of rice used in this work?
Rice, which is among the most widely produced grain products worldwide, has many genetic varieties. These varieties are separated from each other due to some of their features, such as texture, shape, and color. In this work, five different varieties of rice often grown in Turkey were used: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.

## How many grain images were included in the dataset?
A total of 75,000 grain images were included in the dataset, with 15,000 images from each of the five rice varieties: Arborio, Basmati, Ipsala, Jasmine, and Karacadag.

## Future Work
We can explore improving the performance of CNN and AlexNet models by experimenting with different optimizers such as RMSprop and Adagrad. Additionally, trying alternative CNN architectures like VGGNet and ResNet can help determine if they yield better results in classifying various types of rice images. Increasing the number of epochs and adjusting other hyperparameters are also avenues worth exploring to assess their impact on performance.
