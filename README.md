# SOC 2 Audit

## Objective

I completed a SOC 2 Capstone Project as part of the Symposia curriculum, where I gained hands-on experience in SOC 2 readiness and audit processes. For the fictional company Logger, I defined controls and test descriptions for key Trust Services Criteria, prioritized critical criteria, and recommended a SOC 2 report type to support their expansion into regulated industries. This project enhanced my understanding of SOC 2 compliance and its application in real-world scenarios

### Skills Learned

- **SOC 2 Readiness and Audit Processes:** Gained hands-on experience in preparing for and conducting SOC 2 audits, including defining controls and test descriptions.
- **Trust Services Criteria Prioritization:** Learned to identify and prioritize key Trust Services Criteria based on organizational needs.
- **Control Development and Testing:** Developed and tested controls aligned with SOC 2 requirements, ensuring compliance with industry standards.
- **Regulatory Compliance Strategy:** Recommended SOC 2 report types and strategies to support business expansion into regulated industries like healthcare and finance.

## Scenario

Logger is a US-based company that provides a 24x7x365 SOC-as-a-Service platform to help
organizations collect and analyze terabytes of log data from across their enterprise. In this case,
SOC stands for Security Operations Center. Log data can be ingested from different sources
using Cloud Connectors and are securely transferred to Logger’s platform over HTTPS. All of
Logger’s services are hosted in Microsoft Azure.
For the end users, Logger offers a simple-to-use and configurable web interface with a full suite
of capabilities that include alerting using machine learning models and an add-on service to help
customers offload the day-to-day management of these logs. Logger’s platform has a range of
authentication options including Single Sign On (SSO) using SAML or username and password
with Multi-Factor Authentication (MFA). The platform also uses role-based access controls to
manage user permissions across an account.
Logger has built its information security using the NIST CSF as a framework. The company has
policies and procedures in place along with a suite of controls that give them a decent maturity
rating against NIST CSF. While the company has successfully completed several customer
audits, it is not something they have had to deal a lot with yet.
In addition to the SaaS offering, Logger plans to introduce more managed services to help
provide monitoring services for customers.

## Project Scope

1. Describe the benefits of obtaining a SOC 2 audit report for Logger.
2. Decide on the SOC 2 report type.
3. Prioritize the Trust Services Criteria that make the most sense for Logger.
4. Write controls for 5 criteria.
5. Write test descriptions for the defined controls.

## Benefits of Obtaining a SOC 2 Audit Report

Logger would benefit significantly from obtaining a SOC 2 audit report. Firstly, it would enhance the company's credibility and trustworthiness, especially as it aims to expand into more regulated industries such as finance and healthcare. Secondly, it would demonstrate Logger's commitment to high standards of security and privacy, which is crucial for attracting and retaining clients. Lastly, it would facilitate compliance with industry regulations, thereby reducing legal risks and improving overall business resilience.

## Recommended SOC 2 Audit Type

I recommend a SOC 2 Type 2 audit, which evaluates the effectiveness of controls over a period rather than at a single point in time. This will provide a comprehensive assessment of Logger's control environment and demonstrate to potential clients that the company consistently maintains high security standards over time.

## Important Trust Services Criteria

1. **Confidentiality:** Given Logger's handling of potentially sensitive data, ensuring that information is protected and only accessible to authorized personnel is critical.
2. **Processing Integrity:** This ensures that the system processing is complete, valid, accurate, timely, and authorized, which is essential for maintaining the reliability and integrity of the terabytes of log data that Logger processes.
3. **Availability:** Since Logger provides a 24x7x365 service, it is important to ensure that systems are available and operational to meet clients' needs. This helps to maintain service reliability and client satisfaction.

## Controls for Criteria
