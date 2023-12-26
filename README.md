# Agent Based Model Calibration to predict Stocks Behavior

This project contains some algorithms to help stocks behavior prediction, thanks to agent based models (ABM) and generalized moments method (GMM).
The model used here is:

$p_{t+1} - p_t = \kappa_1(v_t-p_t) + \beta\text{tanh}(\gamma m_t)+\varepsilon_t$

$m_t=(1-\alpha)m_{t-1}+\alpha(p_t-p_{t-1})$

$v_t = (1-\lambda)v_{t-1}+\lambda p_t$

Then, the parameters we will try to approach is $\xi=(\kappa_1, \beta, \gamma, \alpha, \lambda, \sigma(\varepsilon))$.

If you want to have more informations on the results and their interpretation, I suggest you read miscellaneous/slides.pdf!

If you have any question on the code, or on everything related to this project, don't hesitate to contact me : marius.verdier@student-cs.fr

Have fun!