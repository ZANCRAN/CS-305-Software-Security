# CS-305-Software-Security
 Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial is a financial consulting company that offers various individual financial solution plans such as savings, retirement, investments, and insurance. Due to the nature of its activity, Artemis financial information system platform will have to manipulate sensitive customer data such as social security, bank account information, transaction, stocks report, bonds information, retirement account, etc. Securing Artemis Financial RestFul web application API is done by protecting data at rest and in transit and by scanning and addressing dependency check issues as recommended by OWASP.
• What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I used the vulnerability assessment flow diagram, OWASP REST security, OWASP REST assessment, OWASP API security to identify potential security threats with Artemis financial Restful web application API. Among the security threats that need to be inspected and addressed, we can list :

o Protecting and restricting HTPPs requests and responses (avoid leaking sensitive information)
o Verifying authentication, authorization, and session management with every request
o Building a custom access control design and web application firewall
o Validating all sources(3rd-4th-5th party vendor) of data and encrypt sensitive data
o Making use of validation/sanitation libraries or frameworks in your specific language
o Developing APIs keys and Using Jason Web tokens
o Avoiding endpoints management exposure via the internet
o Ensuring appropriate XML parser hardening for XML content
o Including appropriate headers in API response such as content
o Security policy, cache-control, X-XSS, strict-transport security, and x-frame options
o Delivering appropriate cross-origin resource sharing (CORS) headers
o Sanitizing log data beforehand and by considering logging token validation errors
o Using relevant secure coding practices
o Protecting transactions with the synchronizer tokens pattern

         Coding securely is the number one priority to avoid multiples attacks, and it enhances users and company relationships. It ensures the customer on the quality of the product and increases the company’s notoriety 
• What about the process of working through the vulnerability assessment did you find challenging or helpful?
The process of working through the vulnerability assessment is not linear but interrelated. It is difficult to identify the boundaries of each process flow.
• How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
• How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
The first thing is to identify the architecture and proceed to vulnerability assessment. After that, we can prioritize the common security threats, test the software and run a dependency check. Once the previous step is done, we address the security issues found in the applications by refactoring the code. We repetitively run, test, and refactor the code until all the vulnerabilities found are mitigated. The techniques and strategies that I have learned during this class to address a mitigation plan for a web application are highlighted in the following points:
o HTTP verb GET less secure and leak sensitive information
o Verify and validate every input and request using exception handling and branches
o Respond with a generic message and avoid revealing unnecessarily failure detail
o Allow client-side configuration, authentication, and authorization
o Ensure frameworks, servers, and system components are running the latest approved version.
o Run system health check before running the application
o Consider logging token validation error to detect an attack
o REST service must provide only HTTPS endpoints

• What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Java secure coding guidelines, OWASP secure coding practices, quick reference guide, and spring frameworks security libraries were very helpful to build a secure Rest API application.
• Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
On this particular assignment, I want to show my future employer that I am able to identify potential security threats based on the architecture. I can also use OWASP tools to address security flaws. I demonstrated the use of keytool to generate a self-signed certificate. I used the hash function with the cipher algorithm SHA-256 to map a message to a key. Thus, I used spring frameworks with MVC (Model, view, controllers) class to develop a secure Restful web application.
