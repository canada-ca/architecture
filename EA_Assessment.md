This is currently in development. The hope is to generate assessment questions that will help Enterprise Architecture review assessments to align with the TBS policy [https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=15249)

My goal:

 - to develop a list of questions that can be asked in an interview of a
   thing(service, solution, program, package).
 - to ask just enough question to ensure alignment ... I don't want to
   induce *death by questioning* to the assessment process

## Enterprise

 - What enterprise services are being used/reused ?
 - Does thing align to organizations strategic plan ? 
 - Does thing align to GC Digital principles ?
 - Is thing being tracked by TBS APM ? 

## Business

**Align to the GC Business Capability model**

 - Does this *thing* align to either the GC Business Capability model
   (GC BCM) or your departments own Business Capability model ?

**Design for Users First and Deliver with Multidisciplinary Teams**

 - Does this *thing* focus on the needs of users ?
 - Does this *thing* conform with accessibility and official languages requirements 
 
 **Design Systems to be Measurable and Accountable**

 - Does this thing produce routine reports ?
 - Does this *thing* have defined KPI's  ?

## Information

**Data Collection**

 - Does this *thing* collect data in a manner that maximizes use and
   reuse of data ?
 - Does this *thing* collect data in a manner that aligns to organization
   data standards ?
 - Does this *thing* collect data in a manner to ensure high quality yields ?
 
 **Data Management**
 - Does the data management for *thing* align with the departments data governance ?
	  - Has your organizations Data Management group been consulted ?
 - Have the data roles and responsibilities been defined for *thing* ? 

**Data Storage**

 - Is data stored in a secure manner in accordance to:
	 - National Cyber Security Strategy ?
	 - Privacy Act ?
 - Does it follow existing retention and disposition schedules ?
 - Is the data scan-able for discovery and accessibility ?

**Data Sharing**
 - Will the data for the application be shared/sharable :
	 - Source Code ?
	 - Configuration Files ?
	 - Knowledges Bases ?
	 - Database repositories ? 
	 - Etc.
 -  Will the data be exposed via an API ?
	 - Will the API be registered on the API store ?
 - Will the *thing* use an API's or other datasets ?


## Application
Has your organizations Application Management group been consulted ?
**Use Open Standards and Solutions by Default**

 - Were open source software, solutions and standards evaluated for
   *thing* ?
 - If open source was not possible was platform-agnostic COTS over proprietary COTS selected ?
 - Has all application assets been released under an appropriate open source software license 
	 - Source Code ?
	-	Scripts ?
	 - Configuration Files ?
 - Does this *thing* expose public facing data ?
 
 **Maximize Reuse**
 
 - Does the *thing* reuse existing services ?
 - Was this *thing* designed with the enterprise in mind ?
 - Does the *thing* align to:
	 - relevant standards
	 - best practices ?
 - Is the coding be share with :
	 - The public ?
	 - The government of Canada ?
  
**Enable Interoperability**
 - Has all functionality been exposes as consumable services ?
 - Does the thing align with Microservices methodology ?
 - Does the thing have an API interfacce
	 - Has it been enabled ?
	 - Has it been registered with the GC API Store ?
- Does the thing use containers ?

## Technology
Has your organizations Technology and Data-center Management group been consulted ?
**Use Cloud first**

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
 
**Design for Performance, Availability, and Scalability**

- Is the *thing* designed for resiliency ?
- Is the *thing* being monitored for service and availability ?
- Are the *things* response times being monitored for user acceptance ?
- Was the *thing* designed with a distributed architecture ?

## Security & Privacy

 - Has your organizations Security Management group been consulted ?
 - Has security been implemented security across all architectural domains ?
 - Has the *things* data and information been properly categorized to determine safeguards ?
 - Has a PIA been completed ?
 - Has a balance of securtity and user needs been established ? 

   
