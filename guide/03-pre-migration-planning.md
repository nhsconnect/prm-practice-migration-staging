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

The new supplier (providing the new clinical solution) or GP IT Delivery Partner (such as a Commissioning Support Unit) can advise the Practice on any common/known data issues when migrating to the new solution (these may vary from solution to solution). 

Rectifying the data early and before the [Initial data production phase](initial-data-production) will reduce the amount of work the Practice needs to complete during later phases.

* * * 
**_SLA:_**  Reviewing the quality of the data in your current solution should not take more than 6 weeks. This review should include identifying any irregularities in the data, performing standard data quality checks and assessing any misused codes or concepts, such as clinical findings terms.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 11)</em>
* * *

<!-- [UPLIFT] added reference to Step 4 SLA from the Ancillary Document -->
<!-- [GAP] need to check whether 'Source Solution data quality review' is the same activity as 'Clean up the current system data' i.e. is the SLA here in the right place? -->

### Tasks include...

* Requesting a reconciliation of the practice database against the PCSE database (For more information: see a [Guide to Patient Registrations](https://pcse.england.nhs.uk/services/registrations/)
* Identifying any local or practice created codes and mapping these to the appropriate Read/SNOMED codes if available 
* Confirm which patients have any current issues of un-mapped codes and as part of the clean-up of the current system data, map those drugs and devices according to the [Dictionary of Medication and Devices (dm+d)](https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/dictionary-medicines-and-devices-dmd) 
* Establishing which letter and data entry templates should be transferred into the new system. These will need to be manually copied over.

## Notifying third parties and links

Refer back to the list created at the Kick-off of all the supporting/connecting solutions and community services that the clinical solution or the practice works with, such as:

* Pathology labs and any other services or providers that send information and results automatically to the current system (eg. screening services, Hospital letters, 111, Out of hours)
* Pharmacies
* [Primary Care Support England](https://pcse.england.nhs.uk/) 
* [Subsidiary and third party solution suppliers](/prm-practice-migration/guide/pre-migration-tasks#subsidiary-suppliers), (eg. DocMan or Apollo Scan for document scanning and management, DispensIT - see below)

## Subsidiary and Third party solution suppliers {#subsidiary-suppliers}

It may be necessary to migrate data from subsidiary suppliers (also referred to as [Lot 1 services]((https://digital.nhs.uk/services/gp-systems-of-choice/gpsoc-services#lot-1-gp-principal-clinical-systems-and-subsidiary-modules)) as part of the migration (eg. DocMan or Apollo Scan for document scanning and management).

__Regardless of whether you plan to migrate away from the subsidiary supplier or integrate with them, you will need to give notice to them of your solution change__. The notice period required will vary depending on the system. 

   -- If you require a data extract from the subsidiary supplier, this should be requested at the same time as you place the order for the new system. 

   -- The data extract from a subsidiary supplier should be completed at the same point in time as the main system extraction and provided to the new supplier following the agreed process.

   -- This applies to both the Initial data extract and the Final data extract

Please be aware that reconfiguration work may be required by a subsidiary supplier after you have migrated to the new system ([Post Go-Live](post-go-live) to enable integration. 


## Notifying patients

During the migration, the practice may need to remove access to online services. It may also be necessary for patients to re-register onto the new online service (if applicable). The practice will need to plan for how it will notify patients of this potential requirement. 

Most practices display posters for many weeks in advance to create awareness, some add messages on their practice website, and others may enlist the help of the Patient Participation Group (PPG).

The practice should also advise patients about other potential impacts of the implementation of the new system. For example, in the period immediately after the migration as staff adjust to the new system, prescription requests may take slightly longer and consultations may run over time.
 

## Schedule any training

Schedule your training plan and book rooms. [Read more about training](training). 

## Check hardware and software deployment timelines

If the [Technical Survey](technical-survey)identified any additional hardware or software requirements, make sure that these are scheduled in and that access is available.

## Data checking preparation

The new supplier will provide a set of test criteria for data checking. The practice will be asked to find patient records that match these criteria (usually up to 20 records) and a selection of random records. Usually, the new supplier or delivery partner will assist with the initial selection of records before asking the practice to complete finding the remaining patient records unaided. You will need to supply a list of the selected patients to the new supplier as well as various reports such as QOF and target reports.
