# disaster_response_pipeline_Udacity
## Intructions
1. Required libraries:
    - Machine Learning Libraries: Numpy, Pandas, Sklearn
    - Natural Language Process Libraries: NLTK
    - SQLlite Database Libraries: SQLalchemy
    - Web App and Data Visualization: Flask, Plotly

2. Run the following commands in the project's root directory to set up your database and model.
    - To run ETL pipeline that cleans data and stores in database python data/process_data.py data/disaster_messages.csv data/disaster_categories.csv data/DisasterResponse.db
    - To run ML pipeline that trains classifier and saves python models/train_classifier.py data/DisasterResponse.db models/classifier.pkl

3. Run the following command in the app's directory to run your web app. python run.py

4. Go to http://0.0.0.0:3001/

## About the project
This project is part of the Udacity's Data Scientist Nanodegree program in collaboration with Figure Eight.

The project is about This project is about analyzing message data for disaster response. The data gotten from Figure Eight is used to builda model that classifies disaster messages and web app where an respondent can input a new message and get classification results in several categories.

## File description
- app
| - template
| |- master.html  # main page of web app
| |- go.html  # classification result page of web app
|- run.py  # Flask file that runs app

- data
|- disaster_categories.csv  # categories data to process 
|- disaster_messages.csv  # messages data to process
|- process_data.py        # cleaning the data
|- ETL Pipeline Preparation.ipynb    # notebook is same as the process_data.py

- models
|- train_classifier.py      #running this gives the model
|- ML Pipeline Preparation.ipynb  # notebook is same as the train_classifier.py   

- README.md

## Results


![1  main page](https://user-images.githubusercontent.com/104189092/197836163-599e1601-d0bf-4aed-8cf9-4249f11a5d85.png)

![2](https://user-images.githubusercontent.com/104189092/197836210-e7169aa2-95de-4943-9988-8a4e2585bb0d.png)
![3](https://user-images.githubusercontent.com/104189092/197836214-a0714d3e-3071-4a00-9f7d-87f084869cb2.png)
![4](https://user-images.githubusercontent.com/104189092/197836218-ec7195dd-4aec-49e6-b4e6-b37cda229be3.png)
