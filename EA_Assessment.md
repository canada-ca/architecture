# EA Assessment

This is currently in development. The hope is to generate assessment questions that will help Enterprise Architecture review assessments to align with the TBS policy [https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249)

Goals:

- to develop a list of questions that can be asked in an interview of a
  thing(service, solution, program, package).
- to ask just enough question to ensure alignment ... I don't want to
  induce *death by questioning* to the assessment process

## Enterprise

- Who is the business owner of this *thing* ?
- What enterprise services are being used/reused by this *thing* ?
- Does this *thing* align to organizations strategic plan ?
- Does this *thing* align to GC Digital Standards ?
- Is this *thing* being tracked by TBS APM ?
- Is this *thing* considered a “Mission Critical” (as per TBS APM Definition)?

## Business

### Align to the GC Business Capability model

- Does this *thing* align to either the GC Business Capability model
  (GC BCM) or your departments own Business Capability model ?

### Design for Users First and Deliver with Multidisciplinary Teams

- Who will be using this *thing* ?
- Is this *thing* available internally or externally or both?
- Does this *thing* focus on the needs of users ?
- Does this *thing* conform with accessibility and official languages requirements ?

### Design Systems to be Measurable and Accountable

- What are the business processes that are supported by this *thing* ?
- Does this thing produce routine reports ?
- Does this *thing* have defined KPI's  ?
- Are there any specific laws, regulations, or policies that this *thing* must be compliant with? Have these requirements been incorporated into the architecture and design ?
- Has a Business Impact Assessment been completed?
- What would the impact on the business be if the information was disclosed in an unauthorised manner?
- What would the impact on the business be if the integrity of the information was compromised?
- Is there a business continuity and disaster recovery plan that is tested on a regular basis to ensure the return to operational status with minimal disruption.

## Information

### Data Collection

- Does this *thing* collect data in a manner that maximizes use and
reuse of data ?
- Does this *thing* collect data in a manner that aligns to organization
data standards ?
- Does this *thing* collect data in a manner to ensure high quality yields ?

### Data Management

- Does the data management for *thing* align with the departments data governance ?
  - Has your organizations Data Management group been consulted ?
- Have the data roles and responsibilities been defined for *thing* ?

### Data Storage

- Is data stored in a secure manner in accordance to CSE-approved cryptographic algorithms and protocols ?
- Does it follow existing retention and disposition schedules ?
- Is data retained only for the minimum time necessary ?
- Is the data scan-able for discovery and accessibility ?
- Does the data back-up or archiving service ensure that business requirements related to protection against data loss are met? (I.e. does the service support the business Recovery Point Objective?)

### Data Sharing

- Has data been shared openly by default as per the Directive on Open Government, while considering existing laws and regulations for safeguarding of security and the privacy of data?
- Will the data for the application be shared/sharable :
  - Source Code ?
  - Configuration Files ?
  - Knowledges Bases ?
  - Database repositories ?
  - Etc.
- Will the data be exposed via an API ?
  - Will the API be registered on the API store ?
- Will the *thing* use an API's or other datasets ?
- Will data be shared in an open government context, and if so has a threat risk assessment been completed ?

### Data Protection

- Does the data back-up or archiving service ensure that business requirements related to protection against data loss are met? (I.e. does the service support the business Recovery Point Objective?)
- Is there a data backup strategy to ensure that it can recover from an incident that leads to data loss or corruption?
- Have requirements for the encryption of the information that will be placed in the *thing* been determined?
- Is data protected while in transit, in use and at rest using appropriate encryption and protocols ?
- Does the *thing* use only approved encryption protocols and algorithms (as defined in CSE IT Standards)?
- Does the party responsible for managing the cryptographic keys have a key management plan that meets the requirements defined in the CSE IT Security Guidance?

## Application

Has your organizations Application Management group been consulted ?
Has the architecture of this *thing* been reviewed by a security architect ?
Have security requirements been applied to the architecture of this *thing* ?

### Use Open Standards and Solutions by Default

- Were open source software, solutions and standards evaluated for
  *thing* ?
- If open source was not possible was platform-agnostic COTS over proprietary COTS selected ?
- Has all application assets been released under an appropriate open source software license
  - Source Code ?
- Scripts ?
  - Configuration Files ?
- Does this *thing* expose public facing data ?

### Maximize Reuse

- Does the *thing* reuse existing services ?
- Was this *thing* designed with the enterprise in mind ?
- Does the *thing* align to:
  - relevant standards
  - best practices ?
- Is the coding be share with :
  - The public ?
  - The government of Canada ?

### Enable Interoperability

- Will this *thing* require integration with other GC Applications or Cloud Services ?
- What security mechanisms have been implemented to safeguard the integration ?
- Is there a current Departmental Threat Assessment that supports this proposal ?
- Has all functionality been exposes as consumable services ?
- Does the thing align with Microservices methodology ?
- Does the thing have an API interface
  - Has it been enabled ?
  - Has it been registered with the GC API Store ?
- Are APIs developed and secured in accordance with the GC API Standards ?
- Have all APIs been developed to enforce appropriate authentication ?
- Does the thing use containers ?

### Secure Application Delivery

