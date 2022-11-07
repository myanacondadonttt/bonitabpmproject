# bonitabpmproject
Bonita BPM project for Process Engineering course at MoSiG M2 program.

## Answers for the questions:

### The model displays some errors. Do you know why?
We are observing an error because the output transitions from a XOR gateway must be default or conditional. We haven't used the forks for gateway such as "Yes" or "No" anser after the XOR gateway. In order to fix this error we have to add the condition. To do so we had to click on the connection leaving the gateway and add the conditions accordingly.
<img width="664" alt="image" src="https://user-images.githubusercontent.com/46463790/196209224-421a1455-58d1-4b18-90cf-52c0385f9e8c.png">

Source : https://community.bonitasoft.com/questions-and-answers/xor-conditional-output-settings

### Why do we define variables at the process level?
A process variable is available throughout the life of a process. Process variables can be uses to store data for transition conditions, and identifiers for business data stored in an external database. They are typically items of data which affect the path of the process, or are used at several steps of the process, but which become redundant, once the process instance has completed.

Source: https://documentation.bonitasoft.com/bonita/2022.2/data/specify-data-in-a-process-definition

To be able to use them properly during the whole process lifecycle. :)



### Why do we use operations in Bonita BPM?

### Which are the human tasks that need a form? Why?

### What happens if you try to realize the task Approve proposal after 15 seconds (suppose you define the timer with 15sec)?

### Why we should not use a terminate event in this case?
