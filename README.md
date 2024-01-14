## Build and Deploy Sklearn model with Custom Script in Sagemaker

### Steps followed

1. Initialize Boto3 SDK and create S3 bucket. 
2. Upload data in Sagemaker Local Storage. 
3. Data Exploration and Understanding.
4. Split the data into Train/Test CSV File. 
5. Upload data into the S3 Bucket.
6. Create a Training Script
7. Train script inside Sagemaker container. 
8. Store Model Artifacts(model.tar.gz) into the S3 Bucket. 
9. Deploy Sagemaker Endpoint(API) for the trained model, and test it. 
