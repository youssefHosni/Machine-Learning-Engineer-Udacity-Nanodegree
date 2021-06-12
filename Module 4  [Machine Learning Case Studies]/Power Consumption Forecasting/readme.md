Energy Consumption Data
The data we'll be working with in this notebook is data about household electric power consumption, over the globe. The dataset is originally taken from Kaggle, and represents power consumption collected over several years from 2006 to 2010. With such a large dataset, we can aim to predict over long periods of time, over days, weeks or months of time. Predicting energy consumption can be a useful task for a variety of reasons including determining seasonal prices for power consumption and efficiently delivering power to people, according to their predicted usage.

Interesting read: An inversely-related project, recently done by Google and DeepMind, uses machine learning to predict the generation of power by wind turbines and efficiently deliver power to the grid. You can read about that research, in this post.

Notebook Outline 
* Loading and exploring the data
* Creating training and test sets of time series
* Formatting data as JSON files and uploading to S3
* Instantiating and training a DeepAR estimator
* Deploying a model and creating a predictor
* Evaluating the predictor
