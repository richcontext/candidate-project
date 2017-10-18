# Candidate Project

No one enjoys the whiteboard based technical screening interviews. In those type of technical interviews, your test taking ability is graded rather than your actual ability as an engineer. This sample project is a quick way of working in your own space and time to show your abilities in a much more realistic work environment. 

# Backend

You will build a data collection system consisting of background workers along with a JSON API for client consumption. You can use whatever language and framework you feel most comfortable in, but bonus points for doing it with Python/Django/Celery.

Outline:

* Build background/async workers that run once an hour and collects tweets from Twitter's real-time random sample feed
* The workers should use an async job queueing system
* Store the tweets in a data store of your choice
* Build a REST API that produces JSON that exposes the collected twitter data 
* Ensure the REST API is sortable and filterable
* Deploy the application to a publicly accessible service. (Bonus: Deployed on AWS)
* Push your application to your fork of this project on Github
