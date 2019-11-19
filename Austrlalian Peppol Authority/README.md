# Accreditation Process
This following information describes the process and requirements that a Service Provider must complete to become an accredited provider of Access Point (AP) and/or Service Metadata Publisher (SMP) services on the Pan European Public Procurement Online (PEPPOL) eDelivery Network in Australia.

# On this page
* What is accreditation?
* How do I get accredited?
* Service Provider accreditation process
* Established PEPPOL Service Provider accreditation process

# What is accreditation?
The PEPPOL Framework sets out PEPPOL’s standards and organisational interoperability requirements for providers of AP and/or SMP services. The high level of interdependency of participants in such an environment means that interoperability across the PEPPOL eDelivery Network is critical.

The Australian PEPPOL Authority (‘we’/’us’) has implemented this accreditation process to:

ensure Service Providers have the technical capability and compatibility needed to interoperate within the network in accordance with the PEPPOL Framework
help maintain reliability and stability in the network operations
manage risks which might damage the reputation of, and/or trust in the network.
Through this process the Service Provider (‘you’) can also choose to be recognised by the New Zealand (NZ) PEPPOL Authority as an accredited NZ Service Provider.

# How do I get accredited?
The following information has been divided into two processes:

* Service Provider accreditation process - outlines the process for a new Service Provider entering the PEPPOL eDelivery network.
* Established PEPPOL Service providers’ accreditation process - outlines the process for an existing Service Provider already operating in the PEPPOL eDelivery network.

# Service Provider accreditation process
The following steps outline the process a new PEPPOL Service Provider must complete to become accredited. The time required to complete this process will vary and is dependent on the readiness of the individual Service Provider seeking accreditation.

These steps do not necessarily need to be completed in sequence but all must be finalised and verified by us and OpenPEPPOL before a Service Provider is accredited to transact within the PEPPOL network.

1. Join OpenPEPPOL
2. Expression of interest
3. Sign Transport Infrastructure Agreement (TIA)
4. Complete due diligence
5. Complete security questionnaire
6. Testing
7. Receive accreditation
8. Proceed into production

## 1. Join OpenPEPPOL
OpenPEPPOL membership is mandatory for all Service Providers who intend to offer AP and or SMP services within the PEPPOL network.

You can apply to become an OpenPEPPOL member at any time by contacting info@peppol.eu and completing the registration forms.

All members of OpenPEPPOL are required to pay an annual subscription fee to support the purposes and activities of the Association. The fee payable will depend on the Service Provider’s membership category – refer to the OpenPEPPOL website for further details.

It is strongly recommend that Service Providers engage with one of the OpenPEPPOL Coordinating Communities after joining OpenPEPPOL as a member. Participation in these communities will provide you with an opportunity to network with established PEPPOL members (across multiple countries and industries) and benefit from their experience.

## 2. Expression of Interest
A Service Provider interested in becoming accredited needs to submit an expression of interest with the PEPPOL Authority.  

The ATO operates the Australian PEPPOL Authority. Expressions of interest can be submitted to us via the ATO Digital Service Provider (DSP) Portal.  You can find out how to register and access the Portal from Online services for DSPs.   

We will endeavour to respond to expressions of interest within two business days. The response will include a PEPPOL Service Provider onboarding pack – a zip file that includes additional information you will need to complete the accreditation process.

## 3. Sign the Service Provider Transport Infrastructure Agreement
Following membership approval, you will need to sign the Transport Infrastructure Agreement (TIA) with us. There are separate agreements for AP providers and SMP providers.

You will also be given to opportunity to sign the New Zealand Annex 5 to be automatically recognised as an accredited Service Provider in both jurisdictions following the completion of this process.

The purpose of the TIA and the annexes is to define the general principles for the operation of the PEPPOL Transport Infrastructure and clarify the role and responsibilities of both you as Service Provider and us as the PEPPOL Authority.

The TIA set of minimum requirements to be consistently applied throughout the entire PEPPOL eDelivery Network. Annex 5 to the TIA contains the details of the additional requirements and criteria that apply to Service Providers operating in Australia.

## 4. Due Diligence checks
To protect the interests of end-users and the other Service Providers operating in the network, we will use the information obtained in Annex 1 of the TIA to conduct a number of due diligence checks.

The due diligence checks include:

