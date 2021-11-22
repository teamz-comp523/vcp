## Client Overview



**What are the major pieces of your overall system? Include your architecture diagram (or perhaps a simplified version of it) and describe it in a way the client can understand.**

Our application is containerized using Docker in a public GitHub repository at https://github.com/teamz-comp523/vcp_project. We’ve implemented most of our functions — user authentication, project, takes, captures, and scene view. We implemented the back end using Django and front end using React. We have PostgreSQL as our database. 

![Architecture Diagram](https://teamz-comp523.github.io/vcp/diagram.jpg)



**Where is each piece deployed?**

We deployed the project to AWS using ECR, RDS, and Elastic Beanstalk.



**How can the client manage everything? (You should give your client admin access over the infrastructure, if you haven’t already.)**

The client can use the [public repository](https://github.com/teamz-comp523/vcp_project) based on its README file. We have listed clear and simple steps to build a read-to-use development environment. To manage the system, client can use [this link](http://vcptest-env.eba-7spnf825.us-east-1.elasticbeanstalk.com/) to check the back-end environment of the project.



**How much does everything cost? Is that subject to change? If so, under what conditions? Remember to include yearly subscriptions (like an Apple Developer membership) as well as monthly costs.**

It depends on the network flow of the server. AWS has a detailed [formula](https://calculator.aws/) to calculate the cost.



**Where does the code live? Is it open source or closed source? Does the client have a license to do what they want with it?**

The code is open source at https://github.com/teamz-comp523/vcp_project. . It's under MIT license and client can have full accessability over it.



**How can the client access the live app?**

[VCP](http://vcptest-env.eba-7spnf825.us-east-1.elasticbeanstalk.com/vcp/)



**If the app isn’t generally available, is there a way that the client can share the app with somebody else, so that they can use it?**

Yes. We have a simple and clear developer README file [here](https://github.com/teamz-comp523/vcp_project/blob/main/README.md).



**Of the “need-to-have” user stories (see [Assignment 2](https://comp523.cs.unc.edu/user-stories/)), which ones are complete, partially complete, or unstarted?**

complete:

- Sign Up
- Log in
- Create a project
- Project View
- Scene View
- Create a new Scene
- Create a new Take
- Log off

partially complete:

- Upload the files for caputres

unstarted:

- Wait and download file from the cloud
- Support
- Put the file into whatever app they want



**Did you make any progress on the “nice-to-have” user stories? If so, which ones, and how much progress?**

We haven't gotten a chance to further investigate into this part. 



**What do you think the highest priority next steps are?**

Finish the upload feature for the project and add a more complex security layer into the user authentication feature given that the media files may include sensitive and private content.

