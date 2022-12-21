
# DemoQA Application Project Tests

# Goal of the project

1. crated a framework that can be run through terminal and create a nice HTML report
2. Practice core components of request and response in API Testing

### pom.xml file
* which dependencies we need?
  - RestAssured
  - cucumber -java
  - cucumber-junit
  - Object Mapper (Jackson, GSON)
  - Selenium, Boni-Garcia (No need for APIT tests)
* which plug-in for to be able to run from terminal our code?
- Maven surefire Plug-in

### API Tests:
* two important topics to comprehend this type testing
 - how to send our request?
 - BaseUrl + endpoint (path parameters and/or query parameters)
 - headers info, content type, authorization
 - HTTP protocol type (Reauest type) GET, POST, PUT, PATCH or DELETE
 - might have request body


 - how to read and verify response?
 - status code
 - depending on the requirements, we will verify headers and body

  Body Verification
    body verification: path, jsonPath, POJO, Java classes, Hamcrest Matchers