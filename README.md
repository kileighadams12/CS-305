# CS-305

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a company that helps clients with savings, insurance, and investment services. They needed to improve their web application's security to protect client data while it was being transferred. They also wanted a way to confirm that the data wasn’t changed during transfers by adding a checksum feature.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I was able to add SHA-256 checksums and set up HTTPS without causing problems in the web application's functionality. Secure coding is important because it protects sensitive data and helps prevent security breaches that could harm a company’s reputation. It also builds trust with users and helps the company stay compliant with security best practices.

# Which part of the vulnerability assessment was challenging or helpful to you?
Deciding which vulnerabilities to address first took some thought since there were many areas that needed improvement. Using OWASP Dependency-Check was helpful because it showed which dependencies were outdated or risky. This made it easier to see which updates would have the most impact on improving security.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added HTTPS to secure data in transit using a self-signed certificate and used SHA-256 to confirm data integrity. These updates made the application more secure without adding unnecessary complexity. In the future, I would continue using automated tools like OWASP Dependency-Check and reviewing CVE reports to decide which vulnerabilities to address.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
After making security updates, I tested the web application to ensure it worked as intended. I ran dependency checks again to see if any new vulnerabilities appeared after the changes. This helped me confirm that the updates improved security while keeping the application functional.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used OWASP Dependency-Check to identify and track vulnerabilities in the application's dependencies. I also used Java Keytool to generate a self-signed certificate, allowing me to test HTTPS locally within Spring Boot. These tools and practices will be helpful for future projects that require secure coding and testing.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show employers how I added HTTPS and checksum features to improve an application's security while ensuring it continued to function properly. This assignment demonstrates that I can apply secure coding practices and use industry tools to deliver a secure product. It also shows that I can take practical steps to address actual security needs in a project.