* confirmation the entity providing the service is a registered business
* confirmation the entity providing the service is not insolvent
* confirmation the entity’s senior office holders are not banned, disqualified or bankrupt
* criminal record check.

You must also confirm your intent to procure / provide evidence of an enforceable professional indemnity insurance policy of $10 million (or greater) per occurrence in the country’s currency. This helps ensure that you can mitigate against the risk of claims extending to other e-invoicing network participants. This insurance must be in place before live connection to the e-invoicing network.

Some of the information collected may need to be refreshed annually to keep the records up-to-date and accreditation is maintained.

## 5. Complete Security Questionnaire
All Service Providers are required to complete and submit a security questionnaire via the ATO DSP portal. The questionnaire requires evidence of the following:

* Self-assessment or independent audit against ISO/IEC 27001 or ASD/NZ ISM. This includes suitable evidence for the following controls:
  * Encryption key management
  * Network segregation
  * Audit logging
  * Patch and vulnerability management program
  * Information security awareness, education and training
  * Physical and environmental security
  * Operational procedures and responsibility
  * System acquisition, development and maintenance – including secure coding practices
  * System access control
  * Personnel security
  * Backup
* Encryption in transit (Access Points only)
* Encryption at rest
* Security monitoring practices
* Multifactor authentication (Access Points only)

## 6. Test the Service Offering
To verify the AP/SMP service offering conforms to PEPPOL specifications (and the additional local requirements) you are required to execute testing as per the following requirements:

## Unit Testing (AP and SMP)
It is strongly recommended that you complete unit testing in their own environment to verify that their service is able to send and receive PEPPOL BIS documents in line with the PEPPOL eDelivery Network specifications.

## Obtain Test PKI Certificate (AP only)
Before you can execute the next phase, PEPPOL Acceptance Testing, you will need to obtain a Test PKI Certificate. A test certificate is needed to access the PEPPOL central test bed and execute the Acceptance Test use cases.

The test certificate must be requested via the OpenPEPPOL Jira Service Desk portal. This portal is open to the public meaning no login details are required to access it. On the portal main page select ‘PKI Certificate Request’ and complete the certificate request form. You will need to attach an up-to-date copy of their Annex 1 and company registration document as part of the PKI Certificate Request.

OpenPEPPOL will review the request for completeness and verify your membership status. If any membership fees are outstanding you will be asked to pay these before the request will be processed. OpenPEPPOL will then assign the certificate request to us for final approval.

Once approved, the Service Provider will have 10 days to download their test certificate. Certificates not downloaded within this timeframe will expire. If this occurs, you will need to raise a new Service Desk request to have the certificate renewed.

## PEPPOL Acceptance Testing – eDelivery Network compliance (AP only)
The Acceptance Test is conducted in the OpenPEPPOL central test bed and formally tests your compliance with PEPPOL eDelivery Network specifications. This test may be completed by you without OpenPEPPOL intervention, with the Test PKI Certificate acting as a logon to enter the central test bed from which the test may be executed. Acceptance Testing involves:

verification of your certificates (both the PEPPOL and TLS certificate)
validating your ability to send/receive business documents to/from the Test AP
generating acknowledgment of the documents sent.
Upon completion of the test, you must provide their results to OpenPEPPOL for verification. OpenPEPPOL will notify us when you have successfully completed Acceptance Testing.

### Interoperability Testing (AP and SMP providers)
You can notify us when you are ready to complete interoperability via the ATO DSP Portal. The specific use cases to be executed as part of the Interoperability Test are outlined in the Service Provider onboarding pack.

We will facilitate an Interoperability Test with an existing PEPPOL AP provider.

Test scheduling
It is expected that you notify us of your intended test commencement date as soon as practicable following the successful completion of PEPPOL Acceptance Testing via the ATO DSP Portal.

A lead time of two weeks is generally required to allow us to identify and engage a suitable test partner (existing AP provider) with whom the Interoperability Test can be scheduled.

Test closure memo
Upon successful completion of Interoperability Testing you will need to provide us with confirmation.

## Receive Accreditation
We will confirm all required activities have been successfully completed and notify you that the accreditation process has been finalised.

We will also add you to the register of accredited Service Providers.

## Request Production PKI Certificate
Once accredited, the final step for you is to request your Production PKI Certificate be issued by OpenPEPPOL. The Production PKI Certificate allows you to prove they are a trusted network participant and begin transacting within the PEPPOL network.

