# **Automation of Team Building Balancer Flutter WebApp**

This repository includes the automated tests for the Team Building Balancer Flutter WebApp. The tests focus on key user interactions, 
including onboarding, sign in, sign up, creating teams with skills, creating team without skills. The implementation also incorporates random email generator functions to handle sign up everytime with a new email.

## **Automated Test Cases**
**1. Registration Flow**
  - Automates the user onboarding and registration process, the sign up process with random email generation, sign up with valid email, sign up with existing email

**2. Sign In**
  - Automates the user login process, sign in with valid email, sign in with valid email and invalid password, verification for forgot password, sign in with valid email and password, sign in with invalid email and invalid password
Automates the user login process, including handling email verification through Mailinator.

**3. Sport Selection**
  - Automates the sport selection, sport selection and no teams or players added for error verification

**4. Team Creation With Skills**
  - Automates the login, sport selection and fills and the necessery fields

**5. Team Creation Without Skills**
  - Automates the login, sport selection without selecting skills

## Why These Test Cases?

These test cases were chosen because that's what was asked in the challange and it represents some of the core functionalities of the Team Buildin Flutter WebApp. 
Automating these flows ensures:

  - The integrity of the user authentication system.
  - A smooth user experience for new registrations.
  - The reliability of the platform.

## Page Object Model (POM) Implementation

The tests are implemented using the Page Object Model (POM) pattern, which includes:
  - A Base Class for shared methods and reusable logic, ensuring consistency and reducing code duplication.

## Test Data Generation
Test data for the automation was dynamically generated.
This ensures:
  - Realistic and unique test inputs for signups

## How to Run the Tests

  1. Installation
      - Navigate to https://www.devassure.io/
      - Login with email: usz88937@msssg.com and password: UnoDosTres123?
      - Download the IDE
  
  2. How to Run the Tests
     - Import the folder test into the IDE
     - Run the tests 
  
  3. How to See Reports
     - Reports are generated automatically after each run, if the test fails or if needed can be taken screenschots

## Conclusion
This project demonstrates the use of robuts automation practices to ensure the realiability of critical user flows on the Team Buildin Flutter WebApp. The inegration of the random email generator functions and the ose of POM showcases a modern approach to test automation.
