# ADAM-Add: Enhancing ADAM with Adaptive Decay Rates

## Abstract
We proposed a modification to the Adam optimizer. In addition to the maximum of past squared gradient adpated by AMSGrad, we added an update to the decay rates $\beta_1$ and $\beta_2$. Following this modifications, we visualized the convergence on several artificial landscapes, and tested our optimizer empirically on logistic regression, multi-layer neural network, and CNNs. Initially, we believe that adding an adaptive decay rate will stabilize the update, which will improve the speed of convergence. However, in practice, as shown in our experiments, the result was not always positive. In addition, in cases where our optimizer converges, although the optimizer was stable, it is sometimes too cautious and thus result in slow convergence. Nonetheless, we do find in some experiments that our additional update to $\beta$ improves Adam in both the rate of convergence and the loss at convergence.

## Report
Our report is available at [CSC413_Project_Report.pdf](CSC413_Project_Report.pdf)
