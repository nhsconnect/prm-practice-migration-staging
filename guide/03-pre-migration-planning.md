---
layout: page_with_sidebar
permalink: /guide/pre-migration-tasks
title: Pre-migration tasks
subtitle: Things to start doing to get ahead
nextpage: /guide/initial-data-production
previouspage: /guide/technical-survey
breadcrumbparent: /guide
---

This is the time to start completing the items discussed in the Kick-off.


## Request a data extract from your current supplier {#request-data-extract}

By now you should have [formally requested a data extract from your current supplier](/prm-practice-migration/guide/get-started#request-data-extract). Your current supplier must provide this extract according to the Data Migration Standard (DMI06). 
<!-- [UPLIFT] added reference to Data Migration Standard -->
If you do not have confirmation from the current supplier that the extract will be provided on the date requested, you need to chase this up with them. They must provide all the data extract(s) you require in a suitable, encrypted, electronic format as documented in the DDE. All data extracts must also contain the full set of audit trails, where applicable (see DMI07 and DMI26 for more details).

* * *
**_SLA:_**  Once a request is made for an extract, your old supplier has 5 working days to provide this to you/your new supplier.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 6)</em>
* * *
<!-- [UPLIFT] added reference to the Supplier SLA in terms of responding to queries from a Migration Management Agent -->

<!--The DDE is the 'Documented Data Extract' that shows what physical data is to be included in the extract and its format and structure (see DMI02).
 [UPLIFT] added reference to the Supplier SLA in terms of responding to a request for an extract -->

A data extract request will also need to be completed for any other supplier who will need to migrate data. For example, any document management and scanning solutions such as DocMan or anticoagulation management software such as INR Star.

__The request needs to be completed as early as possible__. The current suppliers have varying lead times/notice periods to provide this data upon request; for example, a supplier may require up to 5 weeks notice. __Any delays to giving notice may impact the migration timeline__.

## Clean up the current solution data

The new supplier (providing the new clinical solution) or GP IT delivery partner (such as a Commissioning Support Unit) can advise the Practice on any common/known data issues when migrating to the new solution (these may vary from solution to solution). 

Rectifying the data early and before the [Initial data production phase](initial-data-production) will reduce the amount of work the Practice needs to complete during later phases.

* * * 
**_SLA:_**  Reviewing the quality of the data in your current solution should not take more than 6 weeks. This review should include identifying any irregularities in the data, performing standard data quality checks and assessing any misused codes or concepts, such as clinical findings terms.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 11)</em>
* * *

<!-- [UPLIFT] added reference to Step 4 SLA from the Ancillary Document -->
<!-- [GAP] need to check whether 'Source Solution data quality review' is the same activity as 'Clean up the current system data' i.e. is the SLA here in the right place? -->

### Tasks include...

* The appropriate management of duplicate and orphaned records which will not migrate to the new solution


* Complete an information cleansing exercise to ensure only current letter templates and data entry templates are kept. Note; letter and data entry templates will need to be manually copied over. Completing this exercise will make it easier to identify which templates you need in the new solution


* Clearing down the practice inboxes, outstanding workflows and all open communication tasks, for example, pathology and registration;  as you approach the [Final data production day](/prm-practice-migration/guide/cutover-and-go-live#final-data-production), you will want to have zero tasks outstanding



## Data checking preparation {#data-checking-prep}

The new supplier (target) will provide a set of test criteria for data checking following the [Initial data production day](initial-data-production). The Practice will be asked to find a series of patient records that match these criteria (usually up to 20 records) and a selection of random records. Usually, the new supplier (target) or GP IT delivery partner (such as a Commissioning Support Unit) will assist with the initial selection of records before asking the Practice to complete finding the remaining patient records unaided.

The Practice will need to detail the selected patient records in a document provided by the new supplier (target). The list of selected patient records will need to be available on the [Initial data production day](initial-data-production).


### Is a reconciliation needed?

A reconciliation may be completed between Personal Demographics Service (PDS) through an Additional Service Request (ASR) to force a patient list synchronisation.

{%- capture lesson_learnt_1 -%}
__Recommendation__ The Personal Demographic Service and NHAIS can get out of sync. Thus the reconciliation and any outstanding registration for any patient needs to be done before Go Live. If not done before Go Live, patient information can be lost and it could also cause issues during data migration.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}
<!-- [GAP] need to check how practices request reconciliation -->


## Notification of 3rd parties and links

Refer back to the list created at the Kick-off of all the supporting/connecting solutions and community services that the Clinical solution or the practice works with, such as

* [Electronic Prescription Service (EPS)](https://digital.nhs.uk/services/electronic-prescription-service)


* [GP2GP](https://digital.nhs.uk/services/gp2gp)


* [Summary Care Records (SCR)](https://digital.nhs.uk/services/summary-care-records-scr)


* Pathology labs and any other services or providers that send information and results automatically to the current solution. For example, Bowel screening, Hospital letters, 111, Out of hours


* Pharmacies


* [Primary Care Support England](https://pcse.england.nhs.uk/)


* [Subsidiary and Third party solution suppliers](/prm-practice-migration/guide/pre-migration-tasks#subsidiary-suppliers), for example, DocMan or Apollo Scan for document scanning and management (see below)



## Subsidiary and Third party solution suppliers {#subsidiary-suppliers}

You may need to migrate data from Subsidiary suppliers (also referred to as [Lot 1 services](https://digital.nhs.uk/services/gp-systems-of-choice/gpsoc-services#lot-1-gp-principal-clinical-systems-and-subsidiary-modules)) as part of your principal clinical solution migration. For example, DocMan or Apollo Scan for document scanning and management. 

__Regardless of whether you plan to migrate away from the Subsidiary supplier or integrate with them, you will need to give notice to them of your solution change__. The notice period required will vary, for example, the Electronic Prescription Service may require 5 weeks, whereas another may require 5 days. 

   -- If you require a data extract from the Subsidiary supplier, you need to notify the Subsidiary Supplier well in advance of the date when you require the data extract to be completed

   -- The data extract from a Subsidiary supplier will need to be completed at the same point in time as any data extract is completed for your current clinical solution

   -- This applies to both the Initial data extract and the Final data extract

   -- Agree with the new solution supplier as to who and how the data extract will be collected from the subsidiary supplier

Please be aware that reconfiguration work may be required by a Subsidiary supplier after you have migrated to the new clinical solution ([Post Go-Live](post-go-live)) to integrate with the new principal clinical solution.


## Notification of patients
Start to display posters within the surgery advising of any disruption to services such as the ability to book appointments online and that patients may also be required to re-register on your new online service solution (if applicable). 

## Schedule any training

Schedule your training plan and book rooms. [Read more about training](training). 

## Check hardware and software deployment timelines

If the [Technical Survey](technical-survey) identified any additional hardware or software requirements, make sure to check in on the current status.
