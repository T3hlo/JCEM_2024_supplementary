# Abstract

## Background:
University Hospitals Dorset (UHD) has over 1,000 thyroid patient contacts annually. These are primarily patients with autoimmune hyperthyroidism treated with Carbimazole titration. Dose adjustments are made by a healthcare professional (HCP) based on the results of thyroid function tests, who then T prescribes a dose and communicates this to the patient via letter. This is time-consuming and introduces treatment delays. This study aimed to replace some time-intensive manual dose adjustments with a machine learning model to determine Carbimazole dosing. This can in the future serve patients with rapid and safe dose determination and ease the pressures on HCPs.

## Methods:
Data from 421 hyperthyroidism patients at UHD were extracted and anonymised. A total of 353 patients (83.85%) were included in the study. Different machine-learning classification algorithms were tested under several data processing regimes. Using an iterative approach, consisting of an initial model selection followed by a feature selection method the performance was improved. Models were evaluated using weighted F1 scores and Brier scores to select the best model with the highest confidence.

## Results:
The best performance is achieved using a random forest (RF) approach, resulting in good average F1 scores of 0.731. A model was selected based on a balanced assessment considering the accuracy of the prediction (F1 = 0.755) and the confidence of the model (Brier score = 0.366), a model was selected. 

## Conclusion:
To simulate a use-case, the accumulation of the prediction error over time was assessed. It was determined that an improvement in accuracy is expected if this model was to be deployed in practice.
