**Scenario**: Let’s imagine that you’re building an application for the government that takes the age of a person and then decides to assign the person to a **“minor”** group or an **“adult”** group based on their age. 

So, if their age is equal to or above 18 it will classify them as an **“adult”** and if it’s below **18** it will classify them as a **“minor”**. 

To this end, let’s pretend you’ve created 3 Lambda functions:

•	Your first Lambda function **“GetPersonAge”** generates a random number between 1 and 100. For the purpose of this test, we’ll assume this will be their age. 

•	Your second Lambda function **“ClassifyAsMinor”** takes their age and classifies them as a minor.

•	Your third Lambda function **“ClassifyAsAdult”** takes their age and classifies them as an adult.

Now, let’s say you hear that **AWS Step Functions** is an **orchestration service** that lets you connect your **AWS resources**, such as **Lambda functions**, into **serverless workflows**, called **state machines**. You’re curious to try it out for your application. Walk me through how you would do this.  