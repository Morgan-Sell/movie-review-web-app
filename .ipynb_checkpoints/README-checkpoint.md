


# Movie Review Sentiment Analysis

What sentiment does your critique project?

![Thank You](https://github.com/Morgan-Sell/movie-review-web-app/tree/master/images/enjoy_the_show.jpg)

## Usage
The user of this applications writes his/her review into the text box then select "Submit". A trained long short term memory (LSTM) model inform the user whether the sentiment of his/her critique is positive or negative. The image below is an example the application's response to a user's commentary of "Motherless Brooklyn."

![Web App](https://github.com/Morgan-Sell/movie-review-web-app/tree/master/images/web-app-sample.jpg)

The application is deployed using AWS API Gateway, Lambda, and SageMaker. 

![AWS Workflow](https://github.com/Morgan-Sell/movie-review-web-app/tree/master/images/aws_work_flow.png)

API Gateway provides the endpoint that receives the data provided by the user. Before being submitted to the LSTM model, the text is processed -  

## Model Design
The LSTM model was trained on 25,000 IMBd reviews, which were evently balanced positive and negative. The 
