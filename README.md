# Genesis-of-Cyber-Threats-Towards-Attribution-of-Advanced-Malicious-Binaries

## Genesis of Cyber Threats: Data Preparation.ipynb
This notebook takes a CSV file named **data_5002.csv** and generates the feature vector for each feature. The **data_5002.csv** is a known dataset file with six columns: md5, TTP, timestamp, group, Aliases, and Country. The final processed data containing feature vectors is saved with the name **Merged_Feature.csv**, and corresponding labels are saved into **Labels.csv**.

## Genesis of Cyber Threats: RF and Top-N.ipynb
This notebook takes previously saved files, Merged_Feature.csv and Labels.csv, as input. This repository implements the Random Forest Classifier and evaluates with the top-n performance method.

## Genesis of Cyber Threats: Identify Unknown Threat Groups.ipynb
This notebook takes known and unknown datasets and evaluates optimal precision scores for the thresholding Mechanism. Further, it links both known and unknown threat group samples

## The Paper has been accepted to **The IEEE International Conference on Trust, Privacy and Security in Intelligent Systems, and Applications (TPS-ISA) 2024**
