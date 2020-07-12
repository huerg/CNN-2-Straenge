# __Toy example of a two-arm ConvNet and diagnostics using gradCAM__

In order to diminish the influence of colour on its classification accuracy, a small ConvNet will be endowed with a second arm in which the RGB-channels have been collapsed by means of 1x1 convolutions. 
Both arms will then be merged together for classification.
Finally, the individual contribution of the two arms will be assessed with the help of [__GradCAM__](https://arxiv.org/abs/1610.02391) . 
For this purpose the activation heatmaps will be compared, in order to find out whether the arm without different colour channels shows different activation areas.

## __Results__
Even though the quality of the activations of the grayscale (collapsed) arm is low, both pictures show clearly different activation intensities and patterns.


