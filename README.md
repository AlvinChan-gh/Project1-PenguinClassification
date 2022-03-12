# Project 1 - PenguinClassification
Classify Penguins with different Machine Learning models

![picture alt](https://github.com/allisonhorst/palmerpenguins/raw/master/man/figures/lter_penguins.png)

What are culmen length & depth?
The culmen is "the upper ridge of a bird's beak" (definition from Oxford Languages).

**Task:** Predict the class of penguin species
**Questions to Answer:**
* Perform a detailed exploratory data analysis on the dataset
* Experiment using two different ratios of training, validation and test data ie 60-20-20 & 80-10-10. On the two different split ratios do the following
  * Implement Grid Search CV to find optimal hyperparameters for any 3 algorithms (out of LR, SVM, MLP, RF, Boosting)
  * Plot the learning curve using the learning curve function from scikit-learn to analyze the model performance. The plot should show the training score and cross validation score against the number of training examples.
  * Analyze the results on Validation set and Test set and mention which model performed the best and why?
* Compare the performance of models(using precision, recall, accuracy, latency).
* What was the best proportion or split ratio of data from the set of experiments you conducted and why?

## References

**Data originally published in:**

  - Gorman KB, Williams TD, Fraser WR (2014). Ecological sexual
    dimorphism and environmental variability within a community of
    Antarctic penguins (genus *Pygoscelis*). PLoS ONE 9(3):e90081.
    <https://doi.org/10.1371/journal.pone.0090081>

**Data citations:**

Adélie penguins:

  - Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Adélie penguins (*Pygoscelis adeliae*) nesting along the
    Palmer Archipelago near Palmer Station, 2007-2009 ver 5.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f>
    (Accessed 2020-06-08).

Gentoo penguins:

  - Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Gentoo penguin (*Pygoscelis papua*) nesting along the
    Palmer Archipelago near Palmer Station, 2007-2009 ver 5.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/7fca67fb28d56ee2ffa3d9370ebda689>
    (Accessed 2020-06-08).

Chinstrap penguins:

  - Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Chinstrap penguin (*Pygoscelis antarcticus*) nesting
    along the Palmer Archipelago near Palmer Station, 2007-2009 ver 6.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/c14dfcfada8ea13a17536e73eb6fbe9e>
    (Accessed 2020-06-08).
