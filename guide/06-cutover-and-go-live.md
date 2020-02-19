---
layout: page_with_sidebar
permalink: /guide/cutover-and-go-live
title: Cut-over and Go Live
subtitle: Transitioning to the new solution/system
nextpage: /guide/post-go-live
previouspage: /guide/planning-for-cut-over
breadcrumbparent: /guide
---

During the Cutover phase, you will carry out all the activities planned for in the [cut-over preparation phase](/prm-practice-migration/guide/planning-for-cut-over).

## Who is involved
* Practice Staff
* Project Manager
* CCG / Delivery Partners
* Trainers
* New Supplier


## What to expect during the cutover

### Final data production 
The cut-over will start with a ‘Final data production’. Practice staff continue using existing solution (source) knowing that the data entered will not be migrated. 

The final data extract (excluding any data entered during cut-over) is provided to the new supplier (target), who import it into the new solution.


### Manual processes are put in place
[Refer back to the cut-over planning for further details of the processes](/prm-practice-migration/guide/planning-for-cut-over#appointments)


### Data re-checking

The practice should re-check the patients identified and tested previously as part of the [initial data production](/prm-practice-migration/guide/initial-data-production) as well as random patients. 

Practice staff should recheck reports such as QOF and indicator points, cytology and immunisation target reports, capitation figures and the remapping of local codes.


### Training on the new solution

Practice staff may have already received [training for the new solution](/prm-practice-migration/guide/training) or may receive it during the Cut-over period, including training for any changes to practice processes.  

{%- capture lesson_learnt_1 -%}
__Lesson learnt__ - Remember to include any Clinical staff who may work remotely
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}

### Dictionary of Medication and Devices mapping {#dictionary-of-medication-and-devices-mapping}

Dictionary of Medication and Devices (DM&D) mapping needs to be done for the Electronic Prescription Service (EPS) during the cut-over


{%- capture lesson_learnt_2 -%}
__Lesson learnt__ - DM&D may only be available 1-2 days before Go Live and if the DM&D is not checked, it causes issues with Electronic Prescription Service after Go Live. 
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}


### Configure devices

Depending on which solution you are migrating to, configuration of devices (for example, scanners, check-in and call waiting boards) may occur pre-Go Live or on Go Live day. This is usually completed by the GP IT delivery partner (such as a Commissioning Support Unit).  <!-- [UPLIFT] added reference to some scenarios, where users can be set up in the Live system prior to Go Live -->


### Hardware replacement

By now, incompatible equipment identified in the [Technical Survey](technical-survey) should be replaced and tested.


### Activate Smartcards

Depending on the clinical solution you are migrating to, the solution will be configured for staff, roles and names of sites before Go Live or on Go Live day. Smart cards will also need to be activated at the appropriate time. Who does this varies between the Commissioning Support Unit, Trainers and Practice managers.


### Check Registration links

The new supplier (target) should check patient registration links are working in the new solution, the Registrations clerk is usually involved with this activity.


### Sign off Go Live Data 

After re-checking, if the practice is satisfied that all the data has been transferred and the migration is successful, the practice can sign off Go Live Data and provide confirmation to the Supplier.  

* * * 
**_SLA:_**  The cut-over period should not exceed 72 hours.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 15)</em>
* * *
<!-- [UPLIFT] added reference to Step 10 SLA from Ancillary Document p.15 -->

## Go Live

Following the actions described previously and Sign off of the Go Live Data, the practice goes live on the new supplier's solution. 

The old solution is now read only and available for another 45 days as standard - __check this with your old supplier (source) to ensure that they do not terminate access early__.

Third party solutions should come back online.

{%- capture lesson_learnt_3 -%}
__Lesson learnt__ - Remember to notify and chase third party suppliers and services that were switched off during the cut-over period (e.g. Electronic Prescription Service, Pathology etc)
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_3 accessibility_text="Lesson learnt" markdown=true -%}


## What to look out for

* Staff availability for cut-over tasks.  

* Confirm your Go Live date with the new supplier (target) again to make sure there is no change in their schedules.  

* Each practice has its own MESH inbox/queue/secure file transfer. When MESH changes, teams need to inform partner services of the change in address.  

* Fixing degraded codes could take the practice some time.
<!-- [UPLIFT] reworded the language here -->
* New patients cannot complete registration until after the cut-off period so you will need to ask them to come back after Go Live.

## Process review

As part of your process review, your supplier will submit reports to NHS Digital to help with the continuous improvement of the migration process.

This is likely to include:
<!-- [GAP] include reference to metrics dashboard inputs here -->
* Mapping tables

* Data migration

* Provision of Documented Data Extract

* Hazard Log and Clinical Safety Case

* Issue Logs

* Cut-over timescale

