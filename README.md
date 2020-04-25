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
    <td class="tg-yw4l">Infected</td>
    <td class="tg-yw4l">4919</td>
    <td class="tg-yw4l">615</td>
    <td class="tg-yw4l">615</td>

  </tr>
  <tr>
    <td class="tg-yw4l">Normal</td>
    <td class="tg-yw4l">7081</td>
    <td class="tg-yw4l">885</td>
    <td class="tg-yw4l">885</td>
  </tr>
</table>


# Models
Access VGG16 Model [here](https://drive.google.com/file/d/1UQL71b9DtTiSLKR61ZCNNNuMFWrjMBi5/view?usp=sharing)

Access ResNet18 Model [here](https://drive.google.com/file/d/1Io_WxP4ouGCmF93oMaDLyowIs6b-DZzi/view?usp=sharing)


## Covid-19 X-rays images classification using Transfer learning
# VGG16 vs Resnet18 

![VGG16](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/Ccomparison%20vgg-resnet.PNG
)



![Resnet18]()


# Model Evalualuation 

![Result](https://github.com/Asif-Ejaz/MSDS19010_COVID19_DLSpring2020/blob/master/Results/testResults.PNG)

# Experiments Summary



# Discussion :

VGG gives more accuracy than Resnet but it requires more training time than Resnet. It is costly in terms of parameters so it provides that much high accuracy easily.
Resnet requires less training time than VGG but due to less parameters it is not able to provide that high accuracy in comparison to vgg. But setting optimal parameters like learning rate we can tune this to work better.
