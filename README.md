# Intrusion-Detection-System-on-UNSW-NB15-Dataset
UNSW-NB15: Data Information
Source/Useful Links
Get the data from: https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/

PS .i have downloaded it from Kaggle 
## What is IDS (Intrusion Detection System)?
Intrusion Detection Systems (IDS) are precisely present to prevent attacks and infiltration to Networks, which might affect the organization. They monitor network traffic for suspicious activities and issue alert in case of issues.

### Types of IDS:

1, Signature-based intrusion detection– In this kind incoming attacks are compared with pre-existing database of known attacks.
2, Anomaly-based intrusion detection- It uses statistics to form a baseline usage of the networks at different time intervals. They were introduced to detect unknown attacks.

##### Based on where they discover, they can be classified into:

1. Network intrusion detection (NIDS)
2. Host intrusion detection (HIDS)
## Problem Statement
With the rise of Internet usage, it is very important to protect Networks. The most common risk to a network’s security is an intrusion such as brute force, denial of service or even an infiltration from within a network. With the changing patterns in network behavior, it is necessary to switch to a dynamic approach to detect and prevent such intrusions.

### Importance of this dataset:

Although there were few daatset available before this dataset for NIDS, but they were generated decades ago and do not provide realistic outputs. That's why this dataset had been created by Nour Moustafa to tackle existing problems like: unbalanced dataset, missing values etc.

### Data Collection
This dataset has 4 CSV files of the data records and each CSV file contains attack and normal records.

file name	file name size	number of records	number of features
UNSWNB15_1.csv	161.2 MB	700000	49
UNSWNB15_2.csv	157.6 MB	700000	49
UNSWNB15_3.csv	147.4 MB	700000	49
UNSWNB15_4.csv	91.3 MB	440044	49
### Features in the Dataset
This dataset has 49 features.
There are 3 different datatypes:

1. Categorical: proto, state, service, attack_cat
2. Binary: is_sm_ips_ports, is_ftp_login
3. Numerical: Rest of the features
ML Problem Formulation
### Binary classification of attack category

The dataset has "label" with 0 and 1 where 0 represents non-attack and 1 represent attack. So with the features available we will try to predict a given datapoint whether it belongs to attack or non-attack category.

### Performance Metrics
1. Accuracy
2. False Alarm Rate
