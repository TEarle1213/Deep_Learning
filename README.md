# Deep_Learning

## Technologies
  Python, Pandas, sklearn, tensorflow, jupyter notebook

## Resources
 Data for this dataset was found through IRS records. Tax Exempt Organization Search Bulk Data Downloads. https://www.irs.gov/Links to an external site.
 
 ## Purpose
 Create a deep learning model to assist the nonprofit foundation Alphabet Soup in evaluating the success of previous investments. The foundation would like a tool to predict the potential for success of future investment, in order to best allocate their funding. 
  
 ## Analysis Methods
  - Preprocess data utilizing sklearn, standard scaler and train_test_split
  - Create neural network using TensorFlow
  - Evaluate accuracy of model.
  - Use optimization methods to improve neural network and evaluate improvement.
## Reporting
Data Preprocessing

- What variable(s) are the target(s) for your model?
-- The target variable is IS_SUCCESSFUL
- What variable(s) are the features for your model? 
-- All other columns are features except those noted below.
- What variable(s) should be removed from the input data because they are neither targets nor features?
-- EIN and NAME are removed as features, they are identifiers that have no bearing on the success of the venture.

## Compiling, Training, and Evaluating the Model

- Were you able to achieve the target model performance? 
-- Target performance was 75% and each model fell a bit short, never passing 74% accuracy.
- What steps did you take in your attempts to increase model performance?
-- Four total attempts were made to create a model that would hit the 75% accuracy metric being asked for. Across the attempts, additional columns besides the identifiers were dropped, more layers were added, neurons were added and removed, different activations for the neurons were tried and the number of epochs for training were adjusted. The accuracy is too low for deployment, it would be my recommendation to either try further optimization of the neural net model with a tool like keras-tuner or to attempt a machine learning build of a different type. It could be appropriate to try regression modeling or decision trees. 

