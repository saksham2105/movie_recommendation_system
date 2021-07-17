# Flask Based Movie recommendation system
> https://moviercmdsystem.herokuapp.com

![GitHub stars](https://img.shields.io/github/stars/saksham2105/movie_recommendation_system) 
[![Maintenance](https://img.shields.io/badge/maintained-yes-green.svg)](https://github.com/saksham2105/movie_recommendation_system/commits/master)
[![Website shields.io](https://img.shields.io/badge/website-up-yellow)]()

### Website Preview
#### Home Page
<img src="mrs-2.png" width="900">

#### Detail Page
<img src="mrs-1.png" width="900">

----

## Installation 📦

>pip install -r requirements.txt

#### Clone

- Clone this repo to your local machine.

#### Run server locally

```shell
$ python app.py
```
> Go to localhost:portNumber

---
## Features 📋
* User can Search and get results on each key Press.
* User can search through various movies and look through its details.
* User will get movies based on searching genre,cast,rating of movie etc. (Recommendation algorithm (Collaborative Filtering) which suggests new movies based on conditions mentioned.)
---

## Algorithm
##### Collabortive Filtering (Recommender Algorithm)
* Collaborative filtering filters information by using the interactions and data collected by the system from other users. It's based on the idea that people who agreed in their evaluation of certain items are likely to agree again in the future.
* When we want to find a new movie to watch we'll often ask our friends for recommendations. Naturally, we have greater trust in the recommendations from friends who share tastes similar to our own.
* Collaborative-filtering systems focus on the relationship between users and items. The similarity of items is determined by the similarity of the ratings of those items by the users who have rated both items.
* There are two types of collaborative filtering
    * **User-based**, which measures the similarity between target users and other users.
    * **Item-based**, which measures the similarity between the items that target users rate or interact with and other items.
    > I have used **user based** collaborative filtering in this project.
     
