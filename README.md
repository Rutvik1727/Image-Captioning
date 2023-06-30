# Image Captioning with CNN and RNN
This project focuses on generating descriptive captions for images using a combination of Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs). The model leverages the power of deep learning techniques to understand the content of images and generate human-like captions.

## Model Architecture
1. **CNN Model:** A CNN model is utilized to extract relevant features from the input images.

2. **RNN Model:** An RNN model is employed to generate captions based on the image features extracted by the CNN.

## Example
**Input Image**
![](https://github.com/Rutvik1727/Image-Captioning/blob/main/Images/img%20(1).png)
**Generated captions**
```
['<SOS>', 'a', 'brown', 'and', 'white', 'dog', 'with', 'a', 'ball', 'on', 'some', 'grass', '.', '<EOS>', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.', '.']
```

## Graphs

### Loss
![](https://github.com/Rutvik1727/Image-Captioning/blob/main/Images/plt%20(1).png)

### Perplexity
![](https://github.com/Rutvik1727/Image-Captioning/blob/main/Images/plt%20(2).png)

## Results
> Obtained a Perplexity of 17%