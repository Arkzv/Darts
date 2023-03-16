# Calculation of expected score distribution in Darts game

The question to answer
* What is the point on the dartboard with the highest expected score given standard deviation of throws (other words where to throw a dart for novice/advanced/expert player?)

### The distribution of scores varies depending on the standard deviation of throws
All the graphs below are generated using the code in the repository

The sample distribution of scores given 1 cm standard deviation of throws

![Distribution of darts scores fiven 1cm std](Imgs/score_distribution_1cm_std.png)

... and standard deviation of throws 2 cm

![Distribution of darts scores fiven 2cm std](Imgs/score_distribution_2cm_std.png)

... and standard deviation of throws 6 cm

![Distribution of darts scores fiven 2cm std](Imgs/score_distribution_6cm_std.png)

As a result, the target point of dartboard with maximum expected score depends on the standard deviation of the throws

![Distribution of darts scores fiven 2cm std](Imgs/Optimal_track.png)


### Requirements
>Python 3.9.13
>Numpy 1.22.4
>
>Tensorflow 2.11.0
>
>Scipy 1.8.1
>
>matplotlib 3.7.1
