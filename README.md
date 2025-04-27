# CS305-Software-Security
##Artifact Chosen: Practices for Secure Software Report (Project Two)

Artemis Financial is a consulting company that creates personalized financial plans for its customers, covering savings, retirement, investments, and insurance. They hired Global Rain to help strengthen the security of their web application. The main issue they wanted me to address was securing communications, verifying data integrity, and improving overall software security.

When finding vulnerabilities, I did well at carefully identifying weak spots like missing encryption, lack of file verification, and unsecured HTTP communication. It is important to code securely to protect sensitive customer information, maintain trust, avoid data breaches, and support the company’s reputation and operations.

The most challenging part of the project was setting up HTTPS and managing the certificate process. This part helped me understand how important secure communication is and how certificates work in real applications.

To increase the layers of security, I added checksum validation for files, implemented encryption standards, and configured the application to use HTTPS instead of HTTP. In the future, I would continue using static analysis tools like OWASP Dependency-Check and follow vulnerability assessment processes to choose the best mitigation techniques.

I made sure the code and application were functional and secure by testing every change and running a static analysis scan after refactoring. This helped confirm that no new vulnerabilities were introduced.

Some of the key resources, tools, and coding practices I used were Java Keytool for certificate creation, Maven Dependency-Check for static testing, cryptographic hashing, and general secure coding practices like input validation and strong encryption.

For future employers, I would showcase this assignment to demonstrate my skills in finding and fixing software vulnerabilities, applying secure coding practices, using security tools, and delivering secure, working software solutions.
