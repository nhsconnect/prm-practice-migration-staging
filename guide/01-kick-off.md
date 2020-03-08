---
layout: page_with_sidebar
permalink: /guide/kick-off
title: Kick-off Meeting
subtitle: Get everyone on the same page about what needs to happen and when
nextpage: /guide/technical-survey
previouspage: /guide/get-started
breadcrumbparent: /guide
---
<!-- [UPLIFT] added the word 'meeting' -->
## What is a ‘Kick-off’?
A ‘Kick-off’ is a meeting where all the key people who will be involved in the migration discusses the end to end process of migrating between the old and new systems. The objective is to assign roles and get everyone on the same page about what needs to happen and when.

### As a priority...

* **Discuss** the key milestones and week by week activities
* **Agree** on dates and targets for the above milestones and activities
* **Identify** who will be involved in the migration and what are their roles and responsibilities. It is particularly important that a Project Manager for the migration is officially identified by the practice and agreed by all stakeholders.
* **Agree** how you will communicate and share information<br/>
– Between yourselves<br/>
– With third parties<br/>
– [With practice staff](#make-staff-aware)<br/>
– [With patients](#notification-of-patients)
* **Understand** the scope of the entire migration
* **Define** the ownership of risks and the process for mitigations
* **Define** the process of maintaining a hazard Log
* **Discuss** potential rollback scenarios and approach
* **Detail** any system downtime and impact on core hours

### For the Kick-off meeting, you should involve as a minimum...

* **The Migration Project Manager** - This should be an official and agreed representative from your delivery partner (such as a CSU), the CCG or in some cases the Practice Manager or Lead GP. This person should be available from Day 1 until 45 days post migration to ensure nothing is missed during the Run-off period.
* **Practice Managers** - Including any key staff members who play a role in managing/supporting the migration
* **Lead GP** - A primary owner of all tasks and decisions that need to be made by GPs and healthcare assistants
* **New system supplier** - The supplier of the new clinical system you are moving to
* **A dedicated support person from your CCG** - Where the Delivery Partner is not carrying out all activities on behalf of the CCG, a representative from your CCG may attend the Kick-off Meeting

**Note**: When the GP IT delivery partner (such as a CSU) is leading the migration, they may invite other personnel to the Kick-off such as Business Change, Training leads, Data Quality Leads etc. The core practice team involved in managing the migration will need to act as ‘change champions’, setting a positive example of the purpose and benefits to be achieved.

## Key milestones, activities, dates and targets

By now you should have agreed on your Go-Live date. Take a look at the [key phases](/prm-practice-migration/guide#overview-of-key-phases) and put dates in your plan of when these activities need to be completed (use the content on this site to guide you). It is worthwhile stepping through each of the phases and making sure that everyone is aligned on what the phase objective is and what the key activities are within them. 

For example, you should have a plan for the following dates:
* Technical Survey (if not already arranged)
* Initial Data Production and testing days
* Final data production and Cutover
* Go-Live
* Training days

As you go, you may want to create a shared list of actions for each phase, with a column for a target date, who will complete the action and a status/update column. Use this list to track progress throughout the migration.

It is important that all staff are made aware of the upcoming changes, even if those staff members are not driving or managing the migration.

## Clinical Risk Assessments

Once the data migration approach and plans have been agreed by all parties, there is a need to complete a Clinical Risk Assessment to consider any risks to clinical and patient safety. If you consider there to be a material risk associated with the migration, you will need to escalate this through Service Management.

{%- capture service_management -%} 
The process for escalating migration issues under GP IT Futures is currently in review. As soon as the new Service Management process is finalised, we will let you know. 
{%- endcapture -%}
{%- include carecard.html content=service_management accessibility_text="Please note" heading="Please note" markdown=true -%}


## Who, roles and responsibilities

As part of the Kick-off, you should identify who should be involved in the migration and what their roles and responsibilities will be. If people are not present in the Kick-off, think about how you will onboard them and understand their role. As you work through your list of roles, capture and consolidate any contact information for individuals.

The following is a list of common roles, teams and organisations to engage with and involve in your migration.

* **Project Manager**
* **Practice Manager**
* **Practice staff**
* **A General Practitioner** to act as a Lead GP
* **Clinical staff** (including people who may work remotely)
* **GP IT delivery partner** (also referred to as delivery partner)
-- Explore with them the availability of any supporting roles such as Business change, Training leads, Data quality teams etc
* **Clinical Commissioning Group** (CCG)
* **Current supplier** of the GP system
* **Surrounding and community services** - Pharmacies, Pathology labs, [Electronic Prescription Service (EPS)](https://digital.nhs.uk/services/electronic-prescription-service), [GP2GP](https://digital.nhs.uk/services/gp2gp), [Summary Care Records (SCR)](https://digital.nhs.uk/services/summary-care-records-scr), Out of hours, 111 and any screening services etc
* **Any third party system supplier** that integrates with your current system, for example, DocMan or Apollo Scan, DispensIT
* **New supplier** of the GP system may attend the Kick-off, if they are available

## Schedule regular migration meetings

Now is a good time to schedule regular internal migration meetings.

* We suggest holding them on a weekly basis at the same time
* Book rooms and make sure everyone who needs to can attend
* Invite additional attendees if agenda item requires this
* Keep call conference IDs tools consistent i.e. try to reuse the same conference call setup so that all participants can access it easily and repeatedly
* Agree how you’ll all communicate and share information between meetings

## Check dates against availability

Look at your key dates and the people you need:

* Plan for critical days - identify and make sure that people are made aware and will be available
* Do staff have pre-booked holidays or training planned?
* Are there any planned events or surgeries during this time that suggest the practice may be busier than usual?

The aim is to ensure a successful migration and limit the impact on the practice by reducing the amount of practice activity happening during the [Cutover period](/prm-practice-migration/guide/planning-for-cut-over#what-is-the-cut-over) (and 2 days after Go-Live) and secure the availability of as many members of the practice team to support the migration as possible.

###  Securing dates and people’s time {#securing-dates-and-peoples-time}

* Block time if required for key dates
* Encourage staff to keep these dates free and if possible avoid booking holidays on these dates
* If possible, and alternative dates are available, avoid planning any events or data rich chronic disease clinics during the [Cutover period](/prm-practice-migration/guide/planning-for-cut-over#what-is-the-cut-over) that may increase the workload of the practice (e.g. Asthma reviews)
* Pre-book rooms for training, testing and any other migration activity
* Put breather slots in the rotas in the current system for the first couple of weeks post Go-Live if your clinicians are not familiar with the new supplier system.

## Additional topics for your Kick-off

The Kick-off is a good opportunity to also run through the following...


### Common data issues, housekeeping and clean-up tasks

Ask the new supplier or delivery partner to walk through any common/known data issues when migrating to the new system - these may vary from system to system.

The objective is to identify any tasks that the practice can start rectifying early and before the [Initial Data Production phase](initial-data-production). As time goes on, the amount of work the practice needs to complete will grow, so getting ahead can ease the pressure.

If you have access to a Data Quality team (possibly your delivery partner), involve them now.

Discuss and plan any housekeeping tasks such as…

* The appropriate management of duplicate and orphaned records which will not migrate to the new system (you may need to arrange a reconciliation with the PCSE to identify these)
* Complete a review of letter and data entry templates to identify those that will need to be re-entered into the new system. **Note**: letter and data entry templates will need to be manually copied over. Completing this review will make it easier to identify which templates you need to transfer
* Clearing down the practice inboxes, outstanding workflows and all open communication tasks, for example, pathology and registration; as you approach the [Final Data Production day](/prm-practice-migration/guide/cutover-and-go-live#final-data-production), you need to have zero tasks outstanding

Now is also a good time to introduce the [Data Checking tasks](/prm-practice-migration/guide/pre-migration-tasks#data-checking-preparation) and what the practice will need to do during the [Planning and Preparation phase](early-prep-and-planning), such as finding patients that match the test criteria supplied by the new supplier.

### Technical survey and hardware {#technical-survey}

If the practice is not already aware, the [Technical Survey](/prm-practice-migration/guide/technical-survey) (try to schedule this shortly after the Kick-off) may result in the identification of new or additional hardware being required for purchase and unexpected costs. This may not apply in all cases. You may want to highlight this early so that the practice and CCG are aware of this possibility before the Technical Survey is completed.

Compile a list of third party software that integrates with the current system.

Please note that it is the responsibility of the practice to ensure that they have contacted their third party software suppliers to check if the software is compatible with the new system and agree any actions required for implementation. The new supplier will not complete this activity.

### Notifying third parties and links

Make a list of all the supporting/connecting systems and community services that are currently sent electronically. Check if the delivery partner has a list of all the third party providers in the area to help with this task.

* Pathology labs and any other services or providers that send information and results automatically to the current system. (eg. bowel screening, hospital letters, 111, Out of hours)
* Pharmacies
* [Primary Care Support England](https://pcse.england.nhs.uk/)
* [Third party system suppliers](/prm-practice-migration/guide/pre-migration-tasks#subsidiary-suppliers), (eg. DocMan or Apollo Scan for document scanning and management, AccuRx, DispensIT, eConsultation provider)

<!--removed based on user feedback
* [Electronic Prescription Service (EPS)](https://digital.nhs.uk/services/electronic-prescription-service)
* [GP2GP](https://digital.nhs.uk/services/gp2gp)
* [Summary Care Records (SCR)](https://digital.nhs.uk/services/summary-care-records-scr)-->

Plan and schedule how you will notify them of your change of system. The earlier you give notice of your Cutover and Go-Live dates the better. The notice period required will vary depending on the service.

If you use any third party software that integrates with your current system, please be aware that reconfiguration work may be required after you have migrated [Post Go-Live](post-go-live). You should contact the supplier to ensure that is possible in the new system and plan a work around process if not.

Add a task to your plan to contact and remind each party the week before and on the day when you require changes to be made.


### Notifying Patients {#notification-of-patients}

During the migration, you may need to remove access to online services, such as the ability to book appointments, and you may also require patients to re-register on your new online service (if applicable). You will need a plan for how you will notify patients of this potential requirement and it is advised that you give them plenty of notice. Most practices display posters for many weeks in advance to create awareness, some add messages onto their practice website, while others may enlist the help of the Patient Participation Group (PPG).

You may also want to discuss what online messaging is put in place when the service is removed (e.g. What happens if a patient tries to access the online service when it ceases to be available?) You may want to add this as a topic on the practice patient forum.

Remember to make any necessary changes to your practice website. For example, Online Access Links.


### Involve staff in every stage of the process {#make-staff-aware}

Certify that all staff are fully informed and engaged in the process. However, make it known they can ask questions whenever they need to. It is a good idea to have ‘change champions’ within the practice as the ‘go-to’ resource for staff. They will be team members who are most positive about the change and willing to help others.

### Training

The practice should be aware of who will be delivering their training (delivery partner or supplier) and as part of the Kick-off process dedicated meetings should be planned to discuss the delivery. 

During these meetings the trainers should: 

* Work with the practice to agree dates and 
* Tailor training requirements to the needs of each staff role. 
* Plan smartcard access roles and user set up. 

[Read more about training](training).
