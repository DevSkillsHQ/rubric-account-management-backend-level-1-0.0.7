# Rubric - Account Management Backend - Level 1

Hi interviewer! 👋

Here is the evaluation rubric for the "Account Management Backend - Level 1" coding challenge.

This rubric has two goals:

1. Save your time doing a code review.
2. Implement a standardized evaluation of your candidates.

The hints and the structure below will guide you through the process.

## Before you start

1. Make sure the candidate has created a Pull Request with their implementation.
2. Go through the README of the coding challenge that your candidate got to solve. You can locate the candidate repo at https://app.devskills.co/candidates.

## How to submit the assessment results

Use the structure of the "Evaluation Rubric" section and save a filled-in copy under the candidate's scorecard. Locate it at https://app.devskills.co/candidates. 

**Don't save them on the PR itself, as the candidate will see them!**

## Evaluation Rubric

### How were their technical skills?

Use the table below to navigate the code and score each of the tech competencies.

If there are any unclarities, ask the candidate to elaborate. You can either ask them a question on the PR or during a follow-up in-person interview.

#### How to score
| Score | Motivation |
|-------|------------|
| 5 | No issues at all. |
| 4 | Minor issues, but overall it works. |
| 3 | Significant issues affecting the quality. |
| 2 | Major issues. It doesn't work as expected.|
| 1 | Not completed at all. |


#### Competence scorecard
| Tech Competence                      | Description                                                                                                                                                                                                                                                                                                                                     | Score, 1-5 | Comments |
|--------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|----------|
| Working with SQL databases           | A SQL database should be the primary data store of the application. As part of this exercise, only keeping a mapping between the `account_id` and the current account balance would be enough.                                                                                                                                                  |            |          |
| Implement a service API              | This exercise comes with a predefined API spec and an API test suite. The implementation should cover all specified endpoints together with different scenarios outlined in the test suite.                                                                                                                                                     |            |          |
| Optimize the GET endpoints for speed | In this exercise, the app should only expose a single GET endpoint `/balance/{balance_id}`. This requirement then boils down to always storing the up-to-data balance value per `account_id` and returning it on `GET /balance/{balance_id}`.                                                                                                                              |            |          |
| Organize code as a set of low-coupled modules. | The code should be split into low-coupled modules. It's also highlighted that the goal here is to avoid duplication, not breaking things apart needlessly. Try to evaluate how easy it'd be to extend the provided implementation with a new feature.                                                                                                                                                          |            |          |
| Documenting decisions                | Here the candidate is expected to share any instructions for how to run their app along with any hints that should help you review the submission and better understand the decisions they made. Pay attention to how structured the instructions are. A good rule-of-thumb is to count how many times you had to read it to fully understand.  |            |          |

### How was their communication?

#### How to score
| Score | Motivation |
|-------|------------|
| 5 | Crystal-clear explanation. |
| 4 | Minor unclarities. But overal, it's clear. |
| 3 | Significant explanation gaps. At times, it was not clear. |
| 2 | Can't defend and motivate their point of view. |
| 1 | Can't explain their point of view at all. |

#### Score & Comments

| Score, 1-5 | Comments                                                                                          |
|------------|---------------------------------------------------------------------------------------------------|
|    1-5     | Feel free to add a short description of how well the candidate could express their point of view. |

### Final comments

Add a few final notes that defined your final assessment decision.

### Would you advance the candidate to the next round?

Yes/No.
