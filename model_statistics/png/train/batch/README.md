What each color means:
----------------------

1. Brown: LeakyReLU, no dropout, multiple skip additions, 3e-4 learning rate
2. Orange: Original convolutional neural network, 3e-4 learning rate
3. Gray: LeakyReLU, 3e-4 learning rate
4. Navy blue:  LeakyReLU, no dropout, 3e-4 learning rate
5. Green: LeakyReLU, no dropout, skip additions on medium sized layers, 3e-4 learning rate

Min batch root mean square error:
---------------------------

1. 0.3561
2. 0.3790
3. 0.3819
4. 0.3574
5. 0.3669


Max batch value mean square error:
----------------------------

1. 0.8347
2. 1.067
3. 0.938
4. 0.8119
5. 0.8598


Min batch loss:
---------------

1. 0.1268
2. 0.1436
3. 0.1459
4. 0.1277
5. 0.1346


Max batch loss:
---------------

1. 0.6968
2. 1.1398
3. 0.8799
4. 0.6591
5. 0.7393


Convergence time:
-----------------

1. 4h 02m 39s
2. 3h 44m 37s
3. 3h 08m 20s
4. 2h 45m 43s
5. 3h 21m 49s