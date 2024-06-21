# Energy-Efficiency

About the company

We perform energy analysis using 12 different building shapes simulated in Ecotect. The buildings differ with respect to the glazing area, the glazing area distribution, and the orientation, amongst other parameters. We simulate various settings as functions of the afore-mentioned characteristics to obtain 768 building shapes. The dataset comprises 768 samples and 8 features, aiming to predict two real valued responses. It can also be used as a multi-class classification problem if the response is grouped.

DATASET 

The dataset contains eight attributes (or features, denoted by X1...X8) and one response or outcome denoted by y1. The aim is to use the eight features to predict the responses.

Specifically:

X1 Relative Compactness

X2 Surface Area

X3 Wall Area

X4 Roof Area

X5 Overall Height

X6 Orientation (2=North, 3=East, 4=South, 5=West)

X7 Glazing Area

X8 Glazing Area Distribution (0=Unknown, 1=Uniform, 2=North, 3=East, 4=South, 5=West)

y1 Cooling Load

DATASET LINK: https://archive.ics.uci.edu/ml/datasets/Energy+efficiency 

ANALYSIS

We have used various machine learning models to predict the cooling load of the building and then determining which model predicts best by selecting the one with highest accuracy.
