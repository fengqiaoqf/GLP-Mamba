# GLP-Mamba
The specific details of the paper "GLP-Mamba: A Global-Local Mamba Architecture for Accurate Remote Photoplethysmography Estimation"

# The complete code will be made public after the paper is accepted.

# Abstract
Remote photoplethysmography (rPPG) is a non-contact technique for physiological
measurement from facial videos. However, accurate estimation remains challenging
because pulse signals inherently contain both stable long-term rhythms and short-term
local variations, the latter being extremely subtle and easily corrupted by interference.
The main difficulty therefore lies in jointly capturing these multi-scale dynamics while
maintaining robustness to such disturbances. To address this challenge, we propose
GLP-Mamba, a global–local Mamba-based framework for robust rPPG estimation, integrating
the Twin-Path Mamba (TPM) and the Differential Motion Encoder (DME).
The TPM models long-term physiological rhythms through a global Mamba pathway
and captures short-term local variations through a local convolutional pathway.
The DME enhances the input representation by adaptively fusing multi-scale temporal
difference cues with spatial appearance features, thereby suppressing transient artifacts
and preserving subtle pulse-related variations. Experiments on multiple datasets
demonstrate that GLP-Mamba achieves state-of-the-art performance with lower computational
cost and strong cross-dataset generalization, with the largest relative improvement
reaching 24.8%.
