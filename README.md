# CS-305-SNHU
### Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
In this particular scenario the client is a financial company that contracted me to evaluate their web applications vulnerability report from the OWASP dependency check tool. 
### What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I think I did well in identifying the false positives in the dependency check. I did this by manually combing through the dependencies listed in the report and verifying that the application was actually using the version listed as having a vulnerability. 
### What about the process of working through the vulnerability assessment did you find challenging or helpful?
The manual check was by far the most difficult part because those dependencies are not brought in individually in the pom.xml file, thankfully the IDE I use has a dependency checker built in that has version control and allowed me to easily trace my way through all of the dependencies in the spring boot framework. 
### How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
A lot of the security measures I would put into place like input validation to protect from injection attacks could be handled automatically through testing and implementing input scrubbing methods. Other security measures I would put into place include using the HTTPS protocol and implementing a CA for our servers. 
### How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
In order to make sure that the code was functional I ran it and verified that it functioned as intentioned after all the refactoring had occurred. 
### What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I think the dependency check tool was very valuable and would implement that whenever I could if not already implemented. As I mentioned earlier, input validation, CA, and using HTTPS are all excellent methods for securing the application. 
### Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
I would show any future potential employers the vulnerability check report along with the suppression file I was able to successfully implement.
