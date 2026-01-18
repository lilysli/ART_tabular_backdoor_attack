# Tabular Backdoor Attack

This notebook demonstrates how to conduct a backdoor attack on a phishing detection model (compatible with ART).

It consists of the following steps:
1) Loading, cleaning, and splitting the tabular dataset
2) Training a clean baseline phishing detection model (to be used for comparison)
3) Choosing the trigger features: 3 values that when combined will make the model categorise a phishing attempt as legitimate.
4) Poisoning the training dataset
5) Train a new phishing detection model with the poisoned data
6) Evaluate and compare the clean and the backdoored model

Source of phishing detection dataset (dataset_B_05_2020.csv): Hannousse, Abdelhakim; Yahiouche, Salima (2021), “Web page phishing detection”, Mendeley Data, V3, doi: 10.17632/c2gw7fy2j4.3
