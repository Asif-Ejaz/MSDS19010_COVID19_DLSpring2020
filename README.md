# MSDS19010_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes.
# Dataset
Access Dataset [here](https://drive.google.com/drive/folders/1P11biqCGNk5zWqILLdNkuPtbZpvXb1ay?usp=sharing)


<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>Class</b></th>
    <th class="tg-yw4l"><b>Train</b></th>
    <th class="tg-yw4l"><b>Validation</b></th>
    <th class="tg-yw4l"><b>Test</b></th>

  </tr>
  <tr>
    <td class="tg-yw4l"><b>Infected</b></td>
    <td class="tg-yw4l">4919</td>
    <td class="tg-yw4l">615</td>
    <td class="tg-yw4l">615</td>

  </tr>
  <tr>
    <td class="tg-yw4l"><b>Normal</b></td>
    <td class="tg-yw4l">7081</td>
    <td class="tg-yw4l">885</td>
    <td class="tg-yw4l">885</td>
  </tr>
</table>


# Models
Access VGG16 Model [here](https://drive.google.com/file/d/1UQL71b9DtTiSLKR61ZCNNNuMFWrjMBi5/view?usp=sharing)

Access ResNet18 Model [here](https://drive.google.com/file/d/1Io_WxP4ouGCmF93oMaDLyowIs6b-DZzi/view?usp=sharing)


## Covid-19 X-rays images classification using Transfer learning

# Experiments Summary
### Epochs = 10 
### Learning Rate = 0.0001

<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>Model</b></th>
    <th class="tg-yw4l"><b>Parameters</b></th>
    <th class="tg-yw4l"><b>Training Time</b></th>
    <th class="tg-yw4l"><b>Train</b></th>
    <th class="tg-yw4l"><b>Validation</b></th>
    <th class="tg-yw4l"><b>Test</b></th>

  </tr>
  <tr>
    <th class="tg-yw4l"><b>VGG16</b></th>
    <th class="tg-yw4l"><b>2 FC layers</b></th>
    <th class="tg-yw4l"><b> <3 hours</b></th>
    <th class="tg-yw4l"><b> 91.33 </b></th>
    <th class="tg-yw4l"><b>91.33</b></th>
    <th class="tg-yw4l"><b>97</b></th>

  </tr>
  <tr>
    <th class="tg-yw4l"><b>ResNet18</b></th>
    <th class="tg-yw4l"><b>2 FC layers</b></th>
    <th class="tg-yw4l"><b> <1 hrs 30m </b></th>
    <th class="tg-yw4l"><b> 84 </b></th>
    <th class="tg-yw4l"><b> 84</b></th>
    <th class="tg-yw4l"><b>92</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>VGG16</b></th>
    <th class="tg-yw4l"><b> Features.28 + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <3 hours</b></th>
    <th class="tg-yw4l"><b> 88 </b></th>
    <th class="tg-yw4l"><b>89</b></th>
    <th class="tg-yw4l"><b>95</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>ResNet18</b></th>
    <th class="tg-yw4l"><b> Layer4 + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <1 hrs 30m </b></th>
    <th class="tg-yw4l"><b> 61.72 </b></th>
    <th class="tg-yw4l"><b> 61.77</b></th>
    <th class="tg-yw4l"><b>61</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>VGG16</b></th>
    <th class="tg-yw4l"><b> Features 24,26,28 + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <3 hours</b></th>
    <th class="tg-yw4l"><b> 90 </b></th>
    <th class="tg-yw4l"><b>89</b></th>
    <th class="tg-yw4l"><b>96</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>ResNet18</b></th>
    <th class="tg-yw4l"><b> Layer3,4 + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <2 hours</b></th>
    <th class="tg-yw4l"><b> 66.72 </b></th>
    <th class="tg-yw4l"><b> 67.77</b></th>
    <th class="tg-yw4l"><b>67</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>VGG16</b></th>
    <th class="tg-yw4l"><b> All Features  + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <3 hours</b></th>
    <th class="tg-yw4l"><b> 91 </b></th>
    <th class="tg-yw4l"><b>91.77</b></th>
    <th class="tg-yw4l"><b>96</b></th>
  </tr>
  
  <tr>
    <th class="tg-yw4l"><b>ResNet18</b></th>
    <th class="tg-yw4l"><b> All Blocks + 2 FC layers</b></th>
    <th class="tg-yw4l"><b> <2 hours</b></th>
    <th class="tg-yw4l"><b> 65 </b></th>
    <th class="tg-yw4l"><b> 67.77</b></th>
    <th class="tg-yw4l"><b>67</b></th>
  </tr>
  
</table>



# VGG16 vs Resnet18 

![VGG16](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/Ccomparison%20vgg-resnet.PNG
)




# Model Evalualuation 

![Result](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/testResults.PNG)




# Discussion :

VGG gives more accuracy than Resnet but it requires more training time than Resnet. It is costly in terms of parameters so it provides that much high accuracy easily.
Resnet requires less training time than VGG but due to less parameters it is not able to provide that high accuracy in comparison to vgg. But setting optimal parameters like learning rate we can tune this to work better.



# Dealing with high class imbalancement using Focal Loss

# Dataset
Access Dataset [here](https://drive.google.com/open?id=1Fc2Uyy8cMKAwbwuumwys8uZtVnkZw-Ak)

<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>Class</b></th>
    <th class="tg-yw4l"><b>Train</b></th>
    <th class="tg-yw4l"><b>Validation</b></th>

  </tr>
  <tr>
    <td class="tg-yw4l"><b>Covid-19</b></td>
    <td class="tg-yw4l">200</td>
    <td class="tg-yw4l">28</td>

  </tr>
  <tr>
    <td class="tg-yw4l"><b>Pneumonia</b></td>
    <td class="tg-yw4l">2000</td>
    <td class="tg-yw4l">200</td>
  </tr>
  <tr>
    <td class="tg-yw4l"><b>Normal</b></td>
    <td class="tg-yw4l">4000</td>
    <td class="tg-yw4l">400</td>
  </tr>
</table>

### we have 629 unlabeled testing images


# Models
Access VGG16 Model [here](https://drive.google.com/open?id=1-75GUoLsVS0_yZfiUY5RXSGMj1bEWuz3)

Access ResNet18 Model [here](https://drive.google.com/open?id=1pCPchhZu_xRVSADccRnjU8321tKwwnkn)

# Experiments and Analysis

![Result](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/focalloss.PNG)
![Result](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/focal%20loss%202.PNG)
![Result](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/focalloss3e.PNG)

