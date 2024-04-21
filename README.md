# Software-Security
CS-305-R4821 Software Security 24EW4

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
  Artemis Financial is a consulting company that specializes in developing financial plans for customers that include savings, retirement, and investments. The company has a public web interface and wants to modernize their operations to enhance the security of their client data. 

•	What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  One thing I think I did well on when I found the clients software security vulnerabilities is identifying all the potential vulnerabilities by both using Maven, a tool designed to find vulnerabilities, and doing a manual check of the code myself. It is important to code securely to reduce the risk of costly data breaches or attacks. The value provided by including software security to an application is reducing costs, ensuring brand reputation for being safe and secure, and keeping in compliance with local laws. 

•	What part of the vulnerability assessment was challenging or helpful to you?
  The most challenging part was creating a checksum, I ran into a lot of issues of not being able to verify the checksum. I also had a hard time finding where the maven dependency check report saved to, but once I found it, I had no problems with that going forward. 

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  I increased layers of security by checking maven for dependencies, updating to the recent application for them, and by encrypting the data to prevent unauthorized access. In the future I will manually check my code first, then do a maven dependency check to ensure that my code is secure. 

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  To ensure that the code and software was functional and secure I tested the code through maven and conducted a code review. After I refactored the code, I re-ran to check for any new vulnerabilities. 

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  Maven is a tool I have never used before, and I found it to be very insightful. I will absolutely be checking for vulnerabilities this way in the future as I feel a lot more confident using this tool after this class.

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I would show future employers the vulnerability report which shows that I know what areas of security to look at, how to do a manual review, and how to implement static testing.
