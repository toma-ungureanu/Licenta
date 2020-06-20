| Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate | Orange: Original convolutional neural network, 3e-4 learning rate |  Gray: LeakyReLU, 3e-4 learning rate |  Navy blue: LeakyReLU, no dropout, 3e-4 learning rate | Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate|
|---------------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------|------------

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/batch/batch_rmse_top5.png)
*Batch RMSE train top 5*

| Min batch root mean square error | Max batch value mean square error |
|----------------------------------|-----------------------------------|
| 0.3561                           | 0.8347                            |
| 0.3790                           | 1.067                             |
| 0.3819                           | 0.938                             |
| 0.3574                           | 0.8119                            |
| 0.3669                           | 0.8598                            |

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/batch/batch_loss_top5.png)
*Batch loss train top 5*

| Min batch loss | Max batch loss |
|----------------|----------------|
| 0.1268         | 0.6968         |
| 0.1436         | 1.1398         |
| 0.1459         | 0.8799         |
| 0.1277         | 0.6591         |
| 0.1346         | 0.7393         |


| Convergence time |
|------------------|
| 4h 02m 39s       |
| 3h 44m 37s       |
| 3h 08m 20s       |
| 2h 45m 43s       |
| 3h 21m 49s       |
