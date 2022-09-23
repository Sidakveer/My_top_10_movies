# My_top_10_movies

<br>

## Introduction
### In this repository we have created a wesite which uses:
* Flask_SQLAlchemy to work with a sqlite3 database.
* Python's resquests module to work with API's
* FlaskForms to create forms which can be filled by the users.
* Boostrap with the help of Jinja Templating
* WTForms to create quick flask form
* Html and CSS to create and style our website pages.
* Flask web framework to build our project
<br>

<br>

## Description
### **>** Here we have created a website which helps users to build their unique personal website which can store the top 10 favourite movies or more if needed as we are using a sqlite database.
<img src="images/final.png" width=700 height=450>

<br>

## Simulation / Steps of how the website works

### **1** We start with one movie added to our database which shows on the homepage(/home) of our website.
<img src="images/1.png" width=700 height=450>


<br>

### **2** The add movie button sends an APi request to retirive a set of movies which based on the title passed by the user.
<img src="images/2.png" width=1000 height=250>

<br>

### **3** Selecting a movie from the list creates a new movie_id for it in the database and ask us for our input next.
<img src="images/3.png" width=1200 height=500>

<br>

### **4** Fill the review form which uses the movie_id to add to our databse.
<img src="images/4.png" width=700 height=250>

<br>

### **5** Finally we have the new movie displayed and added in order based on the rating provided by the user previously
<img src="images/5.png" width=600 height=450>


<br>

### **6** Whenever we hower over our movie card the card displays information about the particular movie it represents and the rating and review can be edited or the entire card can be deleted from the database if the user wishes to click on the respective buttons.
<img src="images/6.png" width=600 height=450>

