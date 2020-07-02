# __Toy example of a two-arm ConvNet and diagnostics using gradCAM__

In order to diminish the influence of colour on its classification accuracy, a small ConvNet will be endowed with a second arm in which the RGB-channels have been collapsed by means of 1x1 convolutions. 
Both arms will then be merged together for classification.
Finally, the individual contribution of the two arms will be assessed with the help of [__GradCAM__](https://arxiv.org/abs/1610.02391) . 
