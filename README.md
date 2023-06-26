# Cardiovascular Disease Prediction

A project that makes a data analysis and creates a model for classification of cardiovascular disease.

## Dataset Information

<div align='center'>
    <img alt='cardiovascular-disease' src='https://www.maxlab.co.in/category/1668233331.jpg' width='100%' height='400'>
</div>

<br>

This dataset was published on the Kaggle competition platform. For more information it can be seen accessing this [link](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset).

## Project Structure

The project repository is structured as follows:


- database
    - cardio.csv
    - cardio_test.csv

- notebook
    - Heart_Disese.ipynb

- README.md


1. Database directory contains the datasets for training and test the model.
1. Notebook directory contains the .ipynb file where all the data science pipelines performed form analyzing the data to final results.

## Business performance

- What is the accuracy and precision of the model?
    - Accuracy : 0.714
    - Precision : 0.733

- How much profit will healthcare company have with the new tool?
    - The profit using the model is $11,285,500

### Attributes

1. Age | Objective Feature | age | int (days)
1. Height | Objective Feature | height | int (cm) |
1. Weight | Objective Feature | weight | float (kg) |
1. Gender | Objective Feature | gender | categorical code |
1. Systolic blood pressure | Examination Feature | ap_hi | int |
1. Diastolic blood pressure | Examination Feature | ap_lo | int |
1. Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal |
1. Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal |
1. Smoking | Subjective Feature | smoke | binary |
1. Alcohol intake | Subjective Feature | alco | binary |
1. Physical activity | Subjective Feature | active | binary |
1. Presence or absence of cardiovascular disease | Target Variable | cardio | binary |

All of the dataset values were collected at the moment of medical examination. 

## Context

A healthcare company that specializes in detecting heart disease in the early stages. Its business model is service type, that is, the company offers an early diagnosis of cardiovascular disease for a certain price.
 
Currently, the diagnosis of cardiovascular disease is made manually by a team of specialists. The current accuracy of the diagnosis varies between 55% and 65%, due to the complexity of the diagnosis and also the fatigue of the team who take turns to minimize the risks. The cost of each diagnosis, including equipment and analysts' payroll, is around $ 1,000.00.

The price of the diagnosis, paid by the client, varies according to the precision achieved by the team of specialists, the client pays R$ 500.00 for every 5% accuracy above 50%. For example, for an accuracy of 55%, the diagnosis costs R$ 500.00 for the client, for an accuracy of 60%, the value is R$ 1000.00 and so on. If the diagnostic accuracy is 50%, the customer does not pay for it.

### Objective

As a Data Scientist, objective is to create a tool that increases the accuracy of the diagnosis and that this accuracy is stable for all diagnosis.

### Pipeline

* Opening

* Data Descriptions

* Feature Engineering

* Data Exploration

* Filtering Variables

* Exploratory Data Analysis

* Data Preparation

* Feature Selection

* Machine Learning Modeling

* Hyperparameter Fine Tuning

* Traduction and Error's Interpretation

* Deploy

## Reporting Issues

If you encounter any issues or have any suggestions regarding the project, feel free to open an issue in the project repository.

## Contribution Guidelines

Contributions to this project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.

1. Create a new branch for your feature or bug fix.

1. Commit your changes and push the branch to your fork.

1. Submit a pull request to the main repository.

1. Please ensure that your contributions align with the project's coding style and follow the best practices of data science.

## Contact Information

For any additional information or inquiries, please go to my profile and send a mail.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Reference

- Dataset : https://www.kaggle.com/sulianova/cardiovascular-disease-dataset 
- Image   : http://surl.li/ijwwo

## Happy analyzing!

We hope you find this project insightful and informative! Happy analyzing!