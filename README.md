# Cybersecurity---Project-I
Cyber Security Base - Course Project I.
Zip file attached contains the full project.

A1-Injection.
The project is vulnerable to injections. 
Database can be written into as prepared statements are not used.

A2-Broken Authentication and Session Management.
User can log in but resources have not been protected on a sufficient level.

A5-Security Misconfiguration.
Instead of secure traffic an insecure http protocol is used. 

A6-Sensitive Data Exposure.
Unprotected password should be protected by salting them into a database.

A7-Missing Function Level Access Control.
Login page can be skipped and sign-up page can be accessed via URL: http://localhost:8080/form
Access control should be coded and put in place.
