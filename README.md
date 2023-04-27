# RECH
The code implements the RECH model (LSTM-tGARCH) developed in:

N. Nguyen, M.-N. Tran, R. Kohn (2022). Recurrent Conditional Heteroskedasticity. Journal of Applied Econometrics, 37(5), 1031-1054. 
See also https://arxiv.org/abs/2302.08002

Note that, in the JAE paper, we implemented RNN-GARCH for the RECH specification. The LSTM-tGARCH specification is more sophisticated and works better.
The code also implements tGARCH and compares the performance of LSTM-tGARCH with tGARCH. 
Realized measures (on test data) are used as a volatility proxy to test the predictve performance.

Run SP500_analysis.m to see the trained models and their performance.

