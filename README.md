# Scalable TweetMap

Scalable TweetMap is a twitter Sentiment analysis application that plots the tweets on global map to create a heat map. This application is designed to be truely scalable, and is hosted on AWS beanstalk.

# Technology Used
- AWS Elastic BeanStalk: Webapp is hosted on BeanStalk
- Elastic Search: To improve efficiency of searching stored tweets based on keywords.
- Amazon SQS: Amazon's Queuing service to store the streamed tweets to make them available for consumption
- Amazon SNS: Notification Service to notify the subscriber of new tweets.
- Google Map API: To Plot the tweets on map and cluster them.
- Backend - Python 3.5 based on Django 1.9 framework
