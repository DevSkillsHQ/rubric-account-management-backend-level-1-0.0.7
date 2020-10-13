# Evaluation Rubric: Account management Backend - Level 1

| Tech Competence                      | Description                                                                                                                                                                                                                                                                                                                                     | Score, 1-5 | Comments |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|----------|
| Working with SQL databases           | A SQL database should be the primary data store of the application. As part of this exercise, only keeping a mapping between the `account_id` and the current account balance would be enough.                                                                                                                                                  |            |          |
| Implement a service API              | This exercise comes with a predefined API spec and an API test suite. The implementation should cover all specified endpoints together with different scenarios outlined in the test suite.                                                                                                                                                     |            |          |
| Optimize the GET endpoints for speed | In this exercise, the app should only expose a single GET endpoint `/balance/{balance_id}`. This requirement then boils down to always storing the up-to-data balance value per `account_id` and returning it on `GET /balance/{balance_id}`.                                                                                                                              |            |          |
| Documenting decisions                | Here the candidate is expected to share any instructions for how to run their app along with any hints that should help you review the submission and better understand the decisions they made. Pay attention to how structured the instructions are. A good rule-of-thumb is to count how many times you had to read it to fully understand.  |            |          |
