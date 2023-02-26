# CS-305
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial wishes to increases the security of the files being transfered through their app. They wanted to ensure online communications were secure by using a checksum to verify the authenticity of files. Their existing app did not have this security feature which made communications vulnerable to attacks.

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I did a very good job refactoring the code so it would encrypt the data being sent using a strong cipher algorithm such as the SHA-256. I also generated a self-signed certificate using Java keytool. These software security measures will keep online communications secure and will make it almost impossible for a hacker to perform an attack. Adding multiple layers of security to an app will save the company from problems down road.

What part of the vulnerability assessment was challenging or helpful to you?
The summary part of the vulnerability assesment was helpful because it outlined all the known vulnerabilities along with information about them and the severity level. This section helps determine which vulnerabilities must be addressed immidiately.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Security was increased by adding a checksum to verify the file's authenticity. Additionally, I ran the OWASP dependency check to catch any vulnerabilities and eliminate the most severe ones. In the future, I will make sure that dependencies are updated to their latest version to reduce the chance of vulnerabilities.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After refactoring the code, I ran the app and later loaded it on the localhost. The app displayed the data message along with its checksum and this tells me that the app is functional and secure. Running a dependency check after refactoring the code pointed out some new vulnerabilities related to the newly added libraries.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
The OWASP dependency check is a great tool that I will keep using to find vulnerabilities and mitigate them.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I feel pretty confident that showing the whole report to a future employer will demonstrate that I value security and that I am familiar with the basics of security. 
