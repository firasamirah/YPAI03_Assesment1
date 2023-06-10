# Create a deep learning model using LSTM neural network to predict new cases (cases_new) in Malaysia using the past 30 days of number of cases.

## Project Description
The year 2020 was a catastrophic year for humanity. Pneumonia of unknown aetiology was first reported in December 2019., since then, COVID-19 spread to
the whole world and became a global pandemic. More than 200 countries were affected due to pandemic and many countries were trying to save precious lives
of their people by imposing travel restrictions, quarantines, social distances, event postponements and lockdowns to prevent the spread of the virus. However, due
to lackadaisical attitude, efforts attempted by the governments were jeopardised, thus, predisposing to the wide spread of virus and lost of lives. 

This project uses Deep learning concept in detection of Various Deadly diseases. It can detect lung cancer, covid-19, tuberculosis and pneumonia. LSTM neural network will be used to predict new cases (cases_new) in Malaysia using the past 30 days of number of cases.

## Challenges and the solutions

## The installation and how to run the project 

### Steps for installation

##### There are various methods to download the code of github on your system:-

Clone repository

1) Go to that particular repository
2) Click on the download icon
3) Copy the repo link(you can also copy this from page URL)
4) go to your terminal and type git clone <link> 

Download Zip

1) Go to repository
2) Again click on download icon
3) Click on download zip
4) Now your Zip will be downloaded , unzip and use it.

Get raw code

If you don't want the whole repository, or want to use only one or two files ,

1) Go to that file
2) Click on Raw and you will see the page with raw code ,
3) At this point you can download that page, or you can also copy the code.
4) To download the page simply run wget <pageUrl> 

### Steps for running the project 
Here are the steps to compile and run a GitHub project:

1) Clone the repository: Use the "git clone" command in a terminal/command prompt to download the project files to your local machine.
2) Navigate to the project directory: Use the "cd" command to navigate to the directory where the project files are located.
3) Install dependencies: If the project requires any external libraries, install them using the package manager specified in the project's documentation (e.g., pip, npm, etc.).
4) Compile the project: Depending on the language and framework used, compile the project using a build tool (e.g., make, gradle, etc.) or by executing a script provided in the project files.
5) Run the project: Execute the compiled binary or run the script to launch the project.

## Output of the project
##### Graph for trining process model
  
Train and test Mean Absolute Error (MAE) evaluation measures are used in machine learning to rate a model's effectiveness.

The average absolute difference between the expected and actual values is measured by MAE. The formula is as follows:


MAE = [y_pred - y_actual] * (1/n)

where:

The number of data points is n.
The values expected are represented by y_pred.
The values are represented by y_actual.
The MAE generated on the training dataset is referred to as the "train MAE." It gauges how well the model conforms to the training set of data. A low train MAE shows that the model can successfully extract the correlations and patterns from the training set.

On the other hand, test MAE refers to the MAE computed on a different dataset known as the test dataset. This dataset is used to assess how well the model performs on data that has not yet been seen; it is not utilised during the training phase. Test MAE offers an estimate of the model's ability to generalise to fresh, untested examples. It aids in determining if the model has picked up on the data's underlying trends or if it has overfitted the training set.

Low MAE values for the train and test are generally preferred. A low test MAE signals strong generalisation performance, while a low train MAE shows that the model is fitting the training data effectively. Large disparities between the MAE for the training and test sets may be a sign of overfitting, when the model is overly tailored to the training set and underperforms on the test set.

![Training process plotted](https://github.com/firasamirah/YPAI03_Assesment1/assets/91971387/db839d06-b776-4c25-a480-6828f6ccd72f)

##### Graph for Predicted Cases VS Actual Cases 
A graph comparing predicted cases versus actual cases is a visual representation that helps to compare the predicted values generated by a model or algorithm with the actual observed values. This type of graph is commonly used in predictive modeling or forecasting tasks.

The resulting graph will visually show the relationship between the predicted cases and the actual cases. It can help assess how well the predictions align with the observed values and identify any patterns or discrepancies.
  
![Graph for Predicted VS Actual](https://github.com/firasamirah/YPAI03_Assesment1/assets/91971387/ddea6110-c393-42b5-be11-4b6ffcb89b0b)

 
### Source of datasets:
https://github.com/MoH-Malaysia/covid19-public
