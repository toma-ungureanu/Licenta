![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/epoch/epoch_rmse_train_top5.png)
*Epoch RMSE train top 5*

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/train/epoch/epoch_loss_train_top5.png)
*Epoch loss train top 5*

| What each color means                                                                   | Min epoch root mean square error | Max epoch value mean square error | Min epoch loss | Max epoch loss | Convergence time |
|-----------------------------------------------------------------------------------------|----------------------------------|-----------------------------------|----------------|----------------|------------------|
| Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate               | 0.3561                           | 0.6218                            | 0.1268         | 0.3866         | 4h 02m 39s       |
| Orange: Original convolutional neural network, 3e-4 learning rate                       | 0.3790                           | 0.6140                            | 0.1436         | 0.3770         | 3h 44m 37s       |
| Gray: LeakyReLU, 3e-4 learning rate                                                     | 0.3819                           | 0.5684                            | 0.1459         | 0.3231         | 3h 08m 20s       |
| Navy blue: LeakyReLU, no dropout, 3e-4 learning rate                                    | 0.3574                           | 0.5174                            | 0.1277         | 0.2677         | 2h 45m 43s       |
| Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate | 0.3669                           | 0.5252                            | 0.1346         | 0.2759         | 3h 21m 49s       |
