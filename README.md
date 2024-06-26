# ai-notes
A place to keep notes and program snippets for AI concepts.

## plot_entropy.ipynb

Developed in Google Colab.  Displays several graphs to help visualize and understand information entropy.

## functions_of_two_boolean_variables.ipynb

Developed in Google Colab.  Displays all sixteen possible functions of two boolean variables.  This is helpful for understanding why the total number of possible functions for n number of boolean input variables is 2<sup>2<sup>n</sup></sup>.

**Update**: since writing this, I discovered a Wikipedia entry that covers this topic better and in much greater and meaningful detail:
[Truth Table (Wikipedia)](https://en.wikipedia.org/wiki/Truth_table)

## restaurant_decision_tree.ipynb

This notebook implements in Python the restaurant decision tree algorithm pseudocode from Chapter 19 in:

Russell, Stuart, and Peter Norvig. *Artificial Intelligence: A Modern Approach.* 4th ed. Pearson, 2020.

I also add my own code that uses graphviz to render a graphical representation of the decision tree and use it for inference.

## restaurant_waiting_examples.csv
The data from the AIMA textbook.  The "restaurant_decision_tree.ipynb" notebook reads this and uses it as the training set.