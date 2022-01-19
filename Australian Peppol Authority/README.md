# Peppol Overview

The Peppol network is based on an open 4-corner model allowing the exchange of standardised messages, such as eInvoices. Access points connect users to the Peppol network – by connecting to one access point you connect to all.

Peppol is made up of 15 Peppol Authorities and 35 countries and is centrally managed through OpenPeppol. The ATO is the Australian Peppol Authority and is responsible for setting local requirements and managing participants of Peppol in Australia. Find out more about the Australian Peppol Authority.

The Peppol network is reliant on Peppol Service Providers to publish and find details about users such as their message delivery address and the types of messages they can receive. This allows electronic delivery of messages such as eInvoices through software to the correct recipient in the right way.

# Accreditation overview

Accreditation is a process a Peppol Service Provider must complete to transact in the Peppol Network. OpenPeppol is responsible for determining which Peppol Authority you will need to complete accreditation with.

To determine this you will need to register with [OpenPeppol](https://peppol.eu/get-involved/join-openpeppol/). OpenPeppol charge an annual membership fee based on a calendar year regardless of your accreditation status - as such we recommend reading the steps to accreditation before initiating this step.

If you have already been accredited with a Peppol Authority in another jurisdiction but want to provide your services to an Australian business, you will need to adhere to the Peppol Authority specific requirements which are listed on [Internationally accredited Peppol Service Provider](https://softwaredevelopers.ato.gov.au/internationally-accredited-peppol-service-provider).

To become an accredited Peppol Service provider it is essential to understand the Peppol environment and its structure.Below is a brief overview of key Peppol resources:

- [eDelivery network review](https://peppol.eu/what-is-peppol/peppol-transport-infrastructure/) and [specifications](https://peppol.eu/downloads/the-peppol-edelivery-network-specifications/)
- [Implementation Guide for Access Points, Public Key Infrastructure (PKI) certificate and Peppol Testbed guide](https://peppol.eu/downloads/ap-guidelines/)
- [Business interoperability specifications overview](https://peppol.eu/what-is-peppol/peppol-profiles-specifications/) and [Post award specifications](https://peppol.eu/downloads/post-award/)
- [Peppol Compliance Policy](https://peppol.eu/downloads/compliance/) 

Once you have reviewed these resources and are ready to proceed, follow the below steps.

# Steps to become an accredited Peppol Service Provider in Australia

The steps below will apply to Peppol Service Providers who have registered with OpenPeppol and have received advice to complete accreditation with the Australian Peppol Authority.

The time required to complete this process will vary and is dependent on the readiness of the individual Service Provider seeking accreditation.
The steps do not necessarily need to be completed in sequence, but all must be finalised and verified by the Australian Peppol Authority and OpenPeppol before a Service Provider is accredited to transact within the Peppol network.

1.	Submit expression of interest
2.	Legal agreements
3.	Due Diligence checks
4.	Complete A-NZ eInvoicing security questionnaire
5.	Test the service offering
6.	Receive accreditation
7.	Request Production Public Key Infrastructure (PKI) Certificate

## 1. Submit an expression of interest

To submit an expression of interest with the Australian Peppol Authority do this via [ATO Digital service provider (DSP) Portal](https://developer.sbr.gov.au/portal/servicedesk/customer/portal/1). You can find out how to register and access the Portal from [Online services for DSPs](https://softwaredevelopers.ato.gov.au/OnlineservicesforDSPs).

If you are not able to access the ATO DSP Portal because you are not eligible to register, you can submit a request for the EOI via eInvoicing@ato.gov.au.

Once registered we will provide a Peppol Service Provider onboarding pack that includes additional information to complete the accreditation process. We will endeavour to respond to expressions of interest within five business days.

## 2. Legal agreements

OpenPeppol and Peppol Authorities have recently endorsed new agreements (Peppol Service Provider Agreement) which come into effect from 1 July 2022.

### Accreditation prior to 1 July 2022

The Transport Infrastructure Agreements (TIA) sets the minimum requirements to be consistently applied throughout the entire Peppol eDelivery Network. The Annex 5 to the TIA contains the details of the additional requirements and criteria that apply to service providers operating in Australia. For Peppol service providers who are looking to become accredited prior to this date they will need to sign both the new and old agreements below:

- Transport Infrastructure agreement
- Annexes 1 to 6
- Peppol AP and SMP provider agreements
- Peppol Service Provider Agreement

### Accreditation post 1 July 2022

For Peppol service providers who are looking to become accredited post this date they will need to sign the Peppol Service Provider agreement with the Australian Peppol Authority. The Peppol Service Provider agreement is a legal agreement which outlines the roles and responsibility of both you, as the service provider, and us, as the Peppol Authority.

## 3. Due Diligence check

To protect the interests of end-users and the other service providers operating in the network, we will use the information obtained to conduct several due diligence checks.

The due diligence checks include:

- confirmation the entity providing the service is a registered business
- confirmation the entity providing the service is not insolvent
- confirmation the entity’s senior office holders are not banned, disqualified or bankrupt
- criminal record check.

You must also confirm your intent to procure / provide evidence of an enforceable professional indemnity insurance policy of at least $10 million AUD (or equivalent in other currency) per occurrence. This helps ensure that you can mitigate against the risk of claims extending to other eInvoicing network participants. This insurance must be in place before live connection to the eInvoicing network.

## 4. Complete A-NZ eInvoicing security questionnaire

All service providers are required to complete and submit the A-NZ eInvoicing security questionnaire.  The questionnaire requires evidence of the following:

Self-assessment or independent audit against ISO/IEC 27001 or ASD/NZ ISM, including suitable evidence for the following controls:
-  Encryption key management
-  Network segregation
-  Audit logging
-  Patch and vulnerability management program
-  Information security awareness, education and training
-  Physical and environmental security
-  Operational procedures and responsibility
-  System acquisition, development and maintenance – including secure coding practices
-  System access control
-  Personnel security
-  Backup
Encryption in transit (Access Points only).
Encryption at rest.
Security monitoring practices.
Multifactor authentication (Access Points only).

## 5. Test the service offering
To verify the service offering of the Peppol Service Provider conforms to Peppol specifications and the additional local requirements in Australia you are required to sequentially execute these steps.

### Step 1: Complete Unit testing
Complete unit testing in your own environment to verify that your service can send and receive Peppol BIS documents in line with the Peppol eDelivery Network specifications.

### Step 2: Obtain Test PKI Certificate
Obtain the test certificate via the [OpenPeppol Jira Service Desk portal](https://openpeppol.atlassian.net/servicedesk/customer/portal/1). On the portal main page select ‘PKI Certificate Request’ and complete the certificate request form. You will need to attach an up-to-date copy of your Peppol Service Provider agreement and company registration document as part of the request.Outstanding membership fees will need to be paid to OpenPeppol before the request will be processed. OpenPeppol will then assign the certificate request to us for final approval.

Once approved you, the Service Provider, will have 10 days to download your test certificate. Certificates not downloaded within this timeframe will expire. If this occurs, you will need to raise a new Service Desk request to have the certificate renewed.

### Step 3: Peppol acceptance testing – eDelivery Network compliance (AP only)

The Acceptance Test is conducted in the OpenPeppol central test bed and formally tests your compliance with Peppol eDelivery Network specifications. This test may be completed by you without OpenPeppol intervention, with the Test PKI Certificate acting as a logon to enter the central test bed from which the test may be executed. Acceptance Testing involves:

•	verification of your certificates (both the Peppol and TLS certificate)
•	validating your ability to send/receive business documents to/from the Test AP
•	generating acknowledgment of the documents sent.

Upon completion of the test, you must provide the results to OpenPeppol for verification. This can be done via the [Open Peppol Jira Service Desk](https://openpeppol.atlassian.net/servicedesk/customer/portal/1). In the portal select ‘Test and Onboarding’. OpenPeppol will notify us when you have successfully completed Acceptance Testing.

### Step 4: Complete Interoperability testing

Interoperability testing will be completed to ensure that you can send a Peppol invoice as per [A-NZ Peppol BIS 3.0 specifications](https://github.com/A-NZ-PEPPOL/A-NZ-PEPPOL-BIS-3.0) with an [Australian or New Zealand accredited access point](https://www.ato.gov.au/Business/eInvoicing/Finding-an-eInvoicing-accredited-service-provider/?=Redirected_URL).

We can help facilitate an Interoperability Test with an existing Australian accredited access point or access point who has adhered to the Australian Peppol Authority specific requirements. A lead time of two weeks is generally required to allow us to identify and engage a suitable test partner with whom the Interoperability Test can be scheduled. 

The specific use cases to be executed as part of the Interoperability Test will be provided at the time of testing.

Upon successful completion of Interoperability Testing, you will need to provide us with confirmation as per the guidelines provided in the testing document.

## 6. Receive accreditation

We will confirm all required activities have been successfully completed and notify you that the accreditation process has been finalised.
We will request additional information to add your solution to the list of [eInvoicing accredited service providers](https://www.ato.gov.au/business/eInvoicing/finding-an-eInvoicing-accredited-service-provider/) on the ATO website.

## 7. Request Production Public Key Infrastructure (PKI) Certificate

Request the production certificate through the [Open Peppol Jira Service Desk](https://openpeppol.atlassian.net/servicedesk/customer/portal/1). In the portal select ‘PKI Certificate Request’ and complete the certificate request form. You will need to attach an up-to-date copy of your Peppol Service Provider agreement and company registration document as part of the request.

Outstanding membership fees will need to be paid to OpenPeppol before the request will be processed. OpenPeppol will then assign the certificate request to us for final approval.Once approved you, the Service Provider, will have 10 days to download the production certificate.  Certificates not downloaded within this timeframe will expire. If this occurs, the Service Provider will need to raise a new Service Desk request to have the certificate renewed.

## Mutual accreditation with New Zealand

For Peppol Service Providers who are already accredited in New Zealand you can become mutually accredited with the Australian Peppol Authority. To initiate this process contact eInvoicing@ato.gov.au.

For access points who have completed all the steps of accreditation in Australia, they can request mutual accreditation with New Zealand by contacting einvoicing@mbie.govt.nz.

## Annual review of accredited Peppol Service Providers

It is expected that all accredited Peppol Service Providers will meet the requirements of accreditation on an on-going basis. An annual review of accredited Peppol Service Providers will take place to provide this assurance and include:

Provide an up to date provision of a current enforceable Professional Indemnity Insurance policy of at least $10 million AUD per occurrence (or equivalent in other currency) 
Senior office holders confirmed with subsequent due diligence checks
Adherence to A-NZ eInvoicing security requirements which includes: 
-  Completion of section A of the A-NZ eInvoicing Security Questionnaire.
-  Review your evidence to ensure it aligns to the current security requirements and is up to date. Submit updated evidence where required.
-  Advise if there have been changes to your business or product environment.

## Specifications and associated guidance notes

The Peppol network uses standardised messages to enable automation. Jurisdictions can create extensions to the base eInvoicing specification [BIS Billing 3.0](https://peppol.eu/what-is-peppol/peppol-profiles-specifications/)). Australia and New Zealand have worked together to create two extensions - the [A-NZ invoicing extension and A-NZ self-billing extension](https://github.com/A-NZ-PEPPOL/A-NZ-PEPPOL-BIS-3.0).
To assist with invoice processing in Australian and New Zealand we recommend implementing industry best practice fields as per the [A-NZ Invoice Practice Statement - Invoice Content](https://github.com/A-NZ-PEPPOL/A-NZ-Industry-Practice-Statements).

Specifications and associated guidance notes for your implementation can be found on [A-NZ Peppol GitHub](https://github.com/A-NZ-PEPPOL)

## Contact us

For further information and to provide feedback email eInvoicing@ato.gov.au

# Internationally Accredited Peppol Service Provider 

## Peppol specific requirements in Australia

The steps below will apply to Peppol Service Providers who have been domiciled overseas by Open Peppol and met requirements of another Peppol Authority but want to provide access point services to an Australian business.

The Peppol Authority specific requirements that must be met aligns to the accreditation steps an Australian Peppol Service Provider must meet. The time required to complete this process will vary and is dependent on the readiness of the individual Service Provider seeking accreditation.

These steps do not necessarily need to be completed in sequence, but all must be finalised and verified by the Australian Peppol Authority before a service provider is able to transact with an Australian business through the Peppol Network.

1.	Submit an expression of interest
2.	Legal Agreements
3.	Due diligence
4.	Complete the A-Z eInvoicing security questionnaire
5.	Interoperability testing
6.	Receive acknowledgment of meeting the Peppol Authority Specific Requirement

If you have questions on the process prior to submitting an expression of interest contact the Australian Peppol Authority via eInvoicing@ato.gov.au.

## 1. Submit an expression of interest

To submit an expression of interest with the Australian Peppol Authority do this via [ATO Digital service provider (DSP) Portal](https://developer.sbr.gov.au/portal/servicedesk/customer/portal/1). You can find out how to register and access the Portal from [Online services for DSPs](https://softwaredevelopers.ato.gov.au/OnlineservicesforDSPs).

If you are not able to access the ATO DSP Portal because you are not eligible to register, you can submit via eInvoicing@ato.gov.au.

Once registered we will provide an onboarding pack that includes additional information to complete the accreditation process. We will endeavour to respond to expressions of interest within five business days.

## 2. Legal Agreements

The legal agreements set the minimum requirements to be applied throughout the entire Peppol eDelivery Network. OpenPeppol and Peppol Authorities have recently endorsed new agreements which come into effect from 1 July 2022. For internationally accredited Peppol service providers to adhere to the requirements of the Australian Peppol Authority the requirements will change depending on the below dates.

### Accreditation prior to July 1, 2022

For internationally accredited Peppol service providers who are looking to become accredited or meet the Australian Peppol Authority Specific requirements prior to this date they will need to:

- Provide a copy of the signed Transport Infrastructure agreement, Peppol AP and SMP provider agreements.
- Sign the Australian Annex 5.

### Accreditation post July 1, 2022

For Peppol service providers who are looking to become accredited post this date they will need to provide a copy of the signed Peppol Service Provider agreement.

## 3. Due diligence

To protect the interests of end-users and the other service providers operating in the network, we will provide you with a form to complete to conduct due diligence checks, including:

- confirmation the entity providing the service is a registered business
- confirmation the entity providing the service is not insolvent
- confirmation the entity’s senior office holders are not banned, disqualified or bankrupt
- criminal record check.

We recognise that these checks are dependent on the information available in the local jurisdiction of the service provider.

You must also confirm your intent to procure/provide evidence of an enforceable professional indemnity insurance policy of at least $10 million AUD (or equivalent in other currency) per occurrence. This helps ensure that you can mitigate against the risk of claims extending to other eInvoicing network participants. This insurance must be in place before live connection to the eInvoicing network.

## 4. Complete the A-NZ eInvoicing security questionnaire

We will require you to complete the A-NZ eInvoicing security questionnaire to confirm the existence of appropriate security controls. The security control requirements include:

Self-assessment or independent audit against ISO/IEC 27001 or ASD/NZ ISM, including suitable evidence for the following controls:
- Encryption key management
- Network segregation
- Audit logging
- Patch and vulnerability management program
- Information security awareness, education and training
- Physical and environmental security
- Operational procedures and responsibility
- System acquisition, development and maintenance – including secure coding practices
- System access control
- Personnel security
- Backup
Encryption in transit (Access Points only).
Encryption at rest.
Security monitoring practices.
Multifactor authentication (Access Points only).

## 5. Interoperability testing

Interoperability testing will be completed to ensure that you can send a Peppol invoice as per the [A-NZ Peppol BIS 3.0 specifications](https://github.com/A-NZ-PEPPOL/A-NZ-PEPPOL-BIS-3.0) with an [Australian or New Zealand accredited access point](https://www.ato.gov.au/Business/eInvoicing/Finding-an-eInvoicing-accredited-service-provider/?=Redirected_URL).

We can help facilitate an Interoperability Test with an existing Australian accredited access point or access point who has adhered to the Australian Peppol Authority specific requirements. A lead time of two weeks is generally required to allow us to identify and engage a suitable test partner with whom the Interoperability Test can be scheduled.

The specific use cases to be executed as part of the Interoperability Test will be provided at the time of testing.

Upon successful completion of Interoperability Testing, you will need to provide us with confirmation as per the guidelines provided in the testing document.

## 6. Receive acknowledgement of meeting the Peppol Authority

We will confirm all required activities have been successfully completed and provide acknowledgement that you have met the Peppol Authority Specific Requirements.
We will also add you to the list of Australian [eInvoicing access point providers list](https://www.ato.gov.au/Business/eInvoicing/Finding-an-eInvoicing-accredited-service-provider/?=Redirected_URL) on the ATO website.

## Mutual acknowledgement with New Zealand

For access points who have already met the Peppol Authority Specific requirements of New Zealand you can receive mutual acknowledgement with the Australian Peppol Authority. To initiate this process contact eInvoicing@ato.gov.au.

For access points who have completed all the steps in Australia, they can request mutual acknowledgement with New Zealand by contacting einvoicing@mbie.govt.nz.
Annual Review of Peppol Specific requirements

## Annual review of accredited Peppol Service Providers

It is expected that all accredited Peppol Service Providers will meet the requirements of accreditation on an on-going basis. An annual review of accredited Peppol Service Providers will take place to provide this assurance and include:

Due diligence checks and provision of a current enforceable Professional Indemnity Insurance policy of at least $10 million AUD (or equivalent in other currency) per occurrence.
Adherence to A-NZ eInvoicing security requirements which includes: 
- Completion of section A of the A-NZ eInvoicing Security Questionnaire.
- Review your evidence to ensure it aligns to the current security requirements and is up to date. Submit updated evidence where required.
- Advise if there have been changes to your business or product environment.

## Specifications and associated guidance notes

The Peppol network uses standardised messages to enable automation. Jurisdictions can create extensions to the base eInvoicing specification [BIS Billing 3.0](https://peppol.eu/what-is-peppol/peppol-profiles-specifications/)). Australia and New Zealand have worked together to create two extensions - the [A-NZ invoicing extension and A-NZ self-billing extension](https://github.com/A-NZ-PEPPOL/A-NZ-PEPPOL-BIS-3.0).
To assist with invoice processing in Australian and New Zealand we recommend implementing industry best practice fields as per the [A-NZ Invoice Practice Statement - Invoice Content](https://github.com/A-NZ-PEPPOL/A-NZ-Industry-Practice-Statements).

Specifications and associated guidance notes for your implementation can be found on [A-NZ Peppol GitHub](https://github.com/A-NZ-PEPPOL)

## Contact us
For further information and to provide feedback email eInvoicing@ato.gov.au
