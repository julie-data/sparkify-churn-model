
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3. You would need to instantiate a Spark session, but the code is included in the Jupyter notebook.

The code is using the following libraries: numpy, pandas, matplotlib, pyspark, sklearn and seaborn.

## Project Motivation<a name="motivation"></a>

The goal of this project is to predict the customers who have churned from a music streaming plaform. I work on a subset of a dataset containing all the actions users have performed on a fictive music streaming platform during two months. The dataset contains 278154 records for 225 users.

My goal is to identify the customers who churned. I can recognize them by looking at the customers who have cancelled their subscription and therefore ended up on the page "Cancellation Confirmed". I will measure the performance of our model based on the F1 score, which takes into account both precision and recall. Given that the churned customers represent only 23% of our dataset, this will give me a better representation of how well our model is predicting which customers did or did not churn.

You can consult this full Medium post in order to have more information about the project and its realisation: https://medium.com/@julietrinco/should-i-stay-or-should-i-go-predicting-customer-churn-on-a-music-streaming-platform-26e636b6f221 (DRAF LINK TO CHANGE).

## File Descriptions <a name="files"></a>

The file contains a Jupyter notebook and the dataset.

1. mini_sparkify_event_data.json: This is the dataset used throughout the notebook. This is a subset of the full dataset in order to be able to work on a local machine. The dataset contains one row for each event on the streaming platform.

2.sparkify-churn-notebook.ipynb: This notebook contains all the steps of the project. It first loads the data, cleans it, explore it, creates the required features through features engineering and finally create a model to predict the customers who churned from the streaming platform.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@julietrinco/should-i-stay-or-should-i-go-predicting-customer-churn-on-a-music-streaming-platform-26e636b6f221).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Thank you first to Insight Data Science for creating this project and enabled me to learn how to code in Spark (https://www.insightdatascience.com/). Second, I would like to acknowledge Udacity for their great Data Scientist nanodegree of which this project is part of. Finally, I would like to thank Nicolas Essipova, my mentor for this Data Scientist nanodegree who have helped me out throughout this project.
