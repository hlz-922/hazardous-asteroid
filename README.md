# hazardous-asteroid

### **Project Description**

The project involves training a Decision Tree Classifier to predict whether Near-Earth Objects (NEOs) pose a hazard to planet Earth. It's based on a pre-processed version of a dataset from NASA, which can be found on their [website](https://data.nasa.gov/Space-Science/Asteroids-NeoWs-API/73uw-d9i8/about_data). The project description emphasizes the importance of naming variables according to specific requirements and ensuring that these variables retain their values throughout the notebook execution, as they will be used for evaluation.

### Key steps in

**Dataset Preparation and Analysis**:

- The project starts with a dataset from NASA's [website](https://data.nasa.gov/Space-Science/Asteroids-NeoWs-API/73uw-d9i8/about_data), which has been pre-processed for the purpose of this analysis.
- Participants are expected to follow instructions carefully, particularly regarding the naming of variables, to ensure compatibility with evaluation processes.

**Defining Variables**:

- Instructions are provided for defining key variables throughout the project. These include:
    - The main DataFrame **`df`**, which likely contains the NEO data.
    - The features matrix **`X`**, prepared for training the classifier.
    - The target variable **`y`**, indicating whether an NEO is hazardous.
    - Calculations for the fractions of observations in each target class (**`frac0`** for non-hazardous, **`frac1`** for hazardous).

**Model Training**:

- A Decision Tree Classifier is trained to predict the hazardous status of NEOs.
- The process involves selecting relevant features, handling data correctly, and applying appropriate machine learning techniques.

**Evaluation and Optimization**:

- The model's performance is evaluated, with specific steps likely outlined for calculating accuracy and other metrics on training and test sets.
- A grid search may be conducted to find optimal model parameters, improving prediction accuracy.