- Have secure protocols (e.g. HTTPS) been configured for publicly accessible websites and web services ?
- Have industry standard best practices for application security (e.g. OWASP) been applied ?
- Is development, test, and staging environment separate from the production environment? If so, how are they segmented ?
- Is there a formal Software Development Life Cycle (SDLC) process ? Does it include threat modeling?
- Is security testing integrated and automated in order to validate code and address vulnerabilities prior to deployment ?
- Is each release subject to a full secure code review ? Is a secure code review performed at least annually ?
- Has the application been audited against the OWASP Top 10 Application Security Risks ?
- Have appropriate measures been implemented to ensure that sensitive data is protected when stored and transmitted ?
- What measures are in place to ensure that the opportunity for accidental data leakage across application boundaries is minimized ?
- What measures are in place to ensure that only authorised parties can access sensitive information ?
- Are applications that store, process, handle, or have network access to sensitive information audited and assessed before use ?

## Technology

Has your organizations Technology and Data-center Management group been consulted ?

### Use Cloud first

- Were cloud solutions evaluated by priority ?

  1. SaaS
  2. PaaS
  3. IaaS

- Were data center preferences evaluated by priority ?
  1. Public Cloud
  2. Hybrid Cloud
  3. Private Cloud
  4. Non-Cloud

- Is the *thing* resistant to vendor lockin ?

### Design for Performance, Availability, and Scalability

- Is the *thing* designed for resiliency ?
- Is the *thing* being monitored for service and availability ?
- Are the *things* response times being monitored for user acceptance ?
- Was the *thing* designed with a distributed architecture ?
- Has the *thing* been architected to support new technology insertion with minimal disruption to existing programs and services ?
- Do you have an approach to ensure that your production environment remains consistent and controllable ?
- Do you test and certify components in each layer of the technology stack for security vulnerabilities ?
- Has a continuity plan been developed to support recovery activities ?

## Security & Privacy

How security been incorporated into the project governance, working groups, development and implementation teams, etc.?
Has your organizations Security Management group been engaged ?
Has security been implemented across all architectural domains ?
Has a balance of security and user needs been established ?

### Risk-based Approach

- Is there an IT security risk management framework that will be applied (e.g. ITSG-33 security guidance) ?
- Are risk assessments conducted throughout the development of the system and ensure appropriate safeguards to be applied, as per the Policy on Government Security ?
- Have security activities and resources been integrated into the overall project plan, schedule, costs. etc.? Can you describe the different types of security resources used on the project (security architect, security assessor, etc.) ?
- Is there a documented process for identifying, understanding new or ongoing security and privacy threats and the process for managing them ?
- Does the service have any dependency on any third parties (e.g. outsourcers, subcontractors or another service provider) that introduce additional risks ?

### Design for Security and Privacy

- Has security categorization been performed based on the degree of injury that could be expected to result from a compromise of its confidentiality, integrity and availability ?
- Have graduated safeguards that are commensurate with the security category of the information and assets been implemented ? Are these security measures and privacy protections appropriate and cost-effective, and proportionate to user and business needs?
- Has a threat assessment been conducted to determine which threat actors would be applicable to the business area (e.g. hackers, activists, criminal organizations, etc.)
- Has a defense-in-depth approach been applied to the design of the *thing* to reduce exposure to threats and minimize the degree of compromise ?
- Has the *thing* been designed in such a way that it:
  - Prioritizes ease of use in security design to make security simple for users ?
- Protects from common security vulnerabilities ?
- Exposes only the interfaces necessary to operate the service ?
- Is resilient and can be rebuilt quickly to a known clean state in the event that a compromise is detected ?
- Fails secure even if the system encounters an error or crashes ?
- Are appropriate build and hardening standards defined, documented, and deployed for the *thing*?

### Secure Access to Systems and Services

- Does the *thing* align with GC direction on identity management ?
- Does the *thing* leverage GC authentication services ?
- What is the Level of Authentication required for the *thing* ?
- What are the identification and authentication mechanisms that will be used ?
- Is user access to service interfaces constrained to authorised individuals, processes, and/or devices with clearly defined roles and an appropriate level of assurance before granting access to the *thing* ?
- Does the *thing* separate and compartmentalise user responsibilities and privileges ? Are the least set of privileges necessary to complete the job assigned to authorized roles ?
- Is there a higher level of assurance required that the party asserting an identity is the authorised user of the account when authenticating to the service?
- Is multi-factor authentication implemented to protect against unauthorized access ?
- Is there an effective process that is audited at regular intervals to ensure that identities and user accounts are appropriately managed and protected throughout their lifecycle?
- Are all passwords encrypted, especially system/service administrators, in accordance with GC password guidance?

### Ongoing Maintenance and Monitoring

- Have processes been implemented to ensure that the *thing* is operated and managed in in order to impede, detect or prevent attacks ?
- Does the organization continuously monitor system events and performance ?
- Are all relevant security events and logs collected at infrastructure, operating system, and application levels to support root-cause analysis and incident investigation ?
- Does the *thing* use a trusted time source and protect audit logs against modification, deletion, and/or inappropriate access ?
- Are security advisories and patches for components used by the *thing* subscribed to and monitored ?
- Are security-related patches and updates promply applied to reduce exposure to vulnerabilities ? Is there a risk-based mitigation strategy in place for when patches can’t be applied ?
- Is there a formal incident response and management process and plans that clearly specifies how to detect and respond to information security incidents and privacy breaches ? Is this plan tested on a regular basis ?

### Privacy by Design

- Is there personal information being processed or stored in the *thing*?
- Has it been determined if a Privacy Impact Assessment is required ?
- Have appropriate measures been implemented to assure the protection of personal information ?
- Is a privacy by design approach been applied when designing the *thing* ?
