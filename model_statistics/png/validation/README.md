
| Light blue: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate| Navy blue: Original convolutional neural network, 3e-4 learning rate| Orange: LeakyReLU, 3e-4 learning rate | Brown: LeakyReLU, no dropout, 3e-4 learning rate |  Gray: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate |
|----------------|------------------|----------------|------------------|------------------|

<img src="https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_rmse_val_top5.png" width="1500" height="400">
*Epoch RMSE validation top 5*

| Colour |Min validation epoch root mean square error | Max validation epoch root mean square error |
|----------------|----------------|----------------|
| Light blue          |  0.3820      |0.7070  |
| Navy blue         | 0.3708        |0.4775|
| Orange           |   0.3715      |0.4525|
| Brown      |   0.3794       |0.4514 |
| Gray          |  0.3818      |0.4600|

<img src="https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_loss_val_top5.png" width="1500" height="400">
*Epoch loss validation top 5*

| Colour | Min validation epoch loss | Max validation epoch loss |
|----------------|----------------|----------------|
| Light blue          |  0.1459       |0.4999  |
| Navy blue         |  0.1375       | 0.2280|
| Orange           |  0.1380      |0.2048|
| Brown      |   0.1439       |0.2037 |
| Gray          |    0.1458      |0.2116|

| Colour | Convergence time |
|------------------|------------------|
|Light blue| 4h 02m 39s       |
|Navy blue| 3h 44m 37s       |
|Orange| 3h 08m 20s       |
|Brown| 2h 45m 43s       |
|Gray| 3h 21m 49s       |
