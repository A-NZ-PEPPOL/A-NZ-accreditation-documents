# Accreditation overview

This page describes the process a Peppol service provider must complete to become an Australian accredited Peppol service provider and to be authorised to operate within Australia.

The ATO, in its role as the Australian Peppol Authority, sets the accreditation requirements in Australia that form part of the [Australian Peppol Authority Specific Requirements](https://openpeppol.atlassian.net/wiki/download/attachments/2889318401/Australia%20-%20Peppol%20Authority%20Specific%20Requirements.pdf?api=v2) 

The requirements of accreditation are in place to:

- protect the interests of end-users and other Peppol service providers
- ensure interoperability of the Peppol network and ability to send or receive valid A-NZ invoices
- mitigate against security risks to the network.

# Prior to commencing accreditation

For Peppol service providers seeking accreditation for the first time, you will need to contact [OpenPeppol General Support](https://openpeppol.atlassian.net/servicedesk/customer/portal/1) to determine your home Peppol Authority whom you will be required to complete accreditation with first. Open Peppol charges an [Annual membership fee]( https://peppol.eu/get-involved/join-openpeppol/) based on a calendar year; this is payable each year regardless of your accreditation status.

Before commencing accreditation, Peppol service providers should understand the technical, legal and policy framework of Peppol by reviewing the Peppol Technical and policy documents at the bottom of this page.

If service providers have questions or would like a meeting to discuss the Peppol framework or accreditation steps, reach out to eInvoicing@ato.gov.au or through [Online services for DSPs]( https://developer.sbr.gov.au/portal/servicedesk/customer/portal/1).

# Australian accreditation steps

The Australian accreditation process applies to Peppol service providers:

- with Australia as their home Peppol Authority as determined by OpenPeppol
- with a home Peppol Authority that is not in Australia but is seeking to operate in Australia.

The accreditation steps include:

1.	Submit an Expression of Interest
2.	Legal agreements
3.	Due Diligence checks
4.	Information Security Questionnaire
5.	Testing
6.	Receive accreditation

The time required to complete this process is dependent on the readiness of the individual Peppol service provider seeking accreditation.

## 1. Submit an expression of interest

To initiate the accreditation process, submit an expression of interest (EOI) by:

- using the [Online services for DSPs](https://developer.sbr.gov.au/portal/servicedesk/customer/portal/1) for ABN holders
- requesting the EOI from eInvoicing@ato.gov.au for non-ABN holders.

The EOI provides us with an overview of your company and solution. We will endeavour to respond to EOIs within 5 business days and offer an introductory meeting.

## 2. Legal agreements

The [Peppol Service Provider Agreement]( https://github.com/A-NZ-PEPPOL/A-NZ-accreditation-documents/raw/master/Australian%20Peppol%20Authority/PeppolServiceProviderAgreement_v4.0.1.docx) is a legal agreement outlining the roles and responsibilities for you, as the Peppol service provider, and your Peppol Authority.

### Australia is your home Peppol Authority

Provide a signed copy of the [Peppol Service Provider Agreement]( https://github.com/A-NZ-PEPPOL/A-NZ-accreditation-documents/raw/master/Australian%20Peppol%20Authority/PeppolServiceProviderAgreement_v4.0.1.docx) to the Australian Peppol Authority. A countersigned copy will be returned once all other steps of accreditation have been completed.

### Australia is not your home Peppol Authority

Provide a countersigned copy of the [Peppol Service Provider Agreement]( https://github.com/A-NZ-PEPPOL/A-NZ-accreditation-documents/raw/master/Australian%20Peppol%20Authority/PeppolServiceProviderAgreement_v4.0.1.docx) returned from your home Peppol Authority.

## 3. Due Diligence check

To protect the interests of end users and the other Peppol service providers operating in the network, we will use the information provided in the EOI to complete due diligence checks including:

- confirmation the entity providing the service is a registered business
- confirmation the entity providing the service is not insolvent
- confirmation the entity’s senior office holders are not banned, disqualified or bankrupt
- a criminal record check.

You must provide evidence of an enforceable professional indemnity insurance policy equivalent to at least A$1 million per occurrence. When procuring professional indemnity insurance, we recommend that the level of coverage is commensurate to your level of risk exposure and that you adjust to a higher level of insurance where applicable to ensure you can mitigate against the risk of claims extending to other eInvoicing network participants.

## 4. Complete A-NZ eInvoicing security questionnaire

All Peppol service providers are required to complete and submit the [A-NZ eInvoicing security questionnaire](https://github.com/A-NZ-PEPPOL/A-NZ-accreditation-documents/raw/master/Australian%20Peppol%20Authority/A-NZ_e-Invoicing_Security_Questionnaire_v1.docx).  
The security control requirements include:

- Self-assessment or independent audit against ISO/IEC 27001 or ASD/NZ ISM
- Encryption at rest.
- Security monitoring practices.
- Encryption in transit (Access Points only).
- Multifactor authentication (Access Points only).

For further information on security controls refer to [A-NZ Information Security guidance for eInvoicing Service Providers](https://github.com/A-NZ-PEPPOL/Guidance-documents/raw/master/GuidanceNote03_Information%20Security_v1.0.docx).

## 5. Test the service offering

You are required to complete testing to verify your service offering conforms to Peppol specifications and additional local requirements. There are 3 steps of testing required to be completed sequentially:

1.	Unit testing
2.	Peppol acceptance testing
3.	Interoperability testing

Note: Peppol service providers already accredited in another jurisdiction will only be required to complete interoperability testing.

### Step 1: Complete Unit testing

Complete unit testing in your own environment to verify that your service can send and receive Peppol BIS documents in line with the [Peppol eDelivery Network Specifications]( https://peppol.eu/downloads/the-peppol-edelivery-network-specifications/) 

### Obtain Test PKI Certificate

Obtain the test certificate via the contact [OpenPeppol JIRA service desk](https://openpeppol.atlassian.net/servicedesk/customer/portal/1)
On the portal main page, select ‘PKI Certificate Request’ and choose ‘test’ at the certificate purpose option. Complete the remaining fields and include any attachments as requested such as company registration details.

Once OpenPeppol approves, you will have 10 days to download your test certificate. Certificates not downloaded during this timeframe will expire and you will need to raise a new service desk request to have the certificate reissued.

### Step 2: Peppol acceptance testing – eDelivery Network compliance (Access Points only)

The Peppol acceptance test is conducted in the OpenPeppol central test bed and formally tests your compliance with the Peppol eDelivery Network specifications. This test may be completed by you without OpenPeppol intervention, with the Test PKI Certificate acting as a log on to enter the central test bed from which the test may be executed.

Acceptance Testing involves:

- verification of your certificates (both the Peppol and TLS certificate)
- validating your ability to send/receive business documents to/from the Test AP
- generating acknowledgment of the documents sent.

Once completed, submit the test results via the [OpenPeppol JIRA service desk](https://openpeppol.atlassian.net/servicedesk/customer/portal/1). On the portal main page, select ‘Test and Onboarding’ and complete the remaining fields. OpenPeppol will advise if the test results are accepted.

### Step 3: Complete Interoperability testing

Interoperability testing must be completed to ensure you can send or receive a valid [A-NZ invoice] (GitHub - A-NZ-PEPPOL/A-NZ-PEPPOL-BIS-3.0: Australia-New Zealand extensions to the Peppol BIS 3.0 specifications)  with an [Australian or New Zealand accredited Peppol service provider]( https://softwaredevelopers.ato.gov.au/accreditation-Peppol-service-provider-register). The test files and the interoperability testing document will be provided at the time of testing.

Peppol service providers should arrange interoperability testing with an [Australian or New Zealand accredited Peppol service provider]( https://softwaredevelopers.ato.gov.au/accreditation-Peppol-service-provider-register). Where you require help in engaging a Peppol service provider for this purpose we can assist you.

You will need to provide us with the interoperability test results.

## 6. Receive accreditation

### All Peppol service providers

Once you have successfully completed all the steps of the accreditation process, we will confirm you are now accredited in Australia. We will also advise you of your annual review date request details to support:

- listing your solution as an [Australian accredited Peppol Service Provider]( https://softwaredevelopers.ato.gov.au/accreditation-Peppol-service-provider-register)
- adding contacts for the service provider forum and monthly reporting
- mutual accreditation with New Zealand.

### Australian Peppol service providers ONLY

We will return a countersigned copy of the Peppol service provider agreement.

You will need to obtain a production certificate to begin transacting in the Peppol network. The production certificate is obtained via the [OpenPeppol JIRA service desk](https://openpeppol.atlassian.net/servicedesk/customer/portal/1). Select ‘PKI Certificate Request’, and choose ‘production’ at the certificate purpose option and complete remaining fields.

Once OpenPeppol approves your certificate, you will have 10 days to download your certificate. Certificates not downloaded within this timeframe will expire and you will need to raise a new Service Desk request to have the certificate reissued.

## Mutual accreditation with New Zealand

Through the Trans-Tasman single economic market agenda, the Australian and New Zealand governments announced a common approach to eInvoicing. With this common approach, the Australia and New Zealand Peppol Authorities have an aligned accreditation process that supports mutual accreditation of Peppol service providers between the two countries.

Once you are accredited in Australia, you can request mutual accreditation with New Zealand by directly contacting the New Zealand Peppol Authority at einvoicing@mbie.govt.nz.

## Accreditation annual review 

There will be an annual review of the accreditation status to ensure Peppol service providers continue to meet their obligations on an on-going basis. An annual review will include:

- due diligence checks completed by the Australian Peppol Authority
- provision of a current enforceable Professional Indemnity Insurance policy of at least A$1 million (or equivalent in other currency) per occurrence
- adherence to A-NZ eInvoicing security requirements, which includes
- completion of section A of the A-NZ eInvoicing Security Questionnaire
- reviewing your evidence to ensure it aligns to the current security requirements and is up to date, and submitting updated evidence where required
- advising if there have been changes to your business or product environment.

## Peppol technical and policy documents

- [Peppol eDelivery Network – overview]( https://peppol.eu/what-is-peppol/peppol-transport-infrastructure/) 
- [Peppol eDelivery network specifications]( https://peppol.eu/downloads/the-peppol-edelivery-network-specifications/) 
- [Access Point Implementation guides](https://peppol.eu/downloads/ap-guidelines/)
- [Peppol Business Interoperability Specification (BIS) overview](https://peppol.eu/what-is-peppol/peppol-profiles-specifications/ and [post-award BIS specifications and guidelines](https://peppol.eu/downloads/post-award/)
- [Peppol Service Provider Agreement](https://github.com/A-NZ-PEPPOL/A-NZ-accreditation-documents/raw/master/Australian%20Peppol%20Authority/PeppolServiceProviderAgreement_v4.0.1.docx) 
- [Peppol Internal Regulations](https://openpeppol.atlassian.net/wiki/download/attachments/2889252865/Internal%20Regulations%20-%20Use%20of%20Peppol%20Network_v1.0.1%20APPROVED%202022.06.21.pdf?api=v2)
- [Peppol operational procedures](https://openpeppol.atlassian.net/wiki/spaces/AF/pages/2891251733/Peppol+Interoperability+Framework+1+Juy+2022#B4.-Operational-Procedures) 

Specifications and associated guidance notes for your implementation can be found on [A-NZ Peppol GitHub](https://github.com/A-NZ-PEPPOL)

## Contact us

For further information and to provide feedback email eInvoicing@ato.gov.au
