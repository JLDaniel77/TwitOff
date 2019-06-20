# TwitOff

A web application that takes a text string, and determines who is most likely to 
tweet the text by comparing the tweets of two Twitter users. This application was
created using the Python library Flask-SQLAlchemy. It collects tweets from the 
Twitter API, stores the data in a PostgreSQL database, and is deployed on Heroku.
The tweets are converted to embedding vectors using Basilica.ai, which is then
used to run a logistic regression. The model is then used to predict the probability
of a text string belonging to one of two Twitter users, and outputs the username with
the highest probability.

**Application link:** https://jldaniel77-twitoff.herokuapp.com/
