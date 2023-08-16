# deep-learning-challenge


Create a machine learning model that will predict the eligibilty of an applicant for an Alphabet Soup grant. 

## Part 1: Create Initial Model
1. Import the necessary dependencies:
* sklearn.model_selection import train_test_split
* sklearn.preprocessing import StandardScaler
* pandas
* tensorflow
* sklearn

2. Drop non-beneficial columns and determine the number of unique values in each.

3. Create bins for any "object" data types use get_dummies to replace all columns with "object" data type.

4. Create X and y values with is "IS SUCCESSFUL" and then split the data.

5. Create a StandardScaler model and fit it to the X_train, X_test data.

6. Define the deep neural model with 2 layers. Compile the model. Fit to the X_train_scaled and y_train and run.

7. Evaluate the model

8. Export the model
## Part 2: Optimize the Model

1. Repeat steps 1 & 2 from part 1 EXCEPTION- DO NOT- drop Name Column.

2. Repeat steps 3-7 of part 1. Input_dim will change to 398.

3. Reruns the model with increased epochs.

4. Adds a third layer to the model and increases the units in each layer of the model. Run and evaluate.

5. Export the optimized model



