# Physics-integrated deep learning for uncertainty quantification and reliability
estimation of nonlinear dynamical systems

Authors: Udbhav Tripathi, Shailesh Garg, Rajdip Nayek, Souvik Chakraborty

Abstract: Assumptions and approximations made while analyzing any physical system induce modeling uncertainty, which,
if left unchecked, can result in the erroneous analysis of the system under consideration. Additionally, the
discrepancy in the exact knowledge of system parameters can further result in deviation from the ground truth.
This paper explores Physics-integrated Variational Auto-Encoder (PVAE) to account for modeling and parametric
uncertainties in partially known nonlinear dynamical systems. The PVAE under consideration has three main
parts: encoder, latent space, and decoder. The complete PVAE architecture is employed during the training
stage of the machine learning model, while only the decoder is used to make the final predictions. The encoder
determines the correct parameter values for the known part of the model (in the form of a known ODE) .
The decoder is augmented with an ODE solver that solves the known part of the system and the estimated
discrepancy together to reconstruct the measurements. To test the efficacy of the PVAE architecture, three case
studies are carried out, each presenting unique challenges. The probability density functions obtained for the
various systems’ responses demonstrate the efficacy of the PVAE architecture. Furthermore, reliability analysis
has been carried out, and the results produced have been compared against those obtained from a multi-layered,
densely connected forward neural network.
