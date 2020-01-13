# ***What is Vulnerable-API***
Vulnerable API is designed to practically understand OWASP TOP 10 API vulnerabilities.

# ***Vulnerable-API***
Vulnerable-API includes following vulnerabilities: [***OWASP TOP 10***](https://www.owasp.org/index.php/OWASP_API_Security_Project)<br>
Reference- https://www.owasp.org/index.php/OWASP_API_Security_Project
- ***Broken Object level Authorization:<br>***
APIs tend to expose endpoints that handle object identifiers, creating a wide attack surface Level Access Control issue. Object level authorization checks should be considered in every function that accesses a data source using an input from the user. 
- ***Broken Authentication:<br>***
Authentication mechanisms are often implemented incorrectly, allowing attackers to compromise authentication tokens or to exploit implementation flaws to assume other user's identities temporarily or permanently. Compromising system's ability to identify the client/user, compromises API security overall. 
- ***Excessive Data Expose:<br>***
Looking forward to generic implementations, developers tend to expose all object properties without considering their individual sensitivity, relying on clients to perform the data filtering before displaying it to the user. 
- ***Lack Of Resources:<br>***
Quite often, APIs do not impose any restrictions on the size or number of resources that can be requested by the client/user. Not only can this impact the API server performance, leading to Denial of Service (DoS), but also leaves the door open to authentication flaws such as brute force. 
- ***Broken Function level Authorization:<br>***
Complex access control policies with different hierarchies, groups, and roles, and an unclear separation between administrative and regular functions, tend to lead to authorization flaws. By exploiting these issues, attackers gain access to other users’ resources and/or administrative functions. 
- ***Mass Assignment:<br>***
Binding client provided data (e.g., JSON) to data models, without proper properties filtering based on a whitelist, usually lead to Mass Assignment. Either guessing objects properties, exploring other API endpoints, reading the documentation, or providing additional object properties in request payloads, allows attackers to modify object properties they are not supposed to. 
- ***Security Misconfiguration:<br>***
Security misconfiguration is commonly a result of unsecure default configurations, incomplete or ad-hoc configurations, open cloud storage, misconfigured HTTP headers, unnecessary HTTP methods, permissive Cross-Origin resource sharing (CORS), and verbose error messages containing sensitive information. 
- ***Injection:<br>***
Injection flaws, such as SQL, NoSQL, Command Injection, etc., occur when untrusted data is sent to an interpreter as part of a command or query. The attacker's malicious data can trick the interpreter into executing unintended commands or accessing data without proper authorization. 
- ***Improper Assets Management:<br>***
APIs tend to expose more endpoints than traditional web applications, making proper and updated documentation highly important. Proper hosts and deployed API versions inventory also play an important role to mitigate issues such as deprecated API versions and exposed debug endpoints. 
- ***Insufficient Logging & Monitoring:<br>***
Insufficient logging and monitoring, coupled with missing or ineffective integration with incident response, allows attackers to further attack systems, maintain persistence, pivot to more systems to tamper with, extract, or destroy data. Most breach studies demonstrate the time to detect a breach is over 200 days, typically detected by external parties rather than internal processes or monitoring. 

# Installation
- Clone the Git `git clone `

# Contributors
- Jaikey Sarraf (@jaikeysarraf)
- Vishal Sharma (@newaivirus)
