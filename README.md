

<a href="https://movie-rec-n-sen-analysis.herokuapp.com/" ><img src="./static/intro.jpg" height=400 width=1500 ></a>

## Table of Contents
* [Technologies](#technologies)
* [General info](#general-info)
* [Sources of the datasets](#sources-of-the-datasets)
* [Screenshots](#screenshots)



## Technologies

![Python](https://img.shields.io/badge/-Python-ffff00?style=flat&logo=python&labelColor=f2f2f2)<br>
![Flask](https://img.shields.io/badge/-Flask-b3ffe6?style=flat&logo=flask&labelColor=gray)<br>
![HTML](https://img.shields.io/badge/-HTML-00ff00?style=flat&logo=HTML5&labelColor=3333ff)<br>
![CSS](https://img.shields.io/badge/-CSS-d2ff4d?style=flat&logo=CSS3&labelColor=944dff)<br>
![JavaScript](https://img.shields.io/badge/-JavaScript-ff4000?style=flat&logo=javascript&labelColor=333333)<br>
![The Movie Database](https://img.shields.io/badge/-The%20Movie%20Database-1a1aff?style=flat&labelColor=d9d9d9&logo=The%20Movie%20DataBase)


## General info

* **How to get the API key?**

   Create an account in https://www.themoviedb.org/, click on the `API` link from the left hand sidebar in your account settings and fill all the details to apply for API        key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your `API` sidebar once your request is approved.

* **How to run the project?**

   1. Install all the libraries mentioned in the [requirements.txt](https://github.com/kishan0725/Movie-Recommendation-System-with-Sentiment-                           Analysis/blob/master/requirements.txt) file.
   2. Clone this repository in your local system.
   3. Replace YOUR_API_KEY in the `static/recommend.js` file.
   4. Open the command prompt from your project directory and run the command `python main.py`.
   5. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
   6. Hurray! That's it.

* **Similarity Score** 

   How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   
* **How Cosine Similarity works?**
   Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two          vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance       (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
     <p align="center">
         <img src="https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png" />
    </p>
  

  
   More about Cosine Similarity : [Understanding the Math behind Cosine Similarity](https://www.machinelearningplus.com/nlp/cosine-similarity/)

### Sources of the datasets 

1. [IMDB 5000 Movie Dataset](https://www.kaggle.com/carolzhangdc/imdb-5000-movie-dataset)
2. [The Movies Dataset](https://www.kaggle.com/rounakbanik/the-movies-dataset)
3. [List of movies in 2018](https://en.wikipedia.org/wiki/List_of_American_films_of_2018)
4. [List of movies in 2019](https://en.wikipedia.org/wiki/List_of_American_films_of_2019)
5. [List of movies in 2020](https://en.wikipedia.org/wiki/List_of_American_films_of_2020)


### Screenshots
![Home page](./static/screenshorts/home.PNG)
![Home page](./static/screenshorts/recommendation1.PNG)
![Home page](./static/screenshorts/recommendation2.PNG)
![Home page](./static/screenshorts/recommendation3.PNG)
![Home page](./static/screenshorts/recommendation4.PNG)
![Home page](./static/screenshorts/recommendation5.PNG)
![Home page](./static/screenshorts/recommendation6.PNG)



