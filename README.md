# Flexmoney-Assignment
An application for registration and management of yoga classes
# Description
I have built a **highly scalabe ,reliable, consistent and durable** application using which satisfies the given requirements. **Redundancy is avoided** by making two tables for form and payment respectively related to each other. So that when a user will attend yoga classes for mutiple months only the payment table and one coumn in user info that is Batch-timing will be updated. SO there will be only one row in Yoga form table and multiple rows corresponding to each payment in the payments table. This prevents storing the user information(Name, Age) multiple times for each month spearately which will save a lot of memory when used at high scale. I have used **Django models i.e MySQL data base which has ACID properties necessary for financial transactions**. I have not used NO-SQL databases like MongoDB because they are not consistent on a high scale due to sharding as we were told to **build a highle scalable solution. Django and react are used for backend and frontend respectively.**
# ER diagram
<img width="711" alt="ER_diagram" src="https://user-images.githubusercontent.com/54476451/207395661-6c9ceb2b-8a48-4639-b5a6-c29f81affe95.png">

# Setup Instructions

Clone the repository

Install requirements
```bash
pip install -r requirements.txt
```
### Start Web Server

Run the django web server.
```bash
python manage.py runserver
```


# Install Node Modules
```bash
cd frontend
```
Next install all dependicies.
```bash
npm i
```
