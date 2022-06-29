# Project 2: Hybrid Neural Network Recommender

### Project description

This project contains a recommender based on a neural network model. The goal is to achieve the best HR@10 in the final evaluation which is done with seed=6789.

<br>

### Project structure

Project contains 4 main folders:
- data (contains hotel data on which recommender is running)
- data_processing (contains 3 python files, where you can find methods meant to help manage the original data)
- evaluation_and_testing (contains 2 python files with testing and recommender evaluation)
- recommenders (contains 8 python files, all are different kinds of recommenders)

There are 2 ".ipynb" files which contains code execution and they are main part of the project

<br>

### Results

<b>The best achieved result is on model 2 and HR@10 = 0.236253</b>

<img src="best_result_model_2_with_only_one_hot_features.png">

<br>

### Requirements to run the project

1. Create (and activate) a new environment with Python 3.8.10

2. Install all the libraries with command below
 
    ```
     pip install -r requirements.txt
    ```

3. Start Jupyter Notebook and open files:

	- project_1_data_preparation.ipynb
    - project_2_recommender_and_evaluation.ipynb

<br>

This project was based on https://github.com/PiotrZiolo/recommender-systems-class.git repository, created by Piotr Zioło.