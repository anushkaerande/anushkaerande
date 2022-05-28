# DHUN	
 ![readme](https://user-images.githubusercontent.com/99139073/170812522-6e74eb4b-3bf9-48cc-8156-e02b96946576.jpeg)

## Purpose
In today's world where everyone is striving for achievement, but many people are succumbing to depression as a result of this struggle. Making a few poor decisions occasionally. As a result, **DHUN** was designed to assist people in de-stressing by recommending movies and songs based on their feelings and can be also used for entertainment purpose.

## What it does
**DHUN** is a facial expression recognition-based movie and music suggestion website that cheer up users and saves time while searching for a movie or song that matches their mood.
1. It recognizes facial expression based on the 6 categories i.e., angry, sad, fear, happy, surprise and neutral.
2. Based on the emotion it gives user two choices  either suggesting movies or songs.
3. If user wishes to watch movies/songs then a list of movies/songs matching their mood are suggested with movie/songs poster.
4. When user clicks on movie which he wishes to watch, they will be redirected to IMDB website and for songs it redirects them to Spotify website.

## How I built it
Python is the programming language used to create the emotion recognition model and deploy it on the web application using flask. CV2, TensorFlow, NumPy, matplotlib, keras and other libraries are also utilized. This model is deployed on a website created with HTML and CSS using the flask framework. The model is build using the transfer learning approach for which MobileNet model is used. The FER-2013 dataset, which comprises around 28000 photos, was utilized for model training and testing.  Based on the six emotions, a new dataset of movies and music was constructed. The data from movies and songs was utilized to create the various templates that correlate to various emotions.For creating templates HTML and CSS are being used.

## Challenges I ran into
 It was a challenging task to get the website to access 6 movie templates from the movies button and 6 song templates from the songs button based on the emotion recognized. Dynamic links were used as a means to access the templates for movies/songs corresponding to the output of the model.Training the model to get good accuracy.

## What I learned
We learnt about the transfer learning approach for the model, which assisted us in face identification, as well as how to develop basic web pages using HTML, CSS and how to deploy the model on the web using flask. Learnt a great deal about Python and different frameworks such as flask and its integration, many new libraries in Python. 

## How to run the app
Download all the files from github. Make sure you have a good internet connection. Then type folder location in anaconda prompt and open jupyter notebook. Then open the file app.ipynb in jupyter notebook. After that run the ipynb file. In output you will get a link where I have deployed my app. Click on the link which would be off localhostand you will be directed to website. Then click on lets start within seconds  a camera window will appear in taskbar, it will detect your mood direct you to new page. here you will get an option of movies and songs click on any one and respected page would occur according to mood. Click on poster of whichever movie/song you want and it will direct you to imdb or spotify page respectively.

## What's next for **DHUN**
The next step is to improve the model's accuracy and to build a AI bot which could actually talk with humans regarding their mental state or with whom humans could share their feelings so that the bot helps to give them solutions.
