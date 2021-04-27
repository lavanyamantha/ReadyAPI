# ReadyAPI

## Introduction:

- Ready API is tool by SmartBear company
- It is used for Functional test, Performance test & Security test.
- I have installed the trial version - available for 2 weeks

## Sample Application:

### SOAP Service: Employee Managemnet service - http://216.10.245.166:8080/axis2/services/

### Available operations:
- getEmployeeDetails
- deleteEmployee
- addEmployee

#### WSDL Document - Gives the description of web service. It is an XML document. We can get this from above sample service url.

## Test Structure in Ready API (also valid for any automation framework):
- Project > Import API Definition(WSDL) > Test Suite > Test Case > Test Steps > Add Assertions
- Demo of implementation
- Run all or desired tests from 'Launch TestRunner' (we can configure various settings here including reporting - junit/allure)

## How to use this?
- Download the project to your system
- Open ReadyAPI
- Import the project > point to the downloaded folder
- You may execute the tests as-is from various places (from menu bar Or using Test runner)

## Reporting

### ReadyAPI Test execution status
![image](https://user-images.githubusercontent.com/13006890/116269623-60e67080-a74c-11eb-8a42-5da9a9ed142b.png)

### Junit report
![image](https://user-images.githubusercontent.com/13006890/116269871-9723f000-a74c-11eb-9574-f54b015f8111.png)

## What's next ?
- Can be integrated with various tools
- Expand to other services like REST based on use cases
