# Day_1_Devops_Challenge/ Weatherdashboard

 
![Untitled Diagram drawio (1)](https://github.com/user-attachments/assets/7d2a2b76-f9b5-4786-b528-1be87b24cbbf)


Today was the day 1 of Devops Challenge of CodeCrew which included making a WeatherApp Dashboard using Openweather  app API and store the data in the AWS S3 Bucket.

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
```bash
 -- weather-dashboard/
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
```bash
   git clone https://github.com/nikkadur/Day_1_Devops_Challenge.git

3. Install dependencies:
```bash
  Copypip install -r requirements.txt

4. Configure environment variables (.env):
```bash
OPENWEATHER_API_KEY=your_api_key
AWS_BUCKET_NAME=your_bucket_name

4.Configure AWS credentials:
```bash
aws configure

5. Run the application:
python src/weather_dashboard.py

6. Output of the Application
   Visit your S3 bucket and you will be able to see there would be two Buckets present in the region.

7. Post the changes in your local environment to your github repository
    use git push and your remote repository will have the changes same as your local repository.
   
```
What I Learned

* AWS S3 bucket creation and management
* How important API keys are to communicate with the application and to store them in a secure way since they are sensitive.
* Python best practices to place environment variable
* what should be placed in a gitignore file
* Error handling in distributed systems
* To collaborate with other people if you are stuck somewhere (Sometimes, Google or chatgpt does not have all the answers)
* Cloud resource management.

It was a great start to Day 1 of the challenge looking forward for more such challenges !


. 



