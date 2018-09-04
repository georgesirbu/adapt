![adapt-logo](https://user-images.githubusercontent.com/35819157/41377213-60ca05de-6f29-11e8-8c05-e29720906c90.png)


# Summary
ADAPT is a tool that performs automated Penetration Testing for WebApps. It is designed to increase accuracy, speed, and confidence in penetration testing efforts. ADAPT automatically tests for multiple industry standard OWASP Top 10 vulnerabilities, and outputs categorized findings based on these potential vulnerabilities. ADAPT also uses the functionality from OWASP ZAP to perform automated active and passive scans, and auto-spidering. Due to the flexible nature of the ADAPT tool, all of theses features and tests can be enabled or disabled from the configuration file. For more information on tests and configuration, please visit the ADAPT [wiki:](https://github.com/secdec/ADAPT/wiki)


# How it Works
ADAPT uses Python to create an automated framework to use industry standard tools, such as OWASP ZAP and Nmap, to perform repeatable, well-designed procedures with anticipated results to create an easly understandable report listing vulnerabilities detected within the web application.

## Automated Tests:
    * OTG-INFO-002 – Fingerprinting the Webserver
    * OTG-IDENT-004 – Account Enumeration
    * OTG-AUTHN-002 – Default Credentials
    * OTG-AUTHZ-001 – Directory Traversal
    * OTG-SESS-002 – Cookie Attributes
    * OTG-ERR-002 – Testing for Stack Traces
    * OTG-INPVAL-003 – HTTP Verb Tampering
    * OTG-CONFIG-006 – Test HTTP Methods
    * OTG-SESS-001 - Testing for Session Management Schema
    * OTG-AUTHN-001 - Testing for Credentials Transported over an Encrypted Channel
    * OTG-CONFIG-002 - Test Application Platform Configuration
    * OTG-CRYPST-001 - Testing for Weak SSL/TLS Ciphers, Insufficient Transport Layer Protection
    * OTG-CRYPST-002 - Testing for Padding Oracle
    * OTG-ERR-001 - Testing for Error Code
    * OTG-INPVAL-001 - Testing for Reflected Cross site scripting
    * OTG-INPVAL-002 - Testing for Stored Cross site scripting
    * OTG-AUTHN-003 - Testing for Weak lock out mechanism

## Installing the Plugin
1. [Detailed install instructions](https://github.com/secdec/ADAPT/wiki/Installation).


## License
Licensed under the [Apache-2.0](https://github.com/secdec/ADAPT/blob/master/LICENSE) License.

