# Implementation of modified U-Net: Convolutional Networks for Biomedical Image Segmentation in TF 2.0 keras API.
![](https://github.com/minoring/unet/blob/master/misc//u-net-architecture.png)

## Results
Initial predict          |  Training process
:-------------------------:|:-------------------------:
![](https://github.com/minoring/unet/blob/master/samples/predict_image_0.jpg)  |  ![](https://github.com/minoring/unet/blob/master/samples/unet.gif)


## Usage example
```
python main.py \
    --train_path=data/membrane/train\
    --batch_size=2 \
    --epoch=50 \
    --steps_per_epoch=300 \
```

## References
### paper
- https://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/

### blogs
Those are nicely explained material to understand sementic segmentation and convolution operation.

- Understanding Semantic Segmentation with UNET
https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47
- Up-sampling with transposed convolution https://medium.com/activating-robotic-minds/up-sampling-with-transposed-convolution-9ae4f2df52d0


### code
Implementation of deep learning framework -- Unet, using Keras https://github.com/zhixuhao/unet

## Model Architecture
![](https://github.com/minoring/unet/blob/master/misc/model.png)
