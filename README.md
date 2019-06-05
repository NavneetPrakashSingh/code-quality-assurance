
# Code Quality Assurance

## Introduction & Purpose

Implemented and integrated a recipe app website using Java and Spring Boot as the backend. The main focus of the project was to write maintainable code using best backend practices like SOLID principles, design patterns, refactoring techniques, test driven development.

## Continuous Integration

Jenkins, Github and Azure as a medium for providing continuous integration. We created two branches on Github namely develop, test from production/master(default) branch and mapped Azure environment with these branches namely dev environment, test environment and production environment. Further we mapped the environment with Jenkins. We had three setups on Jenkins such that whenever there is a change in develop branch of the project, Jenkins would pick up the change and run it by checking the unit test cases against the code. If everything was successful, Jenkins deploys the application to Azure. 

## Link

The complete report can be accessed here : https://github.com/NavneetPrakashSingh/code-quality-assurance/blob/master/Group3_Report.pdf
