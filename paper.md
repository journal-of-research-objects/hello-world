# Hello World
## Introduction

In order to submit a repository to the Journal of Research Objects, you must have a paper.md file explaining and running the application with the training data. This file will be converted to a Jupyter Notebook and published in order to execute the code cells. 

## Algorithm
```
# The code must be enclosed between these characters. 
import matplotlib.pyplot as plt
f= open("train-data/bars.txt")
#graphing the data
data = [int(line.strip("\n")) for line in f]
plt.figure(figsize=(12,12))

plt.plot(range(len(data)), data)
```

## Conclusions
This algorithm pretends to depict the data in a line plot. 
