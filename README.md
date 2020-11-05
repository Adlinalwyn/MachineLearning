# MachineLearning
Assignment 2 

First I ran the code given in the question, it resulted in [1,    20] with a loss of 2.377 and ended with [10,  1560] loss of 0.903. 

Then I added the L2 regularizer with learning rate - lr=1e-4 and weighted decay of 1e-5; to get : [1,    20] loss: 2.980 and [10,  1560] loss: 1.500. The loss was quite high for this. 

After I changed the values to lr=0.2 and weight_decay=1e-2, to see if it would improve the results and I got drastically bad results [1,    20] loss: 4.374  and [10,  1560] loss: 1.615. 

Tweaking the learning rate an weighted gain again, lr=0.05, weight_decay=1e-10, I got results similar to the first code given in the question but infact with minimized losses ; [1,    20] loss: 2.124 and [10,  1560] loss: 0.897.

I played with the numbers a little more namely; lr=0.075, weight_decay=1e-10 to get better losses [1,    20] loss: 2.075 and 

#### To run the code: 

Please run each cell separately, thanks! 

|   LR Vaule    | Weight-decay  |  Loss begin   |   Loss End    |
| ------------- | ------------- | ------------- | ------------- |
|     0.001     |      0.9      |     2.377     |     0.903     |
|     1e-4      |      1e-5     |     2.980     |     1.500     |
|     0.2       |      1e-2     |     4.374     |     1.615     |
|     0.05      |      1e-10    |     2.124     |     0.897     |
|     0.075     |      1e-10    |     2.075     |          |
