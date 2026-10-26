# CS 305 Software Security

## Artemis Financial

Artemis Financial was the client for this project. The company develops individualized financial plans for its customers, including savings, retirement, investments, and insurance. Artemis Financial wanted to modernize its existing web application while improving the security of customer data and financial information. One of the main requirements was adding a file verification process using a checksum and implementing secure communication within the application.

## Software Security and Vulnerability Assessment

One area I did well was applying multiple layers of security rather than relying on a single control. I implemented SHA-256 checksum verification, configured HTTPS communication, generated a self-signed certificate, and used OWASP Dependency-Check to analyze third-party dependencies. Secure coding is important because vulnerabilities can expose sensitive information, disrupt business operations, and reduce customer trust. Security also adds value to a company by reducing risk and making software easier to maintain safely over time.

One of the more challenging parts of the vulnerability assessment was reviewing dependency-check results and determining what needed to be addressed. Automated security tools can identify many potential vulnerabilities, but developers still need to review those findings and understand how the affected libraries are being used. This helped me better understand that software security requires both automated testing and manual analysis.

## Layers of Security

I increased security by combining several different protections. SHA-256 was used to verify data integrity, HTTPS protected communication between the client and server, and a certificate supported TLS communication. I also used input validation, automated tests, dependency scanning, and manual code review. In future projects, I would continue using tools such as OWASP Dependency-Check, vulnerability databases, secure coding standards, and repeated security testing to determine which vulnerabilities should be prioritized and mitigated.

## Functional and Security Testing

I verified that the application remained functional by running the refactored application and testing the checksum endpoint through HTTPS. I tested both valid and invalid checksum values and reviewed the code for syntax, logic, and security issues. I also ran automated tests and OWASP Dependency-Check after making changes to confirm that the application still worked and that I had not introduced new vulnerabilities.

## Tools and Practices

Several tools and practices from this course will be useful in future projects. These include Java cryptographic APIs, SHA-256 hashing, Java Keytool, TLS and HTTPS configuration, Maven, OWASP Dependency-Check, vulnerability analysis, dependency management, secure input validation, and automated testing. I also learned the value of integrating security throughout the software development lifecycle instead of treating it as something that happens only at the end.

## Portfolio Value

This project demonstrates to future employers that I can analyze an existing application, identify security concerns, implement secure coding improvements, and verify that those improvements work correctly. It shows experience with cryptographic hashing, certificates, HTTPS, vulnerability scanning, dependency remediation, secure software testing, and technical documentation.

The completed **Artemis Financial Practices for Secure Software Report** included in this repository provides evidence of that work.
