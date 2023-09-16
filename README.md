# NEURAL STYLE TRANSFER


## Description

This project is based on leveraging the feature extraction layers of pre-trained models to transfer the style from one image to the content of another, showcasing the evolution of the synthesized image during the iterations, formed only by a dataset of 2 images, thanks to the ability to access networks already trained with large-volume datasets.

## Getting Started

### Dependencies

* Operating System: Windows 10 Home 64-bit - version 21H2.
* Programming Language: Python 3.11.
* IDE: PyCharm Professional 2021.3.3
* Libraries:
  * Torch v2.0.1
  * Torchvision v0.15.2
  * Matplotlib v3.7.3
  * Pillow 10.0.0

## Author
Roi Rodríguez

## Results

### ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Content‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎‎ +‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ ‎Style‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎  ‎ ‎ ‎ ‎ ‎‎ ‎  ‎  ‎  =‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Synthesized Image
<p align="left">
  <img src="TEST1/contido.jpg" width="200">
  <img src="+.jpg" width="50">
  <img src="TEST1/estilo.jpg" width="200">
  <img src="=.jpg" width="100">
  <img src="TEST1/evolution.gif" width="220">
</p>

<div style="text-align:right"><img src="TEST1/loss_TEST1.png" width="800">


### ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Content‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎‎ +‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ ‎Style‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎  ‎ ‎ ‎ ‎ ‎‎ ‎  ‎  ‎  =‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Synthesized Image
<p align="left">
  <img src="TEST2/contido.jpg" width="200">
  <img src="+.jpg" width="50">
  <img src="TEST2/estilo.jpg" width="200">
  <img src="=.jpg" width="100">
  <img src="TEST2/evolution.gif" width="220">
</p>

<div style="text-align:right"><img src="TEST2/loss_TEST2.png" width="800">


### ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Content‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎‎ +‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ ‎Style‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎‎ ‎ ‎‎ ‎  ‎  ‎  =‎ ‎ ‎ 
<p align="left">
  <img src="TEST3/contido.jpg" width="250">
  <img src="+.jpg" width="40">
  <img src="TEST3/estilo.jpg" width="270">
  <img src="=.jpg" width="60">
 
### =‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎  ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ Synthesized Image
<p align="left">
  <img src="=.jpg" width="60">
  <img src="TEST3/evolution.gif" width="300">
</p>

<div style="text-align:right"><img src="TEST3/loss_TEST3.png" width="800">

### ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Content‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎‎ +‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎ ‎ ‎ ‎ ‎ ‎Style‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎‎ ‎  ‎ ‎ ‎ ‎ ‎‎ ‎  ‎  ‎  =‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ ‎ Synthesized Image
<p align="left">
  <img src="TEST4/contido.jpg" width="180">
  <img src="+.jpg" width="50">
  <img src="TEST4/estilo.jpg" width="200">
  <img src="=.jpg" width="100">
  <img src="TEST4/evolution.gif" width="220">
</p>

<div style="text-align:right"><img src="TEST4/loss_TEST4.png" width="800">


