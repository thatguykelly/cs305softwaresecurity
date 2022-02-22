# cs305softwaresecurity

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

  Artemis Financial is a financial consulting company that develops individualized financial plans for savings, retirement, investments, and insurance for their patrons. Artemis Financial has a public web interface and is seeking Global Rain’s expertise in taking steps to protect their client data and financial information. Specifically, Artemis Financial is seeking to add a file verification step to their web application to ensure secure communications. When the web application is used to transfer data, they will need a data verification step in the form of a checksum. You have been asked to take their current software application and add secure communication mechanisms to meet their software security requirements. You will deliver a production quality integrated application that includes secure coding protocols.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  After checking vulberabilities I was able to do a manual code review which was very helpful in deciding which avenues needed addressed. Secure communications are very important to maintain in this application as unsecure communications can cause data to be seen by an attacker and could cause them to steal confidential or personal information. The results of a security breach can cause (but are not limited to) a loss of trust between the application owner and the consumer, financial loss due to fines incurred by governments requiring secure communications, and financial loss due to resources spent repairing/addressing the security issue. Maintaining security in the application will protect the company’s products and assets and keep their client’s trust in tact.


What about the process of working through the vulnerability assessment did you find challenging or helpful?

  The assessment was tough to navigate at first. After working through it a few times I was able to suppress certain vulnerabilities. With adding a checksum there was a way to see that data has been encrypted correctly.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
  Adding the checksum and input validation was key to this project. Also the manual code review was able to open options of what and how to mitigate. I would continue to use the static and dynamic testing and be mindful of other areas where I can improve.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
  By incorporating the checksum, input validation and knowing that the vulnerabilities either didnt effect the code or did not pertain to situations in the code. I re ran the dependancy check tool and was able to suppress anything that was left or update the system within the code.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
  Secure coding practices was number one. We used the java built in security, Maven to check for dependencies and refactoring of code. The NVD database was really helpful and I look forward to diving more into that.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
  The fact that secure coding is evermore important than ever means that as a developer this needs to be on our minds at all times. I will hope that I can send code to Quality Testers that will meet or exceed their initial expectations. Also that I am knowledgeable of the tools out there to help us and that going beyond what the tools offer will be needed in most cases.
