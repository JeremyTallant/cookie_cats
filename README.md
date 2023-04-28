# Mobile Games A/B Testing with Cookie Cats
## Description 
[Cookie Cats](https://www.facebook.com/cookiecatsgame) is a hugely popular mobile puzzle game developed by [Tactile Entertainment](https://tactilegames.com/). It's a classic "connect three" style puzzle game where the player must connect tiles of the same color in order to clear the board and win the level. It also features singing cats. We're not kidding!

As players progress through the game they will encounter gates that force them to wait some time before they can progress or make an in-app purchase. In this project, we will analyze the result of an A/B test where the first gate in Cookie Cats was moved from level 30 to level 40. In particular, we will analyze the impact on player retention.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, and `matplotlib`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy matplotlib
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Of cats and cookies:** Read in and take a look at the Cookie cats AB-test data.
2. **The AB-test data:** Count the players in each AB-group.
3. **The distribution of game rounds:** Plot the distribution of game rounds.
4. **Overall 1-day retention:** Calculate overall 1-day retention.
5. **1-day retention by AB-group:** Calculate 1-day retention for each AB-group
6. **Should we be confident in the difference?:** Do a bootstrap analysis of 1-day retention and plot the result.
7. **Zooming in on the difference:** Calculate and plot the % difference in 1-day retention between the two AB-groups.
8. **The probability of a difference:** Calculate the probability that a gate at level 30 gives higher 1-day retention.
9. **7-day retention by AB-group:** Calculate the 7-day retention for each AB-group
10. **Bootstrapping the difference again:** Do a bootstrap analysis for the difference in 7-day retention.
11. **The conclusion:** Given the data and the analysis should we move the gate to level 40, or keep it at level 30?
