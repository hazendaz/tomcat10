Tomcat 10 Bundle
===============

This project takes tomcat 10.1.23 zip and expands on it to provide the following.

- Tomcat-slf4j-logback integration
- Logback Access integration
- Psi Probe Management Tool
- Java Metro Integration
- All tomcat webapps items removed
- Setup for https (currently disabled)
- Setup for psi probe
- And if you want, drop back in tomcat wars and those are pre-configured as well but intentionally left out

## Notes ##
- Credential usage here is simply for testing purposes only and should be considered exposed.
- Tomcat 10.0 was not created for psi-probe as jakarta work never finished during that time and it since went end of life.  So tomcat 10 servers as 10.1 line only.
