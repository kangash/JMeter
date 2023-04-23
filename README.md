# Performance testing
![JMeter logo](https://img.shields.io/badge/JMeter-090909?style=for-the-badge&logo=apachejmeter)

Here you can find solutions to tasks confirming my experience in performance testing using JMeter.

---

### Task 1:

Create 3 load profiles and write tests for each of them.

### 1.1 

Load Profile 1: 10 users send requests for 10 seconds.

Operational Profile 1: Unregistered users open the main pages of the application.

Task: write 5 tests to verify that Home, About Us, Blog, Contacts, Login pages load for 3 seconds and return status code 200. 

### 1.2

Load Profile 2: 5 users send requests within 60 seconds.

Operational profile 2: An unregistered user posts random comments to one of the posts.

Task: Write a test that checks adding a random comment by a random user.  The test should check that the status code is 200 and the response time is less than 7 seconds.

### 1.3

Load Profile 3: 5 users send requests for 60 seconds.

Operational Profile 3: A registered user posts random comments to one of the posts.

Task: Write a test that checks if a registered user adds a random comment. The test should check that the status code is 200 and the response time is less than 7 seconds.

### 1.4

Task: Using Profiles 3, write a test that will add a new post. The test should check that the status code is 200 and the response time is less than 7 seconds.