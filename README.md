# Cost Estimation

The objective of this kernel is to create a Regression model which restimates the cost of sale per unit based on number of units sold.
 
Our regression analysis kernel consists of 7 steps:

### Step 0 - Import the Libraries:
in addition to the scikit-learn library whhich we use to perform the Regression analysis, we also use several other packages and modules:

- **Pandas**:used for data structures and operations for manipulating numerical tables
- **Numpy**: used for numerical analysis
- **matplotlib.pyplot**: used for plotting data
- **seaborn**: used for data visualization (used on top of matplotlib library)
- **sklearn**: used in our kernel to split the set into a training and a testing set, and to create and to evaluate the model.

### Step 1 - Import the Dataset:
We import the data from a csv file, and we load it into a pandas DataFrame object.

### Step 2 - Visualize Data:
We explore the dataset using a jointplots and an lmplot.

### Step 3 - Train model:
We use the PolynomialFeatures module to transform our data into one with multiple columns, then we create a linear regression

### Step 4 - Evaluate Model:
We plot the results using a scatter plot and we plot our polynomial plot on the graph.
