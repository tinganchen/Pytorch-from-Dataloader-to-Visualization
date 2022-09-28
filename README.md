# Pytorch-from-Dataloader-to-Visualization
Complete workflow for image classification in Pytorch.

## What to learn in this repository?

1. Import dataset and load it as batches
2. CNN model
3. Training, testing and save the model
4. Load model weights and predict
5. Visualize filter weights and feature maps in each layer
6. Save feature maps and input image

## Requirements
- 32 GB RAM
- RTX 2080 GPU
- torch 1.2.0
- torchvision 0.2.1
- json 0.8.4
- matplotlib 3.1.0
- numpy 1.16.4

## Dataset
MNIST - Image classification, 1x28x28 px.

## Model
- Conv2d * 2 + RELU
- Maxpool2d * 2
- Fully connected layer * 2

## Training
Trained in 3 epochs with 128 batch size and the training accuracy is 0.9827. 

## Testing
The testing accuracy is 0.9854.

## Visualization
Trained filters and the output feature maps each layer are plotted to see in the black box.

## Reference
The model is referred to >> https://xmfbit.github.io/2017/03/04/pytorch-mnist-example/. 
