What each color means:
----------------------

1. Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate
2. Orange: Original convolutional neural network, 3e-4 learning rate
3. Gray: LeakyReLU, 3e-4 learning rate
4. Navy blue:  LeakyReLU, no dropout, 3e-4 learning rate
5. Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate

Min epoch root mean square error:
---------------------------

1. 0.3561
2. 0.3790
3. 0.3819
4. 0.3574
5. 0.3669


Max epoch value mean square error:
----------------------------

1. 0.6218
2. 0.6140
3. 0.5684
4. 0.5174
5. 0.5252


Min epoch loss:
---------------

1. 0.1268
2. 0.1436
3. 0.1459
4. 0.1277
5. 0.1346


Max epoch loss:
---------------

1. 0.3866
2. 0.3770
3. 0.3231
4. 0.2677
5. 0.2759


Convergence time:
-----------------

1. 4h 02m 39s
2. 3h 44m 37s
3. 3h 08m 20s
4. 2h 45m 43s
5. 3h 21m 49s