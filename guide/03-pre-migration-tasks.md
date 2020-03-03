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

By now [a data extract should have been requested from the practice’s current supplier](/prm-practice-migration/guide/get-started#request-data-extract), and is normally carried out by the CCG/delivery partner on your behalf. The current supplier must provide this extract. Check with your CCG/delivery partner that the current supplier can provide the data on the date requested. If you made the request yourself then get confirmation directly from the current supplier. They must provide all the data extract(s) in the appropriate format according to the relevant data migration standard.

Complete additional data extract requests for any other clinical system supplier that you use since this data may not be included in the main one. For example, any document management and scanning solutions such as DocMan or anticoagulation management software such as INR Star. 

Additional data extractions should be carried out at the same time as the main one, therefore liaise with the relevant suppliers before booking key dates to ensure that they can also meet them. 

<!--* * *
**_SLA:_**  Once a request is made for an extract, your old supplier has 5 working days to provide this to you/your new supplier.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 6)</em>
* * *-->
<!-- [UPLIFT] added reference to the Supplier SLA in terms of responding to queries from a Migration Management Agent -->

<!--The DDE is the 'Documented Data Extract' that shows what physical data is to be included in the extract and its format and structure (see DMI02).
 [UPLIFT] added reference to the Supplier SLA in terms of responding to a request for an extract -->

__The request needs to be completed as early as possible__. The current suppliers have varying lead times/notice periods to provide this data upon request; for example, a supplier may require up to 5 weeks notice. __Any delays to giving notice may impact the migration timeline__.

## Clean up the current system data {#clean-up-the-current-system-data}

The new supplier, delivery partner or CCG can advise the practice on any common or known data issues when migrating to the new system. It is beneficial to review the quality of the data in the current system and carry out any required remedial actions before the first data extraction. This may reduce the amount of issues that are found during data checking and the subsequent work required to resolve these.

<!--* * * 
**_SLA:_**  Reviewing the quality of the data in your current solution should not take more than 6 weeks. This review should include identifying any irregularities in the data, performing standard data quality checks and assessing any misused codes or concepts, such as clinical findings terms.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 11)</em>
* * *-->

<!-- [UPLIFT] added reference to Step 4 SLA from the Ancillary Document -->
<!-- [GAP] need to check whether 'Source Solution data quality review' is the same activity as 'Clean up the current system data' i.e. is the SLA here in the right place? -->

### Tasks include...

* Requesting a reconciliation of the practice database against the PCSE database (For more information: see a [Guide to Patient Registrations](https://pcse.england.nhs.uk/services/registrations/)
* Identifying any local or practice created codes and mapping these to the appropriate Read/SNOMED codes if available 
* Confirm which patients have any current issues of un-mapped codes and as part of the clean-up of the current system data, map those drugs and devices according to the [Dictionary of Medication and Devices (dm+d)](https://www.nhsbsa.nhs.uk/pharmacies-gp-practices-and-appliance-contractors/dictionary-medicines-and-devices-dmd) 
* Establishing which letter and data entry templates should be transferred into the new system. These will need to be manually copied over.

{%- capture lesson_learnt_2 -%}
__Lesson learnt__ - dm+d may only be available 1-2 days before Go Live and if the DM&D is not checked, it causes issues with Electronic Prescription Service after Go-Live. 
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}

## Notifying third parties and links {#notifying-third-parties-and-links}

Refer back to the list created at the Kick-off of all the supporting/connecting solutions, patient and community services that the system or the practice works with, such as:

* SMS providers (such as eConsultation and AccuRx-Chain). Practices will need to decide how these messages will be captured and stored during Cutover.
* Login of patients to NHS app may be affected if the IM1 credentials of the practice change during the migration. Similarly, access to other apps like Evergreen life may be affected and practices will need to liaise with these third parties.
* Patient Online Services may need to be contacted to issue new patient access IDs, since the patient access IDs for current supplier may not grant access into the portal of the new supplier
* Depending on the system the practice is migrating to, patients' emails may need to be re-verified. There may be a checkbox beside each patient email indicating (in the current system) whether it has been verified or not. If this checkbox is not ticked, the practice may experience difficulties in the transfer of these patient email addresses.
* Pathology labs and any other services or providers that send information and results automatically to the current system (eg. screening services, Hospital letters, 111, Out of hours)
* Pharmacies
* [Primary Care Support England](https://pcse.england.nhs.uk/) 
* [Subsidiary and third party solution suppliers](/prm-practice-migration/guide/pre-migration-tasks#subsidiary-suppliers), (eg. DocMan or Apollo Scan for document scanning and management, DispensIT - see below)

Some third party products suppliers may charge a fee to move the product license over to the new system. (e.g. CliniSys - Labs ICE test requesting) Check if there is a cost and who is expected to pay for this. Therefore allow additional time to raise invoices.


## Subsidiary and Third party solution suppliers {#subsidiary-suppliers}

It may be necessary to migrate data from subsidiary suppliers (also referred to as [Lot 1 services]((https://digital.nhs.uk/services/gp-systems-of-choice/gpsoc-services#lot-1-gp-principal-clinical-systems-and-subsidiary-modules)) as part of the migration (eg. DocMan or Apollo Scan for document scanning and management).

__Regardless of whether you plan to migrate away from the subsidiary supplier or integrate with them, you will need to give notice to them of your system change__. The notice period required will vary depending on the system. 

   -- If you require a data extract from the subsidiary supplier, this should be requested at the same time as you place the order for the new system. 

   -- The data extract from a subsidiary supplier should be completed at the same point in time as the main system extraction and provided to the new supplier following the agreed process.

   -- This applies to both the initial data extract and the final data extract

Please be aware that reconfiguration work may be required by a subsidiary supplier after you have migrated to the new system ([Post Go-Live](post-go-live) to enable integration. 


## Notifying patients {#notifying-patients}

During the migration, the practice may need to remove access to online services. It may also be necessary for patients to re-register onto the new online service (if applicable). The practice will need to plan for how it will notify patients of this potential requirement. 

Most practices display posters for many weeks in advance to create awareness, some add messages on their practice website, and others may enlist the help of the Patient Participation Groups (PPGs). PPGs can also be used post Go-Live to ensure all patients have received their new patient access IDs.

The practice should also advise patients about other potential impacts of the implementation of the new system. For example, in the period immediately after the migration as staff adjust to the new system, prescription requests may take slightly longer and consultations may run over time.
 

## Schedule any training

Schedule your training plan and book rooms. Have dedicated cover/support during those times when staff are in training. [Read more about training](training). 

## Check hardware and software deployment timelines

If the [Technical Survey] (technical-survey)identified any additional hardware or software requirements, make sure that these are scheduled in and that access is available.

## Data checking preparation {#data-checking-preparation}

The new supplier will provide a set of test criteria for data checking. The practice will be asked to find patient records that match these criteria (usually up to 20 records) and a selection of random records. Usually, the new supplier or delivery partner will assist with the initial selection of records before asking the practice to complete finding the remaining patient records unaided. You will need to supply a list of the selected patients to the new supplier as well as various reports such as QOF and target reports.
