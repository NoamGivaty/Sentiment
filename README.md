# Sentiment

# Twitter tweets sentiment analysis (using NLP) 
Asynchronous pipeline project that using reactive programming to process tweets
in real time and analyze the sentiment of the tweets using NLP.

## Use case
Analyze the sentiment of tweets that are related 
to a specific keyword (topic), or filtered by a specific keywords for example -
3 names of companies in order to compare the sentiment of the tweets about them, 
and check what the public opinion about them.

## Technologies and tools
* Backend - Java, **Spring Boot**, **Spring WebFlux** (reactive programming),
* Database - **Redis**
* Message broker - **Kafka** (using Spring Kafka)
  - In order to handle fast and big streams of data.
* **Docker** 
    - For running kafka and redis containers
* Third party API - Twitter API - twitter4j.
* NLP - Stanford CoreNLP library
