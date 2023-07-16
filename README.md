<h1 align="center"> Python </h1>
Basic python in jupyter notebook for Data Science and Data Engineering.

## DataFrame
DataFrame is a data structure that organizes data into a 2-dimensional table of rows and columns, much like a spreadsheet. The size of the dataframe is uncertain. Table data may be different.
Content | Description 
--- | --- 
1: Numpy | NumPy is a library for the Python programming, adding support for large, multi-dimensional arrays and matrices. This notebook shows using [NumPy manipulate vectors and matrices](https://github.com/ThanatPay/Python/blob/main/Pandas/1_Numpy.ipynb).
2: Pandas | Pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool. This notebook shows using [Pandas manipulate data](https://github.com/ThanatPay/Python/blob/main/Pandas/2_Pandas.ipynb). And example using Pandas manipulate Youtube Trending Data Exploration ([Basic](https://github.com/ThanatPay/Python/blob/main/Pandas/3_Pandas_(Data_Set_Trending_YouTube_Video_Statistics).ipynb) and [Advance](https://github.com/ThanatPay/Python/blob/main/Pandas/4_Advanced_Pandas_(Data_Set_Trending_YouTube_Video_Statistics).ipynb))

## Data cleaning and preparation
Data cleaning and preparation is the process of preparing data for analysis. This includes identifying and removing errors, filling in missing values, and dealing with outliers. Data preparation can be a time-consuming process (the most data scientists spend most of their time cleaning data), but it's important to make sure your data is accurate and ready for analysis.
Content | Description 
--- | --- 
1: Clean and prepare loans data | Loans data is columns that contain only one unique value. These columns aren't useful for the model. This notebook shows how to [clean and prepare loans data](https://github.com/ThanatPay/Python/blob/main/DataPreparation/1_LoansDataSet.ipynb).
2: Impute missing value | Missing values occur when no data value stored for some variables. Data may be lost due to incomplete data entry. Device malfunctions, lost files and other reasons. This notebook shows how to [impute missing value](https://github.com/ThanatPay/Python/blob/main/DataPreparation/2_ImputeMissingValue.ipynb).
3: Convert categorical to numeric variables | Categorical variables is variables that have one/more characteristic data that can’t be quantifiable. Categorical variables can be either nominal variables (cannot be compared) or ordinal variables (has an order relation). Machine Learning can not work on categorical variables in the form of strings, also need to convert it into numerical form. This notebook shows how to [convert categorical to numeric](https://github.com/ThanatPay/Python/blob/main/DataPreparation/3_ConvertCategoricalToNumeric.ipynb).
4: Detect and Remove the Outliers | Outliers are data points that deviate significantly from the majority of the other data points in a dataset. Outlier can occur due to various reasons, such as measurement errors, experimental anomalies, or rare events. This notebook shows how to detect and remove outlier ([Titanic Dataset](https://github.com/ThanatPay/Python/blob/main/DataPreparation/4_Outliers_Titanic.ipynb) and [Boston Dataset](https://github.com/ThanatPay/Python/blob/main/DataPreparation/5_Outliers_Boston_(optional).ipynb)).
5: Split train test  | Training set is a subset of a dataset that is used to train a machine learning model. Testing set is a subset of a dataset that is used to evaluate the performance of a trained machine learning model. This notebook shows how to [split train test](https://github.com/ThanatPay/Python/blob/main/DataPreparation/6_SplitTrainTest.ipynb).

## Maching Learning
Machine Learning (ML) is a subfield in AI focusing on understanding and building methods that let machines learn by itself without human intervention. Machine learning algorithms build a model based on sample data, known as training data, in order to make predictions or decisions without being explicitly programmed to do. Machine learning algorithms are used in applications such as medical, email filtering, speech recognition, computer vision.
Content | Description 
--- | --- 
1: Decision Trees (Random Forest) | Decision Trees (DT) is a decision support hierarchical model that used tree-like model. DT learn simple decision rules inferred from data features. Multiple decision trees are used for voting output to enhance decision making, known as Random Forest. This notebook shows example [Decision Trees](https://github.com/ThanatPay/Python/blob/main/MachineLearning/1_Decision_Trees.ipynb) and [Ramdom Forest](https://github.com/ThanatPay/Python/blob/main/MachineLearning/1_RandomForest(hed2020).ipynb).
2: Linear Regression | Linear regression is linear approach for modeling the relationship between one/more input variables and output variable(numerical data). This notebook shows [example linear regression](https://github.com/ThanatPay/Python/blob/main/MachineLearning/2_Linear_Regression.ipynb).
3: Logistic Regression | Logistic regression is statictic approach for modeling relationship between one/more input variables and output variable(category data). This notebook shows [exaple logistic regression](https://github.com/ThanatPay/Python/blob/main/MachineLearning/3_Logistic_Regression.ipynb).
4: Neural Network | Neural Networks (NN) are the heart of deep learning algorithms. Their name and structure are inspired by the human brain. NN are comprised an input layer, one or more hidden layers, and an output layer.  This notebook shows [example neural network](https://github.com/ThanatPay/Python/blob/main/MachineLearning/4_Neural_Network.ipynb).
5: K Nearest Neighbors| K-Nearest Neighbors (k-NN) is a non-parametric supervised learning method. Input consists of the k closest training examples in a data set. Output in k-NN classification is a class membership (plurality vote of k nearest neighbors). Output in k-NN regression is the property value for the object (average of the values of k nearest neighbors). This notebook shows [example K Nearest Neighbors](https://github.com/ThanatPay/Python/blob/main/MachineLearning/5_K_Nearest_Neighbors.ipynb).
6: Support Vector Machine | Support vector machines (SVMs) are supervised learning models. The purpose is to find hyperplane in an N-dimension space with maximum margin (maximum distance between the data points of both classes) to classify data. You can use multi-SVM for classify multi-class. This notebook shows [example SVM](https://github.com/ThanatPay/Python/blob/main/MachineLearning/6_Support_Vector_Machine.ipynb).
7: Save Load Model | Model progress can be saved during and after training. This means that the model can continue where it left off and avoid lengthy training times. Saving also means you can share your model with others or recreate your work when publishing models and research techniques. This notebook shows how to [save and load model](https://github.com/ThanatPay/Python/blob/main/MachineLearning/7_Save_Load_Model.ipynb).
8: K Mean Clustering | K-means clustering is a method that aims to partition n samples into k clusters. Each sample in clusters is nearest its centroid cluster. This notebook shows [example K mean clustering](https://github.com/ThanatPay/Python/blob/main/MachineLearning/8_K_Means_Clustering.ipynb).

## Deep Learning
Deep learning (DL) is a type of machine learning based on neural networks in which multiple layers of processing. DL are used to extract progressively higher level features from data. DL have been applied to fields including computer vision, speech recognition, natural language processing, etc.
Content | Description 
--- | --- 
1: Image Classification | Image classification is a task of computer vision that use model predict class of image. This notebook shows how to classify images of flowers ([Basic CNN model](https://github.com/ThanatPay/Python/blob/main/DeepLearning/1_Image_classification_(Basic).ipynb) and [EfficientNetB1 model with pre-train weight](https://github.com/ThanatPay/Python/blob/main/DeepLearning/2_FlowerClassification_EfficientNet_with_pretrained_weight.ipynb)).
2: Images Segmentation | Images Segmentation is a task of computer vision that use model locate objects and boundaries (lines, curves, etc.) in images. This notebook shows [example image segmentation](https://github.com/ThanatPay/Python/blob/main/DeepLearning/3_Segmentation_UNet.ipynb).
3: Time Series Forecasting| Time series forecasting is the process of analyzing time series data using statistics and modeling to make predictions and inform strategic decision-making. This notebook shows [example time series forecasting](https://github.com/ThanatPay/Python/blob/main/DeepLearning/4_StockPricePredication_LSTM.ipynb).

## Data Storage
A data store is a digital repository that stores information in computer systems. A data store can be network-connected storage, distributed cloud storage, a physical hard drive, or virtual storage. It can store both structured data (information tables) and unstructured data (emails, images, videos).
Content | Description 
--- | --- 
1: Redis | Redis (Remote Dictionary Server) is an in-memory data structure store with clustering, transactional, time-to-live limiting, and auto-failover capabilities. Support wide-range of data structure and many programing languages. This notebook shows [simple social network datastore example](https://github.com/ThanatPay/Python/blob/main/Redis/redis_simple_social_network_example.ipynb).

## Data Extraction
Data extraction is the process of collecting data from various sources for the purpose of transformation, storage, or feeding it to another system for analysis. The sources of data is extracted may be structured or unstructured. 2 steps of Data Extraction are Data Accessing (Reading a file, issue a HTTP request, crawing a web site using Scrappy, calling REST API using request, calling Third-Party API using compatible library) and Data Parsing (Parsing text using regular expression, Parsing docx using python-docx, Parsing excel using Pandas, Parsing HTML page using BeautifulSoup, Parsing JSON string using JSON)
Content | Description 
--- | --- 
1: BeautifulSoup | Beautiful Soup is a Python library for pulling data out of HTML and XML files. It works with parser to provide ways of navigating, searching, and modifying the parse tree. This notebook shows how to [get data from file HTML](https://github.com/ThanatPay/Python/blob/main/DataExtract/1_basic.ipynb) and [get data from wikipeidia page using requests](https://github.com/ThanatPay/Python/blob/main/DataExtract/2_wiki_extraction.ipynb).
2: REST API | REST API is a software architectural style that defines a set of principles for building web services. It provides a standardized way for different systems to communicate with each other over the internet. This notebook shows how to [get data from REST API](https://github.com/ThanatPay/Python/blob/main/DataExtract/3_rest_api.ipynb).
3: Third-party API | Third-party API is an API that is provided by a third-party service or platform. These APIs are developed by external parties and made available for others to use in their applications. This notebook shows How to [get data from Twitter API](https://github.com/ThanatPay/Python/blob/main/DataExtract/4_twitter_extraction.ipynb).
4: Selenium | The selenium package is used to automate web browser interaction from Python. This notebook shows how to [use Selenium to extract data from the web](https://github.com/ThanatPay/Python_notebook/blob/main/DataExtract/5_selenium.ipynb).

## Data Visualization
Data visualization is a process of finding trends and correlations in data by visual representation of data by visualizing data.
Content | Description 
--- | --- 
1: Visualization with python | To perform data visualization in python, we can use various python data visualization modules such as Matplotlib, Seaborn, Plotly, etc. This notebook shows how to [perform iris data visualization in python](https://github.com/ThanatPay/Python/blob/main/Visualization/simple_Matplotlib.ipynb).
