

End-To-End Deployment of Zomato Restaurant Ratings

![image](https://user-images.githubusercontent.com/68732948/142344924-70ec021d-6ed9-4066-8a38-b8a89eaa0201.png)

Main Objective:

The main agenda of this project is:

>Perform Extensive Exploratory Data Analysis(EDA) on the Zomato Dataset

>Build an appropriate Machine Learning Model that will help various Zomato Restaurants

>To predict their respective Ratings based on certain features

>DEPLOY the Machine learning model via Flask that can be used to make live predictions of restaurants ratings


1





STEPS:

A. EDA and Model Building Part

1. Load the dataset and perform the necessary EDA in your Jupyter notebook or google

colab

2. Build your Machine learning algorithm and save your model using “pickle”

B. Deployment Part

1. In this project we are using “pycharm”, however, feel free to use any IDE that you are

conformable with (e.g you can use sublime text editor to achieve the same)

2. Install your favourite IDE (e.g. pycharm) if not installed already.

Download pycharm IDE : https://www.jetbrains.com/pycharm/download/

3. Setting up your Pycharm

• Create a new folder in your system and give it your preferred name (e.g. my\_project)

• Open your pycharm IDE and click on file—>open—>{select the folder you created}
![image](https://user-images.githubusercontent.com/68732948/142345327-e52868d3-cf72-47ea-8106-a9c901a28276.png)



4. Optional (but recommended)

  A. You can create a virtual environment to avoid any conflict in library dependencies

(recommended) follow below links to create a virtual environment:

https://bit.ly/2CwnTfo

https://bit.ly/32pe8uL

   B. You can work with your base environment if you have the required libraries

installed

5. Specifically, install Flask:

 Use: pip install flask or use can cretae the requerement.txt file 
 and then install it 



6. Files we are using in this project:

• Model.py file

• .csv file

• template

• .html file

• .css file

• app.py file


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


4. Creating your files

A. Create a new python file and name it app.y

{your home folder}—>New—>Python file
![image](https://user-images.githubusercontent.com/68732948/142345664-b0f1db37-e009-4a93-a420-e57e7912d2b3.png)


B. Create a template folder (for html)

{your home folder}—>New—>Directory(name it as templates)
![image](https://user-images.githubusercontent.com/68732948/142345678-2513765e-84c9-42d9-ad75-7bbde3561996.png)


C. Create an HTML file:

templates—>New—>HTML file
![image](https://user-images.githubusercontent.com/68732948/142345702-47e254d8-3abf-43ff-9045-e556feb8405c.png)


D.

Create a static folder (for css)

{your home folder}—>New—>Directory(name it as static)
![image](https://user-images.githubusercontent.com/68732948/142345745-91a5a22c-5771-4ae3-812e-9f924a11b31d.png)




E. Create a css file:

static—>New—>css file
![image](https://user-images.githubusercontent.com/68732948/142345786-20ef0da3-f0d3-402a-ab18-cc8e3c2cfdc5.png)

static—>New—>css file

