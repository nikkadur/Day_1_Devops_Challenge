# Day_1_Devops_Challenge/ Weatherdashboard
![Untitled Diagram drawio (1)](https://github.com/user-attachments/assets/7d2a2b76-f9b5-4786-b528-1be87b24cbbf)

Today was the day 1 of Devops Challenge which included making a WeatherApp Dashboard using Openweather  app API and store the data in the AWS S3 Bucket.

# Prequisites for the project

* Version Control System - Git
* Cloud Storage - S3
* Programming Language - Python
* Coding Environment - Visual Studio Code
* External API : Openweather API
* Dependencies:
   1 boto3 (AWS SDK)
   2 python-dotenv
   3 requests

# Features 

* It will fetch the real time data for multiple cities using the Openweather API
* Display temperateure humidity and weather conditions
* Stores the already fetched data and stores it in AWS S3 Bucket
* Since the data is stored in S3 bucket, helps in maintaing historical data of the same

## Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt

## Setup Instructions
1. Clone the repository:
--bash


3. Install dependencies:
bashCopypip install -r requirements.txt

4. Configure environment variables (.env):
CopyOPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

4.Configure AWS credentials:
bashCopyaws configure

5. Run the application:
python src/weather_dashboard.py

What I Learned

AWS S3 bucket creation and management
Environment variable management for secure API keys
Python best practices for API integration
Git workflow for project development
Error handling in distributed systems
Cloud resource management

Future Enhancements

Add weather forecasting
Implement data visualization
Add more cities
Create automated testing
Set up CI/CD pipeline
. 



