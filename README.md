# Rubric - Account Management Backend - Level 1

Hi interviewer! 👋

Here is the evaluation rubric for the "Account Management Backend - Level 1" coding challenge.

This rubric has two goals:

1. Save your time doing a code review.
2. Implement a standardized evaluation of your candidates.

The hints and the structure below will guide your through the process.

## Before you start

Please go through the README of the coding challenge that your candidate got to solve. 

You can locate the candidate repo at https://app.devskills.co/candidates.

## How to submit the assessment results

You will save the results in the candidate's scorecard available at https://app.devskills.co/candidates. 

**Please don't save them on the PR itself, as the candidate will also be able to see them!**

## Evaluation Rubric

Go through each of the sections below.

### How were their technical skills?

Go through the table below and locate the corresponding parts of the code that will help you score each of the competencies. 

There will likely be parts where you'll need an explanation from the candidate before you can score a particular competence. You can do by either asking them a question on the PR that they created, or during a follow-up in-person interview.


| Tech Competence                      | Description                                                                                                                                                                                                                                                                                                                                     | Score, 1-5 | Comments |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|----------|
| Working with SQL databases           | A SQL database should be the primary data store of the application. As part of this exercise, only keeping a mapping between the `account_id` and the current account balance would be enough.                                                                                                                                                  |            |          |
| Implement a service API              | This exercise comes with a predefined API spec and an API test suite. The implementation should cover all specified endpoints together with different scenarios outlined in the test suite.                                                                                                                                                     |            |          |
| Optimize the GET endpoints for speed | In this exercise, the app should only expose a single GET endpoint `/balance/{balance_id}`. This requirement then boils down to always storing the up-to-data balance value per `account_id` and returning it on `GET /balance/{balance_id}`.                                                                                                                              |            |          |
| Organize code as a set of low-coupled modules. | The code should be split into low-coupled modules. It's also highlighted that the goal here is to avoid duplication, not breaking things apart needlessly. Try to evaluate how easy it'd be to extend the provided implementation with a new feature.                                                                                                                                                          |            |          |
| Documenting decisions                | Here the candidate is expected to share any instructions for how to run their app along with any hints that should help you review the submission and better understand the decisions they made. Pay attention to how structured the instructions are. A good rule-of-thumb is to count how many times you had to read it to fully understand.  |            |          |

### How was their communication?

| Score, 1-5 | Comments                                                                                          |
|------------|---------------------------------------------------------------------------------------------------|
|    1-5     | Feel free to add a short description of how well the candidate could express their point of view. |

### Final comments

Add a few notes that you believe drive your final assessment decision.

### Would you advance the candidate to the next round?

Yes/No.
