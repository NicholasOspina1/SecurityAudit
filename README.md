# Security Audit for Botium Toys


-------

# Description <a name="description">

I conducted an internal security audit evaluation for Botium Toys, a fictional toy company. This assessment was completed as a component of my cybersecurity portfolio and as part of the <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Google Cybersecurity Professional Certificate</a> on Coursera, specifically in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> "Play It Safe: Manage Security Risks" </a> Course.


The goal of this project is to audit Botium Toys' cybersecurity action. According to the audit, current business practices must be compatible with industry guidelines and optimal procedures . The audit's objectives include presenting a general plan for enhancing the organization's security posture as well as mitigation recommendations for vulnerabilities identified as "high risk." The audit team must communicate with stakeholders, offer improvement strategies and efforts, and document their results.

# Scenario  <a name="scenario">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the **National Institute of Standards and Technology Cybersecurity Framework** (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of their security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department.

------------------------


The goals for Botium Toys’ internal IT audit are:
- To adhere to the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential
management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements

   
## Internal Security Audit Process  <a name="workflow">
The internal security audit can be divided into two distinct phases, each with their own instructions.

### Part 1
1. Evaluate the scope of the audit, its objectives, and perform a risk assessment.
2. Execute the audit by following these steps:
   - Perform a Controls Assessment
     - Identify which controls require implementation.
     - Assess the priority of each selected control (i.e., whether it should be implemented immediately or in the future).
   - Complete the compliance checklist
     - Provide explanations for the necessity of complying with chosen regulations and standards.
### Part 2
1. Examine the outcomes and deliverables achieved in Part 1, Step #2.
   - Take note of the discoveries made.
   - Think about ways to communicate your recommendations to stakeholders in a concise manner.
2. Send the findings and recommendations to stakeholders in a clear and brief manner.


Controls Assessment  <a name="control-assessment">
===================


Current Assets 
--------------

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs 

- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.

- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management

- Internet access

- Internal network

- Vendor access management

- Data center hosting services 

- Data retention and storage

- Badge readers

- Legacy system maintenance: end-of-life systems that require human monitoring

### Administrative Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | X | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | X | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | X | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | X | High/Medium |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | X | High |

### Technical Controls 
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | N/A | N/A |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | X | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | X | High/Medium |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | X | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | X | High/Medium |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | X | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X | High |


### Physical Controls
| Control Name | Control type and explanation | Needs to be implemented (X) | Priority |
| --- | --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | X | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | X | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | X | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | X | Low |
| Locks | Preventative; physical and digital assets are more secure | X | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | X | Medium |

Compliance Checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.
   
I discovered that Botium Toys must comply with the following guidelines:
     
-   General Data Protection Regulation (GDPR)
      - GDPR is a European Union (E.U.) general data regulation that protects the processing of E.U. citizens' data and their right to privacy in and out of E.U. territory. Additionally, if a breach occurs and a E.U. citizen's data is compromised, they must be informed within 72 hours of the incident.
         - Explanation: Botium Toys is growing its range of services and managing of customer data worldwide, and it is in focus for compliance with GDPR for its management of financial and personal data for customers in the European Union.
   

-   Payment Card Industry Data Security Standard (PCI DSS)

    - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

       - Explanation: To handle both in-person and online payments, as well as effectively store and oversee customer credit card information worldwide, Botium Toys is obligated to adhere to PCI DSS standards. Given the possible consequences, it's essential to treat these requirements and compliance with utmost seriousness. Failing to comply with this standard carries significant penalties, including monthly fines (ranging from 5,000 to 100,000 USD), expenses related to forensic audits in case of a data breach, limitations on payment brands, damage to the brand's reputation, and potential legal costs. 


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

      - Explanation: Botium Toys must set up and uphold suitable user access protocols for both its internal staff and external personnel to reduce risks and guarantee data security. These two standards assess the efficiency of a company's internal safeguards. While SOC1 centers on controls related to financial reporting, SOC2 specifically addresses information security controls, particularly focusing on the safety of customer data.
----------------
   

# Stakeholder Memorandum <a name="stakeholder-memo">

TO: IT Manager, Stakeholders

FROM: Nicholas Ospina\
DATE: 07/15/2023\
SUBJECT: Internal IT Audit Findings and Recommendations

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.

**Scope:**

- The following systems are in scope: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool. We will assess these systems in the following aspects:

  - Evaluating existing user permissions.

  - Reviewing the effectiveness of current implemented controls.

  - Assessing the adequacy of current procedures and protocols.

- Our objective is to ensure that the existing user permissions, controls, procedures, and protocols are in accordance with GDPR, PCI DSS, and compliance standards. Additionally, we will confirm that the current technology and assets, including both hardware and system access, are accurately documented.

**Goals:**

- Adhere to the National Institute of Standards and Technology Cybersecurity
Framework (NIST CSF).

- Establish a better process for their systems to ensure they are compliant.

- Fortify system controls.

- Implement the concept of least permissions when it comes to user credential management.

- Establish their policies and procedures, which includes their playbooks.

- Ensure they are meeting compliance requirements

**Critical findings** (must be addressed immediately):

 Multiple controls need to be developed and implemented to meet the audit goals, including:

- Principle of Least Privilege and Separation of duties.

- Disaster recovery plans.

- Password, Access control, and Account management policies.

- Intrusion Detection System (IDS).

- Encryption (secure website transactions containing sensitive information).

- Backups.

- Implementation of a Password management system.

- Antivirus (AV) software.

- Manual monitoring, maintenance, and intervention for legacy systems.

- Closed-circuit television (CCTV) surveillance.

- Locks.

- Locking cabinets (for network gear).

- Fire detection and prevention (fire alarm, sprinkler system, etc.)

- Policies need to be developed and implemented for the following:

  - Achieving compliance with PCI DSS and GDPR regulations.
  
  - Adhering to SOC1 and SOC2 guidelines concerning user access policies and overall data security.

**Findings** (should be addressed, but no immediate need):

The following physical controls should be considered in the future once the critical findings have been resolved:

- Time-controlled safe

- Adequate lighting

- Signage indicating alarm service provider for restricted areas

**Summary/Recommendations:**

It is advisable to promptly address significant compliance issues related to PCI and GDPR, especially since Botium Toys is expanding its services to include international customers, including those in the European Union. To align with the audit objective of implementing the principle of least privilege, it is recommended to develop policies and procedures based on SOC1 and SOC2 guidance for user access and overall data security.

To ensure business continuity in the face of various incidents, such as physical disasters like fires or worst-case scenarios like cyberattacks or technical disruptions affecting productivity, it is recommended to establish disaster recovery plans and maintain backups as part of a comprehensive data and system resilience strategy. Considering the implementation of fire detection and prevention systems is also worthwhile for physical security against potential attacks.

Integrating Intrusion Detection Systems (IDS) and antivirus (AV) software into the existing systems will enhance the ability to detect and mitigate potential risks, taking into account the legacy systems that require manual monitoring and intervention.

For securing assets at Botium Toys' physical location, it is advisable to utilize locks and closed-circuit television (CCTV) for physical asset security and threat monitoring. Installing a time-controlled safe, adequate lighting, and signage indicating the alarm service provider will further enhance the overall security posture of Botium Toys.   
