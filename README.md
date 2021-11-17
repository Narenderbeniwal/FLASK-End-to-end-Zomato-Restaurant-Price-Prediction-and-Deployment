

End-To-End Deployment of Zomato Restaurant Ratings


Main Objective:

The main agenda of this project is:

perform extensive Exploratory Data Analysis(EDA) on the Zomato Dataset

Build an appropriate Machine Learning Model that will help various Zomato Restaurants

to predict their respective Ratings based on certain features

DEPLOY the Machine learning model via Flask that can be used to make live predictions

of restaurants ratings


1





STEPS:

A. EDA and Model Building Part

\1. Load the dataset and perform the necessary EDA in your Jupyter notebook or google

colab

\2. Build your Machine learning algorithm and save your model using “pickle”

B. Deployment Part

\1. In this project we will be using “pycharm”, however, feel free to use any IDE that you are

conformable with (e.g you can use sublime text editor to achieve the same)

NOTE: There several ways of using Flask to deploy your application including creating a

virtual environment, which we will see in subsequent projects. In this project we will do it

right from our base environment

\2. Install your favourite IDE (e.g. pycharm) if not installed already.

Download pycharm IDE : https://www.jetbrains.com/pycharm/download/

\3. Setting up your Pycharm

• Create a new folder in your system and give it your preferred name (e.g. my\_project

)

• Open your pycharm IDE and click on file—>open—>{select the folder you created}

2





\4. Optional (but recommended)

A. You can create a virtual environment to avoid any conflict in library dependencies

(recommended) follow below links to create a virtual environment:

https://bit.ly/2CwnTfo

https://bit.ly/32pe8uL

B. You can work with your base environment if you have the required libraries

installed

\5. Specifically, install Flask:

Use: pip install flask

OR follow this link: https://bit.ly/32pe8uL

\6. Files you will need:

• Model.py file

• .csv file

• template

• .html file

• .css file

• app.py file

3





File Descriptions

Model.py:

This file contains the code for building our model that is used in predicting the restaurant

ratings

csv file:

This contains our data that we have already cleaned and saved

template file:

The template file contains the html and css documents used in building our web app

App.py:

This contains the Flask API’s that receives restaurant details via a GUI/API calls, then make

the prediction of restaurant ratings based on our model and returns the rate.

4





\4. Creating your files

A. Create a new python file and name it app.y

{your home folder}—>New—>Python file

B. Create a template folder (for html)

{your home folder}—>New—>Directory(name it as templates)

5





C. Create an HTML file:

templates—>New—>HTML file

D.

Create a static folder (for css)

{your home folder}—>New—>Directory(name it as static)

6





E. Create a css file:

static—>New—>css file

F. Start creating the contents of each file following the video

7

