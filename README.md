# SECUREHASH
PROJECT REPORT 
SecureHash – Client-Side Password Hashing Tool 
1. Project Title 
SecureHash – A Secure Client-Side Password Hashing Tool Using Web Crypto API 
2. Abstract 
SecureHash is a client-side web-based password hashing tool designed to convert user 
passwords into secure cryptographic hash values. The project uses modern hashing 
algorithms such as SHA-256, SHA-384, and SHA-512 through the Web Crypto API. All 
hashing operations are performed locally within the user’s web browser, ensuring that 
the password is never transmitted to any external server. This project aims to 
demonstrate the concept of password hashing, enhance awareness about password 
security, and provide a practical learning tool for cybersecurity students. 
3. Introduction 
In today’s digital environment, password security plays a vital role in protecting user 
data and online identities. Storing or transmitting passwords in plain text can lead to 
serious security breaches. To prevent this, cryptographic hashing techniques are widely 
used in secure systems. 
SecureHash is developed to demonstrate how password hashing works in real-world 
applications. It provides an interactive interface where users can input a password, 
select a hashing algorithm, and instantly view the hashed output. This project focuses 
on client-side security, ensuring privacy and transparency in the hashing process. 
4. Problem Statement 
Many systems still rely on weak password storage methods or lack proper 
understanding of hashing mechanisms. Beginners often confuse encryption with 
hashing and are unaware of the risks of storing plain text passwords. There is a need for 
a simple, secure, and interactive tool that demonstrates password hashing without 
relying on backend servers or databases. 
5. Objectives of the Project 
The main objectives of the SecureHash project are: 
• To demonstrate the concept of password hashing 
• To implement secure hashing algorithms using Web Crypto API 
• To provide a client-side password security solution 
• To educate users about secure password handling 
• To allow comparison between different hashing algorithms 
6. Scope of the Project 
This project is primarily intended for educational and demonstration purposes. It helps 
users understand how cryptographic hashing works and how different algorithms 
produce different hash lengths. The project can be extended in the future to include 
salted hashing, key stretching, and advanced password hashing algorithms such as 
bcrypt, scrypt, or Argon2. 
7. Tools and Technologies Used 
• HTML5 – For structuring the web page  
• Web Crypto API – For secure cryptographic operations
• Web Browser – As the execution environment 
8. System Architecture 
The SecureHash system follows a simple client-side architecture. The user enters a 
password through the web interface and selects a hashing algorithm. The JavaScript 
logic processes the input and uses the Web Crypto API to generate the hash. The 
resulting hash is then displayed on the same page along with additional details such as 
hash length and timestamp. No data is sent to any server, ensuring maximum privacy 
and security. 
9. Algorithm Description 
1. Accept password input from the user 
2. Convert the password string into byte format using TextEncoder 
3. Select the hashing algorithm chosen by the user 
4. Generate the hash using Web Crypto API 
5. Convert the hash output into a hexadecimal string 
6. Display the hash along with algorithm details and timestamp 
10. Module Description 
Input Module 
This module allows users to enter a password and select a hashing algorithm. It also 
includes a password visibility toggle feature for user convenience. 
Hashing Module 
This module handles the core functionality of the project. It uses the Web Crypto API to 
apply cryptographic hashing algorithms such as SHA-256, SHA-384, and SHA-512. A 
fallback implementation is used for MD5 for demonstration purposes. 
Output Module 
This module displays the generated hash, hash length, selected algorithm, and 
timestamp. It also includes a copy-to-clipboard feature. 
Utility Module 
This module manages additional functionalities such as clearing inputs, copying the 
hash, and handling user interface interactions. 
11. Source Code Explanation 
The project is implemented using HTML, CSS, and JavaScript in a single file. HTML 
defines the structure of the application, CSS provides a cyber-themed visual design, 
and JavaScript handles all logic-related tasks such as hashing, input validation, and 
output display. The Web Crypto API ensures that hashing operations are secure and 
browser-native. 
12. Input and Output Description 
Input: 
• User password 
• Selected hashing algorithm 
Output: 
• Hashed password in hexadecimal format 
• Hash length 
• Algorithm used 
• Timestamp of hash generation 
13. Applications of the Project 
• Educational tool for cybersecurity students 
• Demonstration of password hashing concepts 
• Client-side password security testing 
• Learning platform for Web Crypto API 
14. Advantages 
• No server-side dependency 
• High security and privacy 
• Uses modern cryptographic standards 
• Simple and user-friendly interface 
• Fast hash generation 
15. Limitations 
• Does not use salting or key stretching 
• MD5 implementation is for demonstration only 
• Not suitable for production password storage 
• Limited to browser-supported algorithms 
16. Future Enhancements 
• Implementation of salted hashing 
• Support for bcrypt, scrypt, and Argon2 
• Backend integration for authentication systems 
• Hash verification feature 
• User authentication simulation 
17. Conclusion 
SecureHash successfully demonstrates the concept of password hashing using modern 
cryptographic techniques. By performing all operations on the client side, the project 
ensures user privacy and security. This project serves as an excellent learning resource 
for understanding password security, hashing algorithms, and client-side cryptography 
in cybersecurity applications.





https://siddharthkusv.github.io/SECUREHASH/
