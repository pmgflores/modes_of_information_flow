# Modes of Information Flow Analysis

Implementation of information flow analysis using time-delayed mutual information and transfer entropy.

## Overview
This code demonstrates the analysis of information flow between time series variables using three distinct modes: intrinsic, shared, and synergistic flow. The implementation follows the framework developed by [James et al. (2018)](https://arxiv.org/abs/1808.06723) and includes practical applications to emotional communication analysis.

## Key Concepts
- **Intrinsic Flow**: Direct prediction of variable Y's present state from X's past
- **Shared Flow**: Prediction of Y using either X's past or Y's past
- **Synergistic Flow**: Combined past states of X and Y predict Y's present state

## Mathematical Framework
Key formulas implemented:
- Time-delayed mutual information
- Transfer entropy
- Intrinsic mutual information
- Derived shared and synergistic flows

## Example Application
The code includes analysis of emotional content in social media communications following natural disasters:
1. Data collection from Twitter
2. Emotion detection using IBM Watson
3. Flow analysis between five emotions (sadness, anger, fear, disgust, joy)
4. Visualization of information flow modes

## References
Based on the post: ["Modes of Information Flow"](http://pablomflores.com/modes-of-information-flow) by Pablo M. Flores.

## License
This work is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
