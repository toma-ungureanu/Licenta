![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_rmse_val_top5.png)
*Epoch RMSE validation top 5*

![alt text](https://github.com/toma-ungureanu/Licenta/blob/master/model_statistics/png/validation/epoch_loss_val_top5.png)
*Epoch loss validation top 5*

What each color means:
----------------------

1. Light blue: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate
2. Navy blue: Original convolutional neural network, 3e-4 learning rate
3. Orange: LeakyReLU, 3e-4 learning rate
4. Brown:  LeakyReLU, no dropout, 3e-4 learning rate
5. Gray: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate


---------------------------





----------------------------




Min epoch loss:
---------------

1. 0.1459
2. 0.1375
3. 0.1380
4. 0.1439
5. 0.1458


Max epoch loss:
---------------

1. 0.4999
2. 0.2280
3. 0.2048
4. 0.2037
5. 0.2116


Convergence time:
-----------------

1. 4h 02m 39s
2. 3h 44m 37s
3. 3h 08m 20s
4. 2h 45m 43s
5. 3h 21m 49s

| Min epoch root mean square error:  | Max epoch value mean square error: |
| ------------- | ------------- |
| 1. 0.3820  |   1. 0.7070 |
| 2. 0.3708  |   2. 0.4775 |
| 3. 0.3715  |   3. 0.4525 |
| 4. 0.3794  |   4. 0.4514 |
| 5. 0.3818  |   5. 0.4600 |
