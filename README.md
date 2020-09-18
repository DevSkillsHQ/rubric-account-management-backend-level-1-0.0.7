# Account management API - Level 1
In this interview challenge, the candidate is supposed to build a backend service that implements the Account Management API. 
The consumers of this API will use it to amend/fetch balances of different accounts.

## Template Repository
[Account management API - Level 1](https://github.com/DevSkillsHQ/account-management-api-level-1)

## Target Level
Junior

## Tasks
### Task 1: Implement update & fetch operations over a REST API.
This task is about building a service that can handle simple update and read operations over a REST API.
There are no tricks here and this challenge simply validates one's general coding ability.

#### Automated test scenario
Update and fetch account balance.

#### Code Review checklist
| Questions                                                                                                                                      | Assessed Skills                            |
|:------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------|
| Do all tests from the provided test suite pass?                                                                                                | TDD, Backend, REST API |
| Has the candidate created any other tests? Do those tests make sense to you? How well did they cover corner cases?                                                              | Code Testing                               |
| How easy was it to grasp the provided code? How easy can this code be unit tested? Is the code loosely coupled and highly cohesive? | Code Design                                |

### Task 2: Implement handling of invalid HTTP requests.
This task is about implementing error handling for different types of invalid incoming requests.
This is a good task for evaluating one's ability to implement practices of defensive programming.

#### Automated test scenario
Rejecting invalid requests.

#### Code review checklist
| Questions                                                             | Assessed Skills |
|:-----------------------------------------------------------------------|:-----------------|
| Do all tests from the provided test suite pass?                       | Error Handling  |
| How tightly is the error-handling logic coupled with the business logic? | Code Design     |

## Evaluation Rubric
| Task                                                  | Evaluated Skills                                                      | Score | Comments                                    |
|:-----------------------------------------------------------|:----------------------------------------------------------------------|:------|:--------------------------------------------|
| Implement update & fetch operations over a REST API        | Backend, Test Driven Development, REST API, Code Testing, Code Design | 1-5   | Free text comments explaining the reasoning |
| Implement handling of invalid HTTP requests.               | Error Handling, Code Design                                           | 1-5   | Free text comments explaining the reasoning |
