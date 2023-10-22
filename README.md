# CS305 

Through the analysis of advanced security concepts, students will learn how to develop secure code that complies with security testing protocols. In addition to exploring and implementing security concepts through code, students will also learn why and how to apply encryption technologies and techniques to communicate securely. 


-Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address? 

Artemix Finacial is a consulting company that handles clients that are entrepreneurs, businesses, and government agencies around the world. They handle financial plans like savings, retirement, investments, and insurance. Artemix Finacial requested Global Rain to evaluate their code and implement industry standard for security for a bank. The request involved running a Determining area of potential attacks, Maven Dependency-Check, along with a manual review and producing a mitigation plan. 

-What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing? 

Choosing the industry standard is important but not taking account for the client business and its customers can decrease the business perception. This client handles extremely sensitive information from identity to financial information. Using higher key length can give greater security, something required for this type of information.   

-What part of the vulnerability assessment was challenging or helpful to you? 

Identifying the areas of security and focusing on only a few helped address significant issues with the code. The areas for this code were the API, Cryptography, and encapsulation. API is the passthrough of information so a weak entry point could allow a data breach. Cryptography provides security to the information directly making it less desirable to steal information as with current encryptions it would take multiple lifetimes to crack. And correct encapsulation to prevent modification to a classes' attributes. 

-How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? 

Adding a try catch blocks around connections to handle any exceptions to prevent the program from crashing or revealing a vulnerability. Encapsulation of the API calls would prevent modification that could allow bad actors to extract information. Encrypting the information adds security even after the information has been extracted. Using the Maven Dependency check finds any past and the most recent vulnerabilities discovered, doing periodic checks and consistent updates will keep the security up to date. Any connection should be verified good and should always have an encrypted connection standard is to use AES-256, any chance of a crash or misuse of an input field should have checks around them to prevent the program from crashing potentially revealing information or the code. Any passwords or limited use information should be stored encrypted also, this will add security if information is leaked.  

-How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? 

The Maven Dependency check has a vast database of known vulnerabilities so any changes to the security aspect of the code should have a dependency check. The dependencies check the libraries used for the code against its database and flag any vulnerabilities. Since libraries are often third parties and keep their libraries up to date to address and security issues. The CVE (Common Vulnerability and Exposures) codes will often give guidance on how to address the issues. This application used an outdated maven check and many libraries needed updates that addressed security vulnerabilities over time. 

-What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? 

The Maven dependency check is a critical aspect to keep code safe. I often wondered how code was kept safe with the vast number of libraries that can be used when coding. Knowing there is a helpful program to help address these issues makes me feel a little more at ease when developing safe code. Using the Keytool and certificate is also important, but I am still learning their full use, I will need to continue researching these topics more.  

-Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment? 

Understand the importance of security and the correct implementation of each. Using a symmetrical cipher for a password is not advisable as a password should rarely change so having a method to decrypt it is counterproductive, using AES-256 to establish a secure connection to verify the connection is correct and trusted. 
