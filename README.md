# Patient List

The main goal of this interview is for us to assess your level of expertise in the QA automation ecosystem, but it's also to understand your habits as Software QA Automation and evaluate your skills. 

It's important for us to have access to your homework BEFORE the interview to have time to review it and prepare some constructive feedbacks. The goal of this interview is for all of us to learn from each other.

We provide a small Web application which manages the patients' list of a physician in a hospital. 

During this ~2h session, we will evalutate your skills on multiple aspects! It's important to read all the instructions before you start the clock !

## Instructions

We are trying to build the E2E pipeline to fully cover the application and avoid regressions for future developments. We expect you to write E2E tests to cover all the application features and edge cases that may be found. 

In this application, you should be able to do : 
- Create new patient, edit and remove patients
- Filter the patients' list based on the patient's name, the indication and the age
- Sorting the table based on a column


A particular attention will be taken to your code structure, the scenarios and the coverage of the application.

To complete the homework you can choose either of the following options:

1. Improve the existing Playwright tests that you can find in the project:
    - improve how the tests are written, and how they're running
    - fix the test that doesn't work, explain what was broken
    - add new test cases for features that were not correctly covered
2. or Add brand new tests using the framework of you choice: Cypress, Selenium, surprise us!


You can choose any of those frameworks, but we expect a clean file structure on your final project.

## Share with us

If you are using a private repository on Github, add us as collaborator ([`baptooo`](https://github.com/baptooo), [`mathieu-schnoor`](https://github.com/mathieu-schnoor) , [`gserrell`](https://github.com/gserrell)) so we can have access to your homework.

Otheriwse, share us your code in a zip file ( using the command `git archive --format zip --output /full/path/to/zipfile.zip master` ).
## Install

`yarn`

## Run

`yarn dev`

## E2E tests

```sh
yarn playwright install
yarn playwright test
```
