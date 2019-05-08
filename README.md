# NCAA

This is a fairly succesful entry in Kaggle's [Mens](https://www.kaggle.com/c/mens-machine-learning-competition-2018) and [Womens](https://www.kaggle.com/c/womens-machine-learning-competition-2018)
NCAA prediction competitions. Both entries placed in the top 5%. 

See the included slides for a more detailed description and the approach is generally outlined in my blog post [here](https://www.ca.com/en/blog-agile-central/understanding-march-madness-machine-learning.html)

# Contents

* Data Cleaning - join and clean the Kaggle data, moving average and diff a few columns
* Binary model - a simple binary classifier to assign a probability that team wins based on their recent performance and their opponent's recent performance 
* Linear models - predict a point differential for two teams given their recent performance. Ultimately, this should be mapped to a win/loss probability. For now, just naively assign the predicted higher scorer a high chance of winning.
