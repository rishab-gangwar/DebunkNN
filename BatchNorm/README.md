# Advantage of Having Batch Normalization Layer
>This part of repo explores the effect of batch normalization on training Neural Nets.
>>* We have taken two different NN with only diiference in the presence of Batch Normalization in one.<br>
>>* We have also plotted the change in distribution of data.<br>
>>   1. It can be seen that the `NN without BN` layer fluctuates the Input distribution very drastically.<br>
>>   2. However,the `NN with BatchNorm` conversely,stabilizes the distribution just after 1st epoch<br>
>>* The NN without BN is unable to train itself and the loss curve seems to get flattened but other NN continues to train even after 20th epoch.<br>

|**`NN without BN`**|**`NN with BatchNorm`**|
|:------:|:------------------:|
|![GitHub Logo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/Mynet.png)|![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/My.png)|
|  Input Data distribution  |![GitHub Logo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/initDist.png) |
|Loss plot after first epoch  |![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/1epochLoss.png)|
|Loss plot after second epoch |![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/2epochLoss.png)|
|Loss plot after fifth epoch  |![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/5epochLoss.png)|
|Loss plot after tenth epoch  |![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/10epochLoss.png)|
|Loss plot after twentieth epoch|![oo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/20epochLoss.png)|
| Final distribution  |![GitHub Logo](https://github.com/rishab-gangwar/nn_from_scratch/blob/master/BatchNorm/Finaldist.png) |
