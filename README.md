# Testistic

# Why
*A procedure for critical evaluation; a means of determining the presence, quality, or truth of something; a trial*

A system which aggregates test results in support of the following questions.
- How is construction of the system going?
- What is yet to start working in an environment?
- What isnt working now that we made a change?
- Has the system under test been extended or improved as a result of change

# What

The system provides an API such that test cases can be submitted

The system provides an API such that test results can be submitted.

A UI for filtering of test results across the dimensions of time, target, feature, epic, task.

# How

### Testitic-Represenation
A domain model
![A domain model](./DomainModel.PNG)

[Source](http://bayeslife.github.com/testability-representation)

### Testistic-Storage
A NoSQL storage of Test Cases and Test Results

[Source](http://bayeslife.github.com/testability-storage)

### Testitic-API
APIs which let anyone push tests cases and results.

### Testitic-UI
A VueJS UI which allows selection of test results by
- Target
- Feature, Epic, Task
- Time Period