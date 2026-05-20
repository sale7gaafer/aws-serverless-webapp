![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=aws-lambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF4F8B?style=for-the-badge&logo=amazon-api-gateway&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazon-s3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)


##  Project Overview
This project demonstrates building a serverless web application using AWS services.

The application uses:
- AWS Lambda for backend processing
- API Gateway for API management
- Amazon S3 for static website hosting

Users can access a static website hosted on S3 and trigger a Lambda function through API Gateway.

---

##  Services Used
- AWS Lambda
- API Gateway
- Amazon S3
- IAM

---

##  Architecture
User → S3 Static Website → API Gateway → Lambda Function

---

##  Features
- Serverless architecture
- Static website hosting on S3
- API integration using API Gateway
- Backend processing with AWS Lambda
- Simple frontend connected to backend API

---

# 🔹 Lambda Function

- Created AWS Lambda function using Python
- Returned JSON response through API Gateway
- Backend logic executed serverlessly
  
<img width="941" height="329" alt="lambda" src="https://github.com/user-attachments/assets/9534692f-64fe-45b0-a250-f2640fbf771e" />
<img width="940" height="417" alt="lambda-code" src="https://github.com/user-attachments/assets/e573224b-87ed-43a0-8c87-79c7f51c9876" />

---

# 🔹 API Gateway

- Created HTTP API Gateway
- Configured GET route `/hello`
- Connected API Gateway with Lambda function
  
<img width="937" height="307" alt="api" src="https://github.com/user-attachments/assets/e1678be1-c612-4a26-bda3-d983aff75869" />
<img width="940" height="383" alt="api-route" src="https://github.com/user-attachments/assets/313f33cc-f3a1-424e-8306-20f1df4318db" />
<img width="934" height="381" alt="api-stage" src="https://github.com/user-attachments/assets/183233d7-0cff-4144-9e57-d1df8d41cd49" />
<img width="943" height="329" alt="api-cors" src="https://github.com/user-attachments/assets/11720f21-06dd-4234-b633-105caae1434d" />

---

# 🔹 API Response

- Successfully invoked Lambda through API Gateway
- API returned JSON response
  
<img width="947" height="384" alt="invoke-url" src="https://github.com/user-attachments/assets/6f3653af-2d80-4b31-93d3-8c4328c3b76d" />


---

# 🔹 S3 Static Website Hosting

- Created S3 bucket
- Enabled Static Website Hosting
- Uploaded frontend files

<img width="929" height="355" alt="static-website" src="https://github.com/user-attachments/assets/06781b9b-6e33-4edc-b85d-ee7af274726b" />
<img width="952" height="314" alt="s3" src="https://github.com/user-attachments/assets/22aea3b3-17d4-4173-b1af-87f74a53d8fe" />

---

# 🔹 Frontend Website

- Created simple HTML frontend
- Added button to call API Gateway endpoint
- Displayed Lambda response on webpage

<img width="778" height="373" alt="html" src="https://github.com/user-attachments/assets/6b4405dc-1a2e-4a56-a5ed-acd4576b0708" />
<img width="925" height="395" alt="website" src="https://github.com/user-attachments/assets/e92fe05f-fc9c-4ee1-8f2d-2678083213d7" />


---

# 🔹 Successful API Call

- Frontend successfully communicated with backend API
- Lambda response displayed on webpage

<img width="956" height="434" alt="wedsite2" src="https://github.com/user-attachments/assets/fde7ab85-3c1b-44d8-8f21-e7f06d66a8fe" />
