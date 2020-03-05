---
layout: page_with_sidebar
permalink: /guide
title: Introduction
subtitle:
nextpage: /guide/get-started
---

This guide aims to help **practices**, **GP IT delivery partners** (referred to as ‘delivery partner’ throughout the guide) and **Commissioning Clinical Groups** (CCGs) plan and implement migrations from one foundation system (also known as ‘solution’) to another. Approaches to migration can differ by region. This guide contains a collection of common processes and activities to help the migration run smoothly.

This is a generic guide and may not cover everything that happens in your migration, but it does aim to cover the key activities and make suggestions on how to act on them. This guide can be used in conjunction with any deployment schedules and guidance issued by your new supplier.

{%- capture beta_version2 -%} 
This guide will continue to be updated as the GP IT Futures framework develops and matures.
{%- endcapture -%}
{%- include carecard.html content=beta_version2 accessibility_text="Please note" heading="Please note" markdown=true -%}

* * *

## Information Governance

Performing a migration inevitably involves access to—and processing of—significant amounts of patients’  personal data. It’s crucial, therefore, that all parties involved adhere to the laws, policies, standards and guidelines in respect to Information Governance, including:
<!-- [UPLIFT] The Supplier Compliance Team requested that we add references to these documents in the Migration Guide -->
>* [Access to Medical Reports Act (1988)](http://www.legislation.gov.uk/ukpga/1988/28/contents)
>* [Access to Health Records Act (1990)](http://www.legislation.gov.uk/ukpga/1990/23)
>* [NHS Act 2006 (Section 251)](http://www.legislation.gov.uk/ukpga/2006/41/section/251) (previously Section 60 of the Health and Social Care Act 2001)
>* [General Data Protection Regulation (GDPR)](https://ico.org.uk/for-organisations/guide-to-data-protection/guide-to-the-general-data-protection-regulation-gdpr/) (see [NHS Digital guidance on GDPR](https://digital.nhs.uk/data-and-information/looking-after-information/data-security-and-information-governance/information-governance-alliance-iga/general-data-protection-regulation-gdpr-guidance))
>* [NHS (Venereal Diseases) Regulations (1974)](http://www.legislation.gov.uk/uksi/1974/29/regulation/2/made)
>* [NHS Data Dictionary](https://www.datadictionary.nhs.uk/?_cldee=bGluZHNheWpveWNlQG5ocy5uZXQ%3d&recipientid=contact-8126f32424a0e61180f95065f38bd5b1-cc367001e5d34f55a9ebb2da53a0be7b&esid=2921a4d1-5a70-e711-810d-5065f38bf2f1&urlid=0)
>* [Records Management - NHS Code of Practice](https://digital.nhs.uk/data-and-information/looking-after-information/data-security-and-information-governance/codes-of-practice-for-handling-information-in-health-and-care/records-management-code-of-practice-for-health-and-social-care-2016) (DHSC)
>* Encryption guidance for health and care organisations<!-- [GAP] link missing for 'encryption guidance' reference, do we even need this reference? -->
>* [Chapter 8c of the General Practice GPG](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/215680/dh_125350.pdf)

<!--{%- capture test_care -%} 
Here is the list: 
* Blah blah blah blah
* bullet point 2 
* bullet point 3
{%- endcapture -%}
{%- include carecard.html content=test_care accessibility_text="Gaps to be confirmed" heading="Gaps to be confirmed" markdown=true -%}-->

* * *


## How long does a migration take?

The end to end migration process takes between 12-16 weeks. This is from the point of placing the order for the new system to the end of the  migration process.


## Overview of key phases

Migrations require a lot of planning and effort from practice staff. Breaking this activity into smaller incremental steps will make this process easier to manage. Here is an overview of the key phases…

{%- include steps/steps.html group='migration-key-phases' -%}
