# scone_unlimited
this is a ML workflow used to classify vehicles and is built using Amazon Sagemaker.
<br />
In this project, I build an image classification model that can automatically detect which kind of vehicle delivery drivers have, in order to route them to the correct loading bay and orders. Assigning delivery professionals who have a bicycle to nearby orders and giving motorcyclists orders that are farther can help Scones Unlimited optimize their operations.
<br />
In order to do this, I used AWS Sagemaker to build an image classification model that can tell bicycles apart from motorcycles. Then i deployed the model, and used AWS Lambda functions to build supporting services, and AWS Step Functions to compose the model and services into an event-driven application. 
<br />
<br />
this project is divided by many steps:
- Step 1: Data staging
- Step 2: Model training and deployment
- Step 3: Lambdas and step function workflow
- Step 4: Testing and evaluation
- Step 5: Optional challenge
- Step 6: Cleanup cloud resources
