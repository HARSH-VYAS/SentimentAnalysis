# SentimentAnalysis Web App Using PyTorch and SageMaker

Our goal will be to have a simple web page which a user can use to enter a movie review. The web page will then send the review off to our deployed model which will predict the sentiment of the entered review.
 
# General Outline

 1. Download or otherwise retrieve the data.
 2. Process / Prepare the data.
 3. Upload the processed data to S3.
 4. Train a chosen model.
 5. Test the trained model (typically using a batch transform job).
 6. Deploy the trained model.
 7. Use the deployed model.

For this project I have used Amazon Sage Maker, Pytorch and created my own Training model. Deployed it using Sagemaker, created a lambda function and Amazon API Gateway to access the data sent from the UI page.
