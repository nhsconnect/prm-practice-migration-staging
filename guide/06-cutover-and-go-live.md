---
layout: page_with_sidebar
permalink: /guide/cutover-and-go-live
title: Cut-over and Go Live
subtitle: Transitioning to the new solution/system
nextpage: /guide/post-go-live
previouspage: /guide/planning-for-cut-over
breadcrumbparent: /guide
---

During the Cutover phase, you will carry out all the activities planned for in the [Planning for the Cutover phase](/prm-practice-migration/guide/planning-for-cut-over).

## Who is involved
* Practice Staff
* Project Manager
* CCG / Delivery Partners
* Trainers
* New Supplier


## What to expect during the cutover

### Final data production 
The Cutover begins when the current supplier produces a final data extraction of the current system. This extract is given to the new supplier who imports the data into the live version of the new system. 

Practice staff will need to be logged off by the time given by the current supplier on Final Data Production day. Practice staff may continue using the current system (solution) knowing that the data entered will not be migrated.


### Manual processes are put in place
[Refer back to the cut-over planning for further details of the processes](/prm-practice-migration/guide/planning-for-cut-over#appointments)

{%- capture lesson_learnt_1 -%}
__Lesson learnt__ - Remember to include any Clinical staff who may work remotely
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_1 accessibility_text="Lesson learnt" markdown=true -%}



### Configure devices

Depending on which solution the practice is migrating to, configuration of devices (eg. scanners, check-in and call waiting boards) may occur pre-Go-Live or on Go-Live day, however these generally cannot be connected to the new system until Go-Live day. This is usually completed by the delivery partner.  <!-- [UPLIFT] added reference to some scenarios, where users can be set up in the Live system prior to Go Live -->


### Hardware replacement

Incompatible equipment identified in the [Technical Survey](technical-survey) may have been replaced and tested by now, or in some cases this may happen on Go-Live day.


### Activate Smartcards

Depending on the clinical solution the practice is migrating to, the solution will be configured for staff, roles and names of sites either before the Go-Live or on Go-Live day. Smart cards will also need to be activated at the appropriate time. Who does this varies between the delivery partner, trainers and practice staff.


### Transfer Booked Appointments

This is the time to enter all future booked appointments that were added to the old system into the new one.

## What to look out for

* Staff availability for Cutover tasks.

* Each practice has its own MESH inbox/queue/secure file transfer. When MESH changes, teams need to inform partner services of the change in address.

* Fixing degraded codes could take the practice some time.


* * * 
**_SLA:_**  The cut-over period should not exceed 72 hours.
<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 15)</em>
* * *
<!-- [UPLIFT] added reference to Step 10 SLA from Ancillary Document p.15 -->



## Go Live

Following directly after Cutover, the practice ‘Sign off’ the Go-Live data, and commences the beginning of the new supplier’s solution. 

* The old solution is now read only and available for another 45 days as standard - **check this with your old supplier to ensure that they do not terminate access early.**

* Third party solutions should come back online.


{%- capture lesson_learnt_3 -%}
__Lesson learnt__ - Remember to check that third party suppliers and services that were switched off during the Cutover period have been re-enabled (e.g. .  DocMan, DispensIT etc)
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_3 accessibility_text="Lesson learnt" markdown=true -%}

### Sign off Go Live Data 

On Go-Live day there will be data checking activities that you need to complete. If the practice is satisfied that all the data has been transferred and the migration is successful, sign off the live data and provide confirmation to the Supplier 

### Switch links back on and notify 3rd parties

Now your new solution is up and running you can contact all the connecting solutions and community services that the system/solution or the practice works with, to switch services back on, for example:

* Third party software/solution suppliers, for example DocMan or Apollo Scan for document scanning and management.

* Complete the registration process for patients that joined the practice during the Cutover period

If you use any third party software as part of your solution, please be aware that reconfiguration work may be required by them now that the practice has migrated to the new clinical solution.


### Data re-checking

The practice should re-check the patients identified and tested previously as part of the [initial data production](/prm-practice-migration/guide/initial-data-production) as well as random patients. 

Practice staff should recheck reports such as QOF and indicator points, cytology and immunisation target reports, capitation figures and the remapping of local codes.


### Training on the new solution

Practice staff may have already received [training for the new solution](/prm-practice-migration/guide/training) or may receive it during the Cut-over period, including training for any changes to practice processes.  

## What to look out for

 * Confirm your Go-Live date with the new supplier again to make sure there is no change in their schedules.  

* Each practice has its own MESH inbox/queue/secure file transfer. When MESH changes, teams need to inform partner services of the change in address.  

* Fixing degraded codes could take the practice some time.
<!-- [UPLIFT] reworded the language here -->

* New patients cannot complete registration until after the Cutoff period so you will need to ask them to come back after Go-Live.

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

