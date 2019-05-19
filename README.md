# MyExamScribe

MyExamScribe is an effort to address and combat issues related to availability of reliable scribes for visually impaired and handicapped people during examinations. 

This application, built on top of Google assistant, is capable of interacting with the user by reading instructions and questions, storing answers, marking questions for review, etc. Its reliability and ease of usability can make it a possible replacement for human scribes.

## Technologies

![](/screenshots/flow.png)

* **Dialogflow aka api.ai (Google assistant)** 

NLP based machine learning model to train different user intents (read question, write answer etc).

![](/screenshots/Dialogflow.png)

* **Firebase cloud database**

NoSQL database to store question paper and candidate's responses.

![](/screenshots/Database.png)

* **Node.js Server** 

Webhook (HTTP endpoint) to serve intents and fetch/mutate data from database.

![](/screenshots/code.png)



## Functionality 
