# rapid-experiments

3 key conclusions:
1. The hidden layer size of 256 is great! Tried 128, 512, 1024..
2. ‘dropout’ probability seemed to be perfect around the value of 0.5
3. "softPLUS" activation function aced! (better than logistic/sigmoid, ReLU, softsign, TanH, in this order!)


The newswire_topics module is now well documented (following proper python docstring conventions.)

Upping the maximum number of words from 1000 to 7000 improved the test accuracy even more above-80%!
