
| Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate| Orange: Original convolutional neural network, 3e-4 learning rate| Gray: LeakyReLU, 3e-4 learning rate | Navy blue: LeakyReLU, no dropout, 3e-4 learning rate |  Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate |
|----------------|------------------|----------------|------------------|------------------|

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/epoch/epoch_rmse_train_top5.png)
*Epoch RMSE train top 5*

| Colour | Min train epoch root mean square error | Max train epoch value mean square error |
|----------------|----------------|----------------|
| Brown          |  0.3561        |0.6218  |
| Orange         |  0.3790        | 0.6140|
| Gray           |   0.3819      |0.5684|
| Navy blue      |   0.3574       |0.5174 |
| Green          |  0.3669       |0.5252|

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/epoch/epoch_loss_train_top5.png)
*Epoch loss train top 5*

| Colour | Min train epoch loss | Max train epoch loss |
|----------------|----------------|----------------|
| Brown          |  0.1268       |0.6968  |
| Orange         |  0.1436       | 1.1398|
| Gray           |   0.1459       |0.8799|
| Navy blue      |   0.1277       |0.6591 |
| Green          |    0.1346       |0.7393|

| Colour | Convergence time |
|------------------|------------------|
|Brown| 4h 02m 39s       |
|Orange| 3h 44m 37s       |
|Gray| 3h 08m 20s       |
|Navy blue| 2h 45m 43s       |
|Green| 3h 21m 49s       |