The production certificate can be requested via the OpenPEPPOL Jira Service Desk portal. In the portal select ‘PKI Certificate Request’ and complete the certificate request form. You will again need to attach an up-to-date copy of their Annex 1 and company registration document as part of their Production PKI Certificate Request.

OpenPEPPOL will review the request for completeness and re-verify your membership status. If any membership fees are outstanding you will be required to pay these before the request will be processed. OpenPEPPOL will then assign the production certificate request to us for final approval.

Once approved, you will have 10 days to download their production certificate. Certificates not downloaded within this timeframe will expire. If this occurs, the Service Provider will need to raise a new Service Desk request to have the certificate renewed.

# Established PEPPOL Service Provider accreditation process
Established PEPPOL Service Providers can apply to be added to the register of accredited Service Providers on the Australian PEPPOL Authority website.

A streamlined accreditation process has been put in place for established PEPPOL Service Providers that have already signed the TIA in another jurisdiction.

The time required to complete this process will vary and is dependent on the readiness of the individual Service Provider seeking accreditation.

These steps do not necessarily need to be completed in sequence, with some being able to be actioned concurrently, but all must be finalised and verified by us before you will be recognised as accredited in the Australian market.

1. Expression of interest
2. Sign A-NZ Annex 5
3. Complete security questionnaire
4. Interoperability testing
5. Receive accreditation
## 1. Expression of Interest
You will need to submit an expression of interest with the PEPPOL Authority.
If your organisation has an Australian presence we recommend that you submit via the ATO Digital Service Provider (DSP) Portal. You can find out how to register and access the Portal from Online services for DSPs.   

If you are not able to access the ATO DSP Portal you can submit an EOI email.

## 2. Sign Annex 5
An established PEPPOL Service Provider has already signed the TIA in another jurisdiction so is not required to also sign the Australian TIA. However, in order to be recognised as an accredited AP provider in Australia, you must sign the Australian Annex 5.

The purpose of Annex 5 is to outline the additional requirements and criteria that apply to Service Providers operating in Australia.

## 3. Due Diligence
To protect the interests of end-users and the other Service Providers operating in the network, we will provide you with a form to complete to conduct a number of due diligence checks.

The due diligence checks include:

* confirmation the entity providing the service is a registered business
* confirmation the entity providing the service is not insolvent
* confirmation the entity’s senior office holders are not banned, disqualified or bankrupt
* criminal record check.

We recognise that these checks are dependent on the information available in the local jurisdiction of the Service Provider.

You must also confirm your intent to procure / provide evidence of an enforceable professional indemnity insurance policy of $10 million (or greater) per occurrence in the country’s currency. This helps ensure that you can mitigate against the risk of claims extending to other e-invoicing network participants. This insurance must be in place before live connection to the e-invoicing network.

Some of the information collected may need to be refreshed annually to keep the records up-to-date and ensure accreditation is maintained.

## 4. Complete the security questionnaire
We will require you to complete the security questionnaire to confirm the existence of appropriate security controls.

The security control requirements include:

* Self-assessment or independent audit against ISO/IEC 27001 or ASD/NZ ISM. This includes suitable evidence for the following controls:
  * Encryption key management
  * Network segregation
  * Audit logging
  * Patch and vulnerability management program
  * Information security awareness, education and training
  * Physical and environmental security
  * Operational procedures and responsibility
  * System acquisition, development and maintenance – including secure coding practices
  * System access control
  * Personnel security
  * Backup
* Encryption in transit (Access Points only)
* Encryption at rest
* Security monitoring practices
* Multifactor authentication (Access Points only)

The evidence collected will need to be refreshed annually to keep the records up-to-date and ensure that accreditation is maintained.

## 5. Interoperability testing
We will facilitate an Interoperability Test with an existing PEPPOL AP provider to confirm that you are able to:

establish compatibility with another Australian PEPPOL AP, and
validate conformance with local BIS requirements (that is, validate the payload)
The specific use cases to be executed as part of the Interoperability Test are included in the Service Provider on-boarding pack.

## Test scheduling
A lead time of two weeks is generally required to allow us time to identify and engage a suitable partner (existing AP provider) with whom the Interoperability Test can be scheduled.

## Test closure memo
Upon completion of the Interoperability Test you will need to provide evidence and confirm completion of testing with us.

# Contact us
For further information and to provide feedback email e-invoicing@ato.gov.au