22.05.2024 10:37:15
Repository not in the required format. Should be a clone of my repository

# Banknotes NB

## Problem 1

14.06.2024 10:23:59 OK

## Problem 2

14.06.2024 10:23:59 OK

## Problem 3

14.06.2024 10:23:59 OK

# Banknotes GMDA

## Problem 1

14.06.2024 10:31:46 OK

## Problem 2

14.06.2024 10:32:53
Almost OK. The arguments pi0 and pi1 to `make_predict_proba` function are wrong. The numbers of countereit and non-counterfeit banknotes are not equal.  

18.06.2024 12:29:27 OK

## Problem 3

14.06.2024 10:33:21
As in the previous problem

18.06.2024 12:29:27 OK

## Problem 4

14.06.2024 10:33:47
Optimal points are wrongly plotted. 
The three classifiers that should be compares are the classifiers from Problems A-C: GDA, GMDA and optimal GMDA

18.06.2024 12:42:31
Your cost is wrong. You should exchange the fp_rate and fn_rate. Positive means counterfeit. 

# Banknotes NN

14.06.2024 10:47:30
You should at least try some more complicated network.

18.06.2024 12:43:53 OK

1.07.2024 15:27:14
The formula for loss is still wrong. False positive means rejecting a non-counterfeit banknote as counterfeit. The loss is the 15zl. But Probability of presenting a non-counterfeit banknote is 0.99 not 0.01. 