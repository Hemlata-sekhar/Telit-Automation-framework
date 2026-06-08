# Telit Automation Framework
This project is a Java-based Selenium Test Automation Framework. The framework is designed using UI Test Automation Cross-browser execution Cloud execution using LambdaTest.

Headless execution Data-driven testing Logging and reporting CI/CD integration using Jenkins.




## 🚀 About Me
Hi ,My name is Hemlata and i have 4+ years of experience in Automation Testing using technologies like Selenium Webdriver,ResAssured, Postman And Playwright.
My Measure expertize is in Java Programming Language and SQl .


## Author

- [Hemlata-sekhar](https://github.com/Hemlata-sekhar)
-EmailAddress:hemasekhar8920@gmail.com

## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/Hemlata-sekhar)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hemlata-na-5a47072bb/?skipRedirect=true)



## Prerequisites
Before running the project ensure the following are installed:

- **Java 21**
- **Maven**
- Git
- IDE (IntelliJ / Eclipse)
Chrome/Firefox/Edge Browser

Verify installation:

java -version
mvn -version


## Framework Features
-**Cross Browser Testing**
-The framework supports headless mode.
-**cloud-based execution**.
-Tests can be executed on LambdaTest cloud infrastructure.
-** data Driven Testing**
-**Reporting**
-Execution logs are generated using Log4j.
-**CLI execution**
Jenkins execution



## Tech Stack used
-Java 21	
-Selenium WebDriver
-TestNg
-Maven
-OpenCSV
-Apache POI	
-Java Faker
-Extent Reports	
-Log4j
-LambdaTest	
-Jenkins



## Setup Installation

 **Clone the Repository**

```bash
 git clone https://github.com/Hemlata-sekhar/Telit-Automation-framework.git

 cd Telit-Automation-framework
```


 **LambdaTest Cloud Execution** 
 ```bash
mvn test -Dbrowser=chrome -DisLambdaTest=true -DisHeadless=false -X
```


**Local machine Headless Execution** 
 ```bash
-mvn test -Dbrowser=chrome -DisLambdaTest=false -DisHeadless=true -X
```

**Test Reports Logs**
 ## After execution Extent Reports are generated at:
./reports.index.html
Open the HTML report in browser to view:
Test Summary
Pass/Fail Status
Screenshots
Execution Logs
-Execution logs are available under:
/logs/

## GitHub Actions
This framework is integrated with github actions.
