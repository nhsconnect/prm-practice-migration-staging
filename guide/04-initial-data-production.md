---
layout: page_with_sidebar
permalink: /guide/initial-data-production
title: Initial Data Production & Data Checking
subtitle: 
nextpage: /guide/planning-for-cut-over
previouspage: /guide/pre-migration-tasks
breadcrumbparent: /guide
---

## What is the Initial Data Production?

The Initial Data Production is the point at which a copy of the current clinical system data is provided to the new supplier, who import it into a test version of their system.

The Initial Data Production activity enables [data checking](#data-checking) to begin – the practice will perform data checking tasks in the test system to make sure that the imported patient data matches how it was when it was taken from your current system. 
During this stage, the new supplier will provide a set of test criteria for data checking. The practice will be asked to find patient records that match the set criteria (up to 20 records) and a selection of random records. 

The new supplier or delivery partner (such as a CSU) will assist with the initial selection of records before asking the practice to locate the remaining patient records unaided. A list of the selected patients will need to be given to the new supplier as well as various reports such as QOF and target reports as part of the initial data production activities. 

## Who is involved in the Initial Data Production?

* The **current supplier** - who provide the data extract from the current system.
* The **new supplier** - who import the data into the dummy system and visit the practice to help with the required activities
* The relevant members of the **practice team**
* Possibly the **delivery partner** - who support the practice and work with the suppliers (the level of support available can vary by area)

## Set up access to the new system

As part of the Initial Data Production phase, the practice will be given access to the test system. The new supplier will setup admin users (about 1-3) and show them how to set up logins for the rest of the practice team.
The new supplier or delivery partner should provide brief basic training on the new system so that users are able to carry out the Initial Data Production activities.

{%- capture lesson_learnt_2 -%}
**Lesson learnt** - at least one member of staff should be involved in this stage so that they have the knowledge to navigate the system to identify patients and know how to set up additional users.{%- endcapture -%} 
{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}

## Data checking {#data-checking}

### Preparation

The following activities should have been completed in advance…

* The [data extract has been requested from the existing supplier in advance]( {{site.baseurl}}/guide/get-started#request-a-data-extract-from-the-current-supplier)
* The practice has identified the patient records matching criteria provided by the new supplier for testing  ([see data checking preparation section in Pre-migration tasks]( {{site.baseurl}}/guide/pre-migration-tasks#data-checking-preparation))
* Rooms have been booked for initial data production meetings, training and data checking activities

### Data checking phases

Data checking generally happens in 2-3 phases:

1. Initial data checking and reporting of any issues or corruption found
2. Rechecking the data after the new supplier has resolved these issues
3. In some circumstances a third phase is required if further issues were found in the recheck, however, most migrations do not require this further recheck of the data.

<!--
* * * 
**_SLA:_** To make sure that any errors are fixed promptly, you must inform your new supplier of any initial data check issues within 5 working days.<br><em>(GP IT Futures Catalogue Solution Migration Process, p. 14)</em>
* * * -->
<!-- [UPLIFT] added approximate reference to the Step 9 SLA from Ancillary Document p. 14 -->

### Timeline for data checking

The timeline and target dates for carrying out and completing the data checking tasks will have been agreed when the key dates for the overall migration process were planned and agreed.

Practices are advised to plan for between 3-5 days for each data checking phase. However, the rechecking phases should not take as long as the initial data checking.

Clinical input will be required and the level of input may vary per practice. Please bear in mind that the lead clinician will be responsible for signing off the final data checking phase.

The new supplier should assist the practice on the first day of Phase 1 Initial data checking.

{%- capture lesson_learnt_2 -%}
**Lesson learnt** - You will need to block out time and dedicated staff to complete the data checking activity as any delays in completing this phase will impact the Go-Live date.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}


{%- capture lesson_learnt_2 -%}
**Lesson learnt** - If possible, try to arrange access to additional support from the new supplier or delivery partner to answer any questions and remove any uncertainty that could block or delay the data checking phase.
{%- endcapture -%}

{%- include inset.html content=lesson_learnt_2 accessibility_text="Lesson learnt" markdown=true -%}

## What to test

The new supplier will provide a complete list of data checking activities.

The majority of testing will focus on the identified patient records—from the Initial Data Production—matching the criteria supplied by the new supplier along with the random patients.

Alongside checking the identified patient records, the practice will be asked to check and compare reports such as QOF reports and indicator points, cytology and immunisation target reports, capitation figures and remapping local codes.

Data checking is a manual process; ideally, the practice staff will complete the activity with the use of two monitors side-by-side, one displaying the current system and the other displaying the test version of the new system. Staff will cross-reference the two to check their consistency. If use of 2 monitors is not possible, then print out the full patient records and reports as required from the current system.

### Reporting issues with data {#reporting-issues-with-data}

We recommend that issues are logged and reported to the new supplier as soon as they are found.

Each new supplier will have a process for reporting issues. The supplier should provide you with this information before or at the start of the initial data checking day.

At the end of each data checking phase, there will be a period whereby the new supplier will review and address the issues found, this may vary depending on the complexity of the issues reported.

The new supplier will notify the practice when the issues have been fixed, however the practice is required to repeat the data checking process to confirm that the fix is acceptable.

## Signing off the data checking {#signing-off-the-data-checking}

Once the recheck is completed the practice will be asked to ‘Sign off’ that the data is accurate and it is satisfied with the quality of the data. This is the data that will be carried forward to the live system. If there are any concerns around outstanding issues then request further fixes and another round of data checking. 

In general most clinical system adaptors are ‘mature’ and the number of discrepancies found at data checking are minimal. 

**Before signing off the data, the practice should ensure that they understand the impact of any data that cannot be migrated in terms of how they will manage it and the volume of work involved.**

The CCG may ask the practice to sign a document to this effect.

