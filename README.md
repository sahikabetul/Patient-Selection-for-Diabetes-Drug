# Patient Selection for Diabetes Drug
## Applying AI to Electronic Health Record(EHR) Data - Udacity AI for Heathcare Course

EHR data is becoming a key source of real-world evidence (RWE) for the pharmaceutical industry and regulators to make decisions on clinical trials. 

<img src="https://hellohealth.com/static/09091f20d7b4381bdf731b0f876d01da/cf0d5/How-Does_an_EHR_Improve_Patient_Care.png" width="800px" height="auto">

## Case of the project
You are a data scientist for an exciting unicorn healthcare startup that has created a groundbreaking diabetes drug that is ready for clinical trial testing. It is a very unique and sensitive drug that requires administering the drug over at least 5-7 days of time in the hospital with frequent monitoring/testing and patient medication adherence training with a mobile application. You have been provided a patient dataset from a client partner and are tasked with building a predictive model that can identify which type of patients the company should focus their efforts testing this drug on. Target patients are people that are likely to be in the hospital for this duration of time and will not incur significant additional costs for administering this drug to the patient and monitoring.

In order to achieve goal, I built a regression model that can predict the estimated hospitalization time for a patient and use this to select/filter patients for my study.

## Dataset
I used a dataset from UC Irvine that has been modified for patient privacy.

https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008 Data Schema The dataset reference information can be https://github.com/udacity/nd320-c1-emr-data-starter/tree/master/project/data_schema_references. There are two CSVs that provide more details on the fields and some of the mapped values.

## Prerequisites
- Intermediate level knowledge of Python
- Basic knowledge of probability and statistics
- Basic knowledge of machine learning concepts
- Installation of Tensorflow 2.0 and other dependencies(conda environment.yml or virtualenv requirements.txt file provided)

## Libraries Used

```
import pandas as pd
import numpy as np
import os
import tensorflow as tf
import functools
```
