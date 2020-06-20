| Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate | Orange: Original convolutional neural network, 3e-4 learning rate |  Gray: LeakyReLU, 3e-4 learning rate |  Navy blue: LeakyReLU, no dropout, 3e-4 learning rate | Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate|
|---------------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|-------------------------------------|------------

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/batch/batch_rmse_top5.png)
*Batch RMSE train top 5*

|Colour                             |Min batch root mean square error | Max batch value mean square error |
|----------------------------------|----------------------------------|-----------------------------------|
| Brown                                  | 0.3561                           | 0.8347                            |
| Orange                                 | 0.3790                           | 1.067                             |
| Gray                                 | 0.3819                           | 0.938                             |
| Navy blue                                 | 0.3574                           | 0.8119                            |
| Green                                 | 0.3669                           | 0.8598                            |

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/batch/batch_loss_top5.png)
*Batch loss train top 5*

| Colour | Min batch loss | Max batch loss |
|----------------|----------------|----------------|
| Brown          | 0.6968         | 0.1268|
| Orange         | 1.1398         | 0.1436|
| Gray           | 0.8799         | 0.1459|
| Navy blue      | 0.6591         | 0.1277|
| Green          | 0.7393         | 0.1346|


| Colour | Convergence time |
|------------------|------------------|
|Brown| 4h 02m 39s       |
|Orange| 3h 44m 37s       |
|Gray| 3h 08m 20s       |
|Navy blue| 2h 45m 43s       |
|Green| 3h 21m 49s       |
