🔷 Advanced Python Testing – Deep Technical

Explain the difference between stub, mock, fake, and spy.

What is Test Isolation and why is it important?

What is dependency injection in tests?

What is flaky test? How do you fix it?

Difference between functional testing and non-functional testing?

What is mutation testing?

Explain boundary value analysis with example.

What is equivalence partitioning?

What is the difference between static testing and dynamic testing?

Explain white box techniques (branch coverage, path coverage)

🐍 Python-Specific Testing Questions

How do you test private methods in Python?

How do you test decorators?

How to test multithreaded code in Python?

How to test asynchronous code (async/await)?

What is monkeypatch in pytest?

What is parametrize in pytest and why is it useful?

How to test file IO operations in Python?

How to test time-based functions (datetime.now)?

What is patching in Python?

What is the difference between @patch and @patch.object?

💻 API & System Testing in Python

What is REST API testing?

Difference between PUT, POST, PATCH in API testing?

How to validate JSON schema in Python tests?

How do you verify headers and cookies in API testing?

How do you test authentication in APIs (JWT, OAuth)?

What is contract testing?

What are common API response codes?

How do you test rate-limiting in APIs?

What is GraphQL testing?

What is API versioning testing?

⚡ Performance & Security Testing

What is load testing vs stress testing?

What is spike testing?

What is endurance testing?

What is security testing in Python?

What is SQL injection testing?

What is vulnerability scanning?

What is penetration testing?

What is OWASP Top 10?

Explain XSS and CSRF vulnerability.

How do you test for broken authentication?

🧪 Automation Framework & CI/CD

What is a testing framework?

Types of testing frameworks (TDD, BDD, Hybrid, Data Driven)

Folder structure of a Python test framework

How to integrate tests in GitHub Actions?

How do you run tests automatically on every push?

Difference between Jenkins and GitHub Actions?

How to store test secrets safely?

What is Dockerized testing?

How to run tests in multiple environments?

What is parallel testing?

🧑‍💻 Practical Scenario-Based Testing

Write a test for a password validation function

Test file upload functionality

How to test payment gateway safely?

How do you test broken links?

Write negative test cases for login

How do you test email notifications?

How do you test CAPTCHA?

How do you test session expiration?

How to test browser compatibility?

How do you handle flaky Selenium tests?

🎯 Real Interview Scenario Questions

A test is failing but works on your machine. What do you do?

Developer says "works on my system". How do you respond?

How do you handle deadline + failing tests?

How do you convince a team to improve test coverage?

What metrics do you track in testing?

Difference between QA, Tester, and SDET

How do you prioritize test cases?

Difference between Smoke, Sanity & Regression

How to test microservices?

How to test distributed systems?

🧠 Behavioural (Testing-focused)

Tell me about a bug you found

How do you ensure product quality?

How do you handle conflicts with dev team?

What tools have you used for defect tracking?

How do you report a bug?

Why are you passionate about testing?

Why Python for automation?

What makes a good QA engineer?

What is your testing strategy for new project?

Where do you see yourself in 3 years (testing)?

🟢 Beginner-Level Python Testing Questions


What is software testing?


Why is testing important?


What is the difference between manual testing and automated testing?


What are unit tests in Python?


What is test case and test scenario?


What is debugging vs testing?


Explain black-box testing and white-box testing.


What is a bug / defect in software?


What is the difference between Verification and Validation?


What is the purpose of test documentation (test plan, test case, test report)?


Example answer (Q4)
A unit test is a type of testing where individual units (functions, methods, classes) of code are tested separately to verify that each part works correctly.

🟡 Intermediate Python Testing Questions


What is Python unittest?


Difference between unittest and pytest?


How do you write a basic test case in Python?


def add(x, y):
    return x + y

def test_add():
    assert add(2, 3) == 5



What are assertions in testing?


What is a test suite?


What is a test runner?


What is mocking in Python testing?


What is test coverage?


What is the difference between integration testing and system testing?


What is regression testing?


Example answer (Q17)
Mocking is used to simulate external services (APIs, DBs) so that we can test code without relying on real data or systems.

🔵 Advanced / Practical Python Testing Questions


What is pytest fixture?


Difference between @classmethod and @staticmethod in test classes?


What is TDD (Test Driven Development)?


Explain BDD with example (Behave / Cucumber style)


How do you test APIs in Python?


How do you test a database connection?


What is Selenium and how do you use it with Python?


What is CI/CD testing?


How do GitHub Actions help in automated testing?


How to test error handling in Python apps?


API Test example:

import requests

def test_api():
    response = requests.get("https://api.example.com/data")
    assert response.status_code == 200


🧠 Scenario-Based Testing Questions


How would you test a login page?


How would you test an e-commerce checkout?


Test a calculator app


Test a registration form


Test file upload and download


How do you test performance?


How do you test security?


How to test a broken API?


How to test edge cases?


Difference between positive and negative testing?



⚙️ Python + Automation Tools


Have you used Selenium with Python?


How do you locate elements in Selenium?


What is XPath?


Difference between ID, Class, Name in HTML for testing?


How do you handle wait in Selenium?


What is load testing? Have you used JMeter?


How will you automate a website using Python?






