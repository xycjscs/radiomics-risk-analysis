# radiomics-risk-analysis
updating for title Incremental prognostic value of CCTA-based myocardial radiomics over clinical and CTA findings in patients with stable angina

## AI-features.py
one needs to get the cropped slice of lesions. Then converted it to .npy form. This python script will extracted Ai features of your .npy figures in the Preprocess folder. Note, the example 1.npy in the folder is used for illustration only. For privacy purpose, it does not related to patients included in this study. 

## Active.Coefficients.csv
This file contains all seletected features and its corresponding coefficients to calculate scros.

## nomo.cvs
It contains time, features, radscors to do survical analysis with the nomogram0208.R..bin tool.

## nomogram0208.R..bin
It is used to perform survaival analysis, generate nomograms, and prpedict for new patiens. 
