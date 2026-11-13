This documentation serves as a comprehensive study guide and quick reference for three core AWS services: **Amazon SageMaker Ground Truth**, **AWS Lambda**, and the **Amazon SageMaker ML Platform**. 

## 📑 Table of Contents
1. AWS Lambda (Serverless Compute) 
2. Amazon SageMaker (ML Platform) 
3. Amazon SageMaker Ground Truth (Data Labeling)

## 1. AWS Lambda (Serverless Compute)

AWS Lambda is an event-driven, serverless compute service that lets you run code for virtually any type of application or backend service. 

### ⚡ Key Concepts
*   **Serverless:** AWS automatically manages the infrastructure, scaling, and patching. You focus purely on code.
*   **Event-Driven:** Executes in response to events from over 200 AWS services (e.g., S3 uploads, API Gateway requests, DynamoDB streams).
*   **Pay-Per-Use:** You pay only for the compute time you consume (measured in milliseconds).
*   **Limits & Performance:** Maximum execution timeout is **15 minutes**. Features *Provisioned Concurrency* to reduce "cold start" latency.

### Top Use Cases:

* Automated image/video processing upon S3 upload.
* Building scalable REST APIs with API Gateway.
* Scheduled cron jobs and automated infrastructure tasks.

### 2. Amazon SageMaker (ML Platform)

Amazon SageMaker is a fully managed service that removes the heavy lifting from each step of the machine learning process. It supports popular frameworks like TensorFlow, PyTorch, and Scikit-Learn.


### Key Features
1. **Fully Managed**: No need to manage EC2 instances for training or hosting.

2. **Built-in Algorithms**: Includes automatic model tuning (hyperparameter optimization).

3. **One-Click Deployment**: Easily deploy models to real-time prediction endpoints.

### Use Cases: Fraud detection, healthcare diagnostics, product recommendations, and sentiment analysis.

#### 3. Amazon SageMaker Ground Truth (Data Labeling)

Supervised learning models require accurately labeled data. Ground Truth helps organizations manage the complex process of data annotation efficiently and cost-effectively.


## Key Features
1. **Raw Data**: Upload unlabeled images, text, or documents.
2. **Human Labeling**: Create a labeling job with specific instructions.
3. **Active Learning**: SageMaker uses ML to auto-label easy data. Only ambiguous or uncertain data is sent to humans.
4. **Quality Control**: Collect and review completed labels, then store them in Amazon S3.

LinkedIn Link: https://www.linkedin.com/in/raj-kumar-giri-348763192/
