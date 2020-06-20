![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_rmse_val_top5.png)
*Epoch RMSE validation top 5*

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_loss_val_top5.png)
*Epoch loss validation top 5*


      | What each color means | Min epoch root mean square error| Max epoch value mean square error| Min epoch loss| Max epoch loss| Convergence time
      | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
      | Light blue: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate                       | 0.3820        |   0.7070      |   0.1459      | 0.4999        | 4h 02m 39s    |
      | Navy blue: Original convolutional neural network, 3e-4 learning rate                                 | 0.3708        |   0.4775      |   0.1375      | 0.2280        | 3h 44m 37s    |
      | Orange: LeakyReLU, 3e-4 learning rate                                                                | 0.3715        |   0.4525      |   0.1380      | 0.2048        | 3h 08m 20s    |
      | Brown:  LeakyReLU, no dropout, 3e-4 learning rate                                                    | 0.3794        |   0.4514      |   0.1439      | 0.2037        | 2h 45m 43s    |
      | Gray: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate               | 0.3818        |   0.4600      |   0.1458      | 0.2116        | 3h 21m 49s    |
