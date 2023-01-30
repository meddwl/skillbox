# Tutorial on QSAR modeling

The tutorial on QSAR starts [here](http://localhost:8889/notebooks/github/skillbox/QSAR/QSAR.ipynb)

## Definition and Goals

QSAR stands for Quantitative Structure-Activity Relationship.

QSAR is a computational method used in drug discovery and toxicology to predict the biological activity of 
chemicals based on their structural and/or physico-chemical properties.

**QSAR aims** to establish a mathematical correlation between the structural characteristics of a chemical compound 
and its biological activity, so that the activity of new compounds can be predicted without conducting expensive 
and time-consuming experimental testing.

## The main steps of QSAR include:

1. **Selection of a dataset**: A dataset of compounds with known biological activity and corresponding structural information is selected for building the QSAR model.
2. **Data preprocessing**: The structural information is prepared for modeling by encoding it into numerical descriptors, which are used as input variables for the model. The dataset is also usually divided into a training set and a test set.
3. **Model building**: A statistical or machine learning model is built using the training set. The model aims to establish a mathematical relationship between the input variables (descriptors) and the biological activity.
4. **Model evaluation**: The model is evaluated using the test set to determine its predictive performance.
5. **Model application**: The model can be used to predict the biological activity of new compounds based on their structural information.
6. **Model validation**: The model is validated by comparing the predicted activity of new compounds to the experimental data.

*Note that*: step vary depending on the complexity of the model, the type of data and the goal of the study
