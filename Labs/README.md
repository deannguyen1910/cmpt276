[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/DocP1R7u)
# Lab 2 (25 marks)

[View Lab Instructions Here](L2.md)

[How to use Github / How to submit](https://parsa-rajabi.github.io/cmpt-276/#/assignment-lab-details?id=submission)

For this lab, you will include all of your "answers" in this README file. Make sure to cite any sources you use. 

## Task 0: Declare your AI Usage 

After you completed the lab, make sure to submit the AI declaration form via MS Form and also upload a PDF copy of your responses to this repository. Note, you must submit this form regardless if you use AI or not. Failure to submit this form will be considered a violation of AI course policy. More details about the AI-usage course policy can be found [here](https://parsa-rajabi.github.io/cmpt-276/#/ai-policy).

[Link to AI Usage Disclosure MS Form](http://bit.ly/276-AI)

Name the file in the following format: 

`Lab#_AI_Declaration_FirstName_LastName_StudentID.pdf`

Example:

`Lab2_AI_Declaration_Parsa_Rajabi_123456789.pdf`


More detailed submission instructions can be found via the [assignment/lab page](https://parsa-rajabi.github.io/cmpt-276/#/assignment-lab-details).

## Task 1: Reading Questions 

For this task, please include your answers for the questions described in the [Lab 2](L2.md) file below:

### Q1 - Summary
[Insert answer here]
The chapter points out a few reason that mostly causes behind schedule or bottleneck such as the unexpect bugs could happen because developers would be too "optimistic", rescheduling not enough time for each stage of SDLC especially testing and planning stage and mentioned that it happen much more common in software engineering, he emphasized the severe of rescheduling and cannot be fixed by adding more people. Afterward, authors suggests some solution as the severe of rescheduling as maximize the communication - sharing data so that every bugs should be figure before deadline, rule of thump is 1/3 planning, 1/6 coding, 1/4 component test and early system test, 1/4 system test and all components in hand, have an optimal number of men at initial stage. However, for the auther, that is still high chance that could be false scheduling.

### Q2 
[Insert answer here]
As the author mentioned that adding more people would give more stress to man-month (Section Gutless Estimating, number 4, 3rd paragraph). Though recuiting quickly done, it also requires more man-month to train people. The work is redistributed, "some work already done will be lost, and system testing must be lengthened." (Section Gutless Estimating, number 4, 2nd paragraph)
    For example, assume that the work left is 7 man-month and there are already 5 men and there is one month left. Suppose that recuiter was done quickly to add 2 more people that would causes:
        - Training time would require 4 men, 2 of them are trained men. So that there are only 3 man are working on the project and 2 men are training and 2 men are being trained. Suppose after half of a month, the work is 5.5 man-month left. There are 7 trained men and half of a month left. At the end of the month, it is still 2 man-month worth of work left. So it leads to 2 conclusion that: it requires extension in schedule or initially recuit more than 2 (which is not simple linear function as, tangent as a = 1).
        - The work could be lost as the a new distributing working list has been change which could cause slowing down the process.


### Q3 
[Insert answer here]
    Unexpected bugs was the problems that causes rushing work as the team was quite confident in working. For example, we spent time in coding to extend runtime performance rather than in testing and system testing. 
    When a member have problem, it would take a small delay to communicate to require support. It is not also slowing down the helper but also the whole process as there is bottle-neck that wouldn't meet the deadline of the 2-week period. A key lesson is that "Communication is the key". 

### Q4 
[Insert answer here]
    - The view was outdated as the internet was not highly applied for studying online. At the time, automation courses and framework for software engineering that could improve training stage and help reducing man-month for training, that was not popular.  
    - Furthermore, if the communication was maximize, the bugs should be monitor in early stage and there will be always back-up team that help reducing bottleneck.
    - Facillities is much more simple that it was in the past as easier to afford and every can own themself a computer so that preparation should be shorten.
    - The work should be breaking into manageable chunks following determined framework so that is it much more easier for newer to approach the problems.
    - Git and Github is more popular as the work is easier to monitor and save in log history. 
    - The communication is better as there is internet would leads to shorter delay in sending and receiving information.
### Q5 
[Insert answer here]
I learned some key idea in the concept from this book that:
    - The planning should point out each stage of work in detail and the schedule of each week. 
    - Leave spare time after if there is urgent problem at the end.
    - Maximize the communication and exchange data after a certain period (e.g middle of the week and and at the end of the week).
    - Break the work into manageable chunks as it is can be continue after each 2 weeks. Leave a certain time in testing at almost the end of the week (for e.g, start from thursday and report at friday).
    - Use automation tools but made by a different person (avoid bias).  
## Task 2: Video Questions

For this task, please include your answers for the questions described in the [Lab 2](L2.md) file below:

### `git checkout`
[Insert answer here]
git checkout/switch: it allows we checkout or switch to the certain commit/branch was made. So that git assumes that we have the same code as that branch and we're working on it.

### `git revert`
[Insert answer here]
It reverts to the branch that was mention in argument without delete any commit log. For example, "git revert master" means that it would revert to the state that we committed master. 

### `git reset`
[Insert answer here]
It reset the commit to the state mention in argument but it doesn't delete the code. However, it would delete the commit log after the commit in the argument.
For example, git reset master means that code is still the same but the commit log that committed after master is removed.
