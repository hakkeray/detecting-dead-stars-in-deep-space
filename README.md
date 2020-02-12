
## PREDICTING A PULSAR STAR

MODULE 5 FINAL PROJECT

* Student name: Ru Keïn
* Student pace: full time
* Scheduled project review date/time: Feb 11, 2020 @ 4 PM EST
* Instructor name: James Irving, PhD
* Blog post URL:

### OVERVIEW

*From Dr. Robert Lyon on Kaggle:*

HTRU2 is a data set which describes **a sample of pulsar candidates collected during the High Time Resolution Universe Survey.**

Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of considerable scientific interest as probes of space-time, the inter-stellar medium, and states of matter .

As pulsars rotate, their emission beam sweeps across the sky, and when this crosses our line of sight, produces a detectable pattern of broadband radio emission. As pulsars rotate rapidly, this pattern repeats periodically. Thus pulsar search involves looking for periodic radio signals with large radio telescopes.

Each pulsar produces a slightly different emission pattern, which varies slightly with each rotation . Thus a potential signal detection known as a 'candidate', is averaged over many rotations of the pulsar, as determined by the length of an observation. In the absence of additional info, each candidate could potentially describe a real pulsar. However in practice almost all detections are caused by radio frequency interference (RFI) and noise, making legitimate signals hard to find.

Machine learning tools are now being used to automatically label pulsar candidates to facilitate rapid analysis. Classification systems in particular are being widely adopted, which treat the candidate data sets as binary classification problems. Here the legitimate pulsar examples are a minority positive class, and spurious examples the majority negative class.

The data set shared here contains 16,259 spurious examples caused by RFI/noise, and 1,639 real pulsar examples. These examples have all been checked by human annotators.

Each row lists the variables first, and the class label is the final entry. The class labels used are 0 (negative) and 1 (positive).

### OUTLINE

    * IMPORT PACKAGES + LIBRARIES
    
    * OBTAIN DATA
    
    * PRE-PROCESSING
    
    * EDA + VISUALIZATIONS
    
    * MODELING:
        * MODEL 1: DECISION TREES
        * MODEL 2: XBOOST
        * MODEL 3: GRIDSEARCH CV
        
    * INTERPRET RESULTS
    
    * CONCLUSION + SUMMARY
    
    * FUTURE WORK



```python
# Import code packages and libraries
import pandas as pd
import numpy as np
import matplotlib as mpl
%matplotlib inline
import matplotlib.pyplot as plt

from sklearn.model_selection import train_test_split
import seaborn as sns
sns.set_style('whitegrid')
plt.style.use('seaborn-bright')


font_dict={'family':'monospace',
          'size':16}
mpl.rc('font',**font_dict)

```


```python
# OBTAIN data
```


```python
# PRE-PROCESSING
```


```python
# EDA + VISUALIZATIONS
```


```python
# MODELING
```


```python
# MODEL 1: DECISION TREES
```


```python
# MODEL 2: XBOOST
```


```python
# MODEL 3: GRIDSEARCH CV
```


```python
# INTERPRET RESULTS
```


```python
# CONCLUSION + SUMMARY
```


```python
# FUTURE WORK
```
