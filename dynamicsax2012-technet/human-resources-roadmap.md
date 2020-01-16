---
title: Human resources roadmap
TOCTitle: Human resources roadmap
ms:assetid: ce45957d-546b-463b-b4f9-a8f0f5b7c454
ms:mtpsurl: https://technet.microsoft.com/library/Dn783393(v=AX.60)
ms:contentKeyID: 62838587
author: Khairunj
ms.date: 09/10/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Human resources roadmap 


This topic is a roadmap to additional information about Human resources in Microsoft Dynamics AX 2012. It includes links to information about how to get started with, configure, use, and integrate with Human resources in AX 2012. You can use this information to help you plan a Human resources implementation, guide you through the implementation steps, and give you a comprehensive list of links to most of the tasks you need to complete.

The Human resources module in AX 2012 streamlines and automates many of the day-to-day recordkeeping processes and provides a framework for human resources (HR) staff to manage areas of oversight. These areas include employee recruitment and retention, benefits administration, training, performance reviews, and change management.

You can use Human resources to complete these tasks:

  - Administer organizational structures

  - Maintain comprehensive worker information from hire to retire

  - Define and administer benefit plans, enroll workers, assign dependent coverage, and designate beneficiaries

  - Establish and monitor absence policies

  - Implement and track profile-based time management and generate pay information to export to a payroll system

  - Manage worker competencies

  - Review performance and implement worker goals

  - Set up, deliver, and analyze training courses that include agendas, sessions, and tracks

  - Recruit workers and track applicants

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dn800886.TopicIcons_OnThisPage(AX.60).png" title="On this page" alt="On this page" />
<p>Get started</p>
<p>Configure</p>
<p>Use</p>
<p>Integration</p>
<p>Still didn’t find what you were looking for?</p></td>
<td><img src="images/Dn800886.TopicIcons_RelatedResources(AX.60).png" title="Related resources" alt="Related resources" />
<p><a href="http://community.dynamics.com/ax/f/33.aspx?pi49988=0%26category=human+resources+and+payroll">Microsoft Dynamics AX Forum (Human resources and Payroll)</a> (forum)</p>
<p><a href="http://community.dynamics.com/ax/b/axhcmnewslearningshighlights/default.aspx">Microsoft Dynamics AX HCM News, Learnings, &amp; Highlights</a> (forum)</p>
<p><a href="https://blogs.msdn.com/b/dax/archive/2014/01/14/human-capital-management-even-better-with-the-latest-release-of-microsoft-dynamics-ax-2012.aspx">Human Capital Management – Even better with the latest release of Microsoft Dynamics AX 2012</a> (blog)</p>
<p><a href="http://sandeepchaudhury.wordpress.com/2013/02/14/time-and-attendance-registration-functionality-of-microsoft-dynamics-ax-2012/">Time and Attendance Registration functionality of Microsoft Dynamics AX 2012</a> (blog)</p>
<p><a href="https://lcs.dynamics.com/home/homeindex">Lifecycle Services</a>* (Cloud-based workspace)</p>
<p><a href="http://www.microsoft.com/en-us/download/details.aspx?displaylang=en%26id=29210">Help and Resources Datasheet for Dynamics AX 2012</a> (download)</p>
<p><a href="https://mbs.microsoft.com/partnersource/northamerica/deployment/documentation/white-papers/ax2012_businessprocessdiagramtemplates">Business Process Diagram Templates for Microsoft Dynamics AX 2012</a> (download)</p>
<p>* In order to use Lifecycle Services, you must have a CustomerSource or PartnerSource account, and have created a project. For more information, see the <a href="lifecycle-services-for-microsoft-dynamics-user-guide-lcs.md">Lifecycle Service User Guide</a></p></td>
</tr>
</tbody>
</table>


## Get started

There are many options to consider and decide on before you set up and implement Human resources.

The following table lists links to topics that you can view to learn more about Human resources. You should review the setup steps in these topics to help you plan and make decisions before you set up Human resources. Some of the links are repeated in the “Configure” and “Use” sections of this topic.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Learn what’s new</p></td>
<td><p>Learn what’s new in your release of Human resources.</p></td>
<td><p><a href="what-s-new-human-resources-features.md">What's new: Human resources features</a></p></td>
</tr>
<tr class="even">
<td><p>Learn about Human resources</p></td>
<td><p>Learn about the functionality that is available in Human resources and learn about worker-related concepts.</p></td>
<td><p><a href="human-resources.md">Human resources</a></p>
<p><a href="about-workers.md">About workers</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan the setup parameters for Human resources</p></td>
<td><p>Plan the identification types that represent certain ID numbers (such as the SSN field), the auto-numbering sequences to use, and whether to allow workers to be assigned to new positions when new positions are created.</p>
<p>Some parameters and settings are specific to a single legal entity (sometimes called a company), whereas others are shared across all legal entities.</p></td>
<td><p><a href="set-up-human-resources-parameters.md">Set up human resources parameters</a></p></td>
</tr>
<tr class="even">
<td><p>Plan number sequences</p></td>
<td><p>Decide how to number records such as personnel numbers, applicants, and positions. Be aware that some numbered records, such as personnel numbers and positions, are shared across legal entities. You must also determine how to set up additional general, recruitment, compensation, and other number sequence parameters.</p></td>
<td><p><a href="set-up-number-sequences-for-human-resources.md">Set up number sequences for Human resources</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan worker identification information</p></td>
<td><p>For organizations in the United States, specify the types of identification you allow for Form I-9 employee eligibility.</p></td>
<td><p><a href="set-up-identification-types.md">Set up identification types</a></p>
<p><a href="usa-set-up-issuing-agencies.md">(USA) Set up issuing agencies</a></p>
<p><a href="usa-set-up-form-i-9-document-types.md">(USA) Set up Form I-9 document types</a></p></td>
</tr>
<tr class="even">
<td><p>Plan personnel action descriptions</p></td>
<td><p>Decide whether to use personnel actions. Personnel actions are activities that occur when a worker is employed, such as transfers, promotions, and the creation of new positions. You can use personnel actions to track the reasons and, optionally, add approval workflows, for each of these actions.</p></td>
<td><p><a href="personnel-actions.md">Personnel actions</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan the structure of your organization’s HR elements</p></td>
<td><p>Decide how to structure your organization’s HR elements, such as departments, jobs, and positions. You can also decide whether to set up teams.</p></td>
<td><p><a href="about-organizations-and-organizational-hierarchies.md">About organizations and organizational hierarchies</a></p>
<p><a href="setting-up-organization-information-for-workers.md">Setting up organization information for workers</a></p>
<p>“View department statistics” section in <a href="key-tasks-departments.md">Key tasks: Departments</a></p>
<p><a href="create-a-team.md">Create a team</a></p></td>
</tr>
<tr class="even">
<td><p>Plan compensation plans</p></td>
<td><p>Decide how to set up compensation plans. These plans include pay for performance.</p></td>
<td><p><a href="about-compensation-plans.md">About compensation plans</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan loan items</p></td>
<td><p>Decide whether to use loan items to keep track of physical items that your organization loans to workers, such as laptop computers and mobile phones.</p></td>
<td><p><a href="about-loan-items.md">About loan items</a></p></td>
</tr>
<tr class="even">
<td><p>Plan reference information for workers</p></td>
<td><p>Decide how to set up worker reference information, such as name sequences, titles, ethnic origins, and absence information. This helps ensure that reference information is entered before worker records are created, which streamlines that process.</p></td>
<td><p><a href="key-tasks-set-up-reference-information-for-workers.md">Key tasks: Set up reference information for workers</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan competencies</p></td>
<td><p>Decide on the competencies to use for workers, applicants, or contact persons. You can track skills, education, and professional experience.</p></td>
<td><p><a href="about-competencies.md">About competencies</a></p>
<p><a href="about-skills.md">About skills</a></p></td>
</tr>
<tr class="even">
<td><p>Plan injury and illness information</p></td>
<td><p>Decide how to set up injury and illness information. Default information is provided for legal entities whose primary address is in the United States or Canada. For other countries/regions, you must manually set up injury and illness information.</p></td>
<td><p><a href="set-up-injury-and-illness-information.md">Set up injury and illness information</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan recruitment projects</p></td>
<td><p>Decide how to set up recruitment. Before you can use recruitment projects, you must set up application bookmarks, default recruitment projects, email templates, and document types that are used to communicate with applicants.</p></td>
<td><p><a href="about-recruitment-projects.md">About recruitment projects</a></p>
<p><a href="set-up-application-bookmarks.md">Set up application bookmarks</a></p>
<p><a href="create-document-types-for-applicant-communication.md">Create document types for applicant communication</a></p>
<p><a href="select-a-default-recruitment-project-for-unsolicited-applications.md">Select a default recruitment project for unsolicited applications</a></p>
<p><a href="create-application-email-templates.md">Create application email templates</a></p></td>
</tr>
<tr class="even">
<td><p>Plan worker performance management</p></td>
<td><p>Decide how to set up performance management goals, goal and discussion types, and rating models.</p></td>
<td><p><a href="create-goal-headings.md">Create goal headings</a></p>
<p><a href="create-discussion-types.md">Create discussion types</a></p>
<p><a href="create-goal-types.md">Create goal types</a></p>
<p><a href="create-a-rating-model.md">Create a rating model</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan benefit plans</p></td>
<td><p>Decide how to set up benefit eligibility policies, rules, and plans.</p></td>
<td><p><a href="key-tasks-benefit-eligibility-policies.md">Key tasks: Benefit eligibility policies</a></p>
<p><a href="key-tasks-determine-benefit-eligibility.md">Key tasks: Determine benefit eligibility</a></p>
<p><a href="set-up-benefits.md">Set up benefits</a></p></td>
</tr>
<tr class="even">
<td><p>Plan Time and attendance management</p></td>
<td><p>Decide how to set up Time and attendance including planned absences, approval groups, and calculation groups.</p></td>
<td><p><a href="about-time-registration-workers.md">About time registration workers</a></p>
<p><a href="about-time-and-attendance-registrations.md">About time and attendance registrations</a></p>
<p><a href="about-registration-groups-for-time-and-attendance.md">About registration groups for time and attendance</a></p>
<p><a href="about-registrations-in-electronic-timecards.md">About registrations in electronic timecards</a></p>
<p><a href="about-adding-clock-out-registrations.md">About adding clock-out registrations</a></p>
<p><a href="about-payroll-in-time-and-attendance.md">About payroll in Time and attendance</a></p>
<p><a href="about-indirect-activities-for-time-and-attendance.md">About indirect activities for time and attendance</a></p>
<p><a href="about-profiles-for-time-and-attendance-registrations.md">About profiles for time and attendance registrations</a></p>
<p><a href="examples-profiles-for-time-and-attendance-registrations.md">Examples: Profiles for time and attendance registrations</a></p>
<p><a href="about-parameters-for-calculations.md">About parameters for calculations</a></p>
<p><a href="about-parameters-for-time-and-attendance.md">About parameters for time and attendance</a></p>
<p><a href="about-dimension-control-for-time-and-attendance.md">About dimension control for time and attendance</a></p>
<p><a href="about-pay-adjustments-and-count-units.md">About pay adjustments and count units</a></p>
<p><a href="example-of-a-pay-adjustment-for-time-and-attendance.md">Example of a pay adjustment for time and attendance</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan absence management</p></td>
<td><p>Decide how to set up worker absence information.</p></td>
<td><p><a href="about-absence-administration.md">About absence administration</a></p></td>
</tr>
<tr class="even">
<td><p>Plan training course management</p></td>
<td><p>Decide how to categorize training courses using course types. Learn about how to enter classrooms, instructors, course locations, and course group information.</p></td>
<td><p><a href="about-courses.md">About courses</a></p>
<p><a href="set-up-course-instructors.md">Set up course instructors</a></p></td>
</tr>
<tr class="odd">
<td><p>Plan the Employee Services site on  Enterprise Portal for Microsoft Dynamics AX</p></td>
<td><p>Learn about the tasks you can complete by using the Employee Services site.</p></td>
<td><p><a href="using-the-employee-services-site.md">Using the Employee Services site</a></p></td>
</tr>
<tr class="even">
<td><p>Consider position budgeting</p></td>
<td><p>Learn about position budgeting, which lets you create and work with forecast positions.</p></td>
<td><p><a href="set-up-position-budgeting.md">Set up position budgeting</a></p>
<p><a href="work-with-forecast-positions.md">Work with forecast positions</a></p>
<p><a href="about-budget-plans.md">About budget plans</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Configure

Complete the tasks in the following table to set up and configure Human resources. You should complete most of the tasks in the order they are listed. You can return to any setup area later to make changes as needed.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Set up Human resources parameters</p></td>
<td><p>Define all parameters before you set up other Human resources data. You can change these settings at any time.</p></td>
<td><p><a href="set-up-human-resources-parameters.md">Set up human resources parameters</a></p></td>
</tr>
<tr class="even">
<td><p>Set up number sequences</p></td>
<td><p>Set up number sequences before you assign number sequences to records in Human resources, such as personnel numbers. Then set up number sequences for the various types of records.</p></td>
<td><p><a href="set-up-number-sequences.md">Set up number sequences</a></p>
<p><a href="set-up-number-sequences-for-human-resources.md">Set up number sequences for Human resources</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up worker identification information</p></td>
<td><p>Set up identification types before you enter identification information for workers. In the United States, you must also set up issuing agencies and Form I-9 document types.</p></td>
<td><p><a href="set-up-identification-types.md">Set up identification types</a></p>
<p><a href="usa-set-up-issuing-agencies.md">(USA) Set up issuing agencies</a></p>
<p><a href="usa-set-up-form-i-9-document-types.md">(USA) Set up Form I-9 document types</a></p></td>
</tr>
<tr class="even">
<td><p>Configure personnel actions</p></td>
<td><p>Set up personnel actions, if you’re using them.</p></td>
<td><p><a href="configure-personnel-actions.md">Configure personnel actions</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up organization information for workers</p></td>
<td><p>Set up departments, jobs, and positions, and set up team types if you plan to use teams.</p></td>
<td><p><a href="key-tasks-departments.md">Key tasks: Departments</a></p>
<p><a href="key-tasks-jobs.md">Key tasks: Jobs</a></p>
<p><a href="key-tasks-new-worker-positions.md">Key tasks: New worker positions</a></p>
<p><a href="set-up-team-types.md">Set up team types</a></p></td>
</tr>
<tr class="even">
<td><p>Set up compensation information</p></td>
<td><p>Set up fixed, variable, and other compensation plans. If you want to associate compensation plans together with worker performance, set up pay for performance.</p></td>
<td><p>“Create a fixed compensation plan” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Create a variable compensation plan” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Create an eligibility rule for a compensation plan” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Create a performance plan” section in <a href="key-tasks-pay-for-performance.md">Key tasks: Pay for performance</a></p>
<p>“Set up performance ratings” section in <a href="key-tasks-pay-for-performance.md">Key tasks: Pay for performance</a></p>
<p>“Set up a pay for performance allocation” section in <a href="key-tasks-pay-for-performance.md">Key tasks: Pay for performance</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up loan items</p></td>
<td><p>Set up loan items, if you’re using them.</p></td>
<td><p><a href="create-loan-items.md">Create loan items</a></p></td>
</tr>
<tr class="even">
<td><p>Set up worker reference information</p></td>
<td><p>Set up worker reference information, such as titles, name sequences, and ethnic origins, before you can create worker records.</p></td>
<td><p><a href="key-tasks-set-up-reference-information-for-workers.md">Key tasks: Set up reference information for workers</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up competencies</p></td>
<td><p>Set up competencies before they can be assigned to workers, applicants, or contacts. You can set up many different competency types, such as education disciplines, institutions, degrees, skills, certificate types, project experiences, positions of trust, test types, and interests.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa589077(v=ax.60)">Education disciplines (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa557412(v=ax.60)">Education discipline category (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa616445(v=ax.60)">Institutions (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa571288(v=ax.60)">Degrees (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa591940(v=ax.60)">Skills (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa619900(v=ax.60)">Certificate types (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa575899(v=ax.60)">Project experience (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa591442(v=ax.60)">Position of trust (form)</a></p>
<p><a href="https://technet.microsoft.com/library/jj677419(v=ax.60)">Test types (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa577265(v=ax.60)">Interest (form)</a></p></td>
</tr>
<tr class="even">
<td><p>Set up injury and illness information</p></td>
<td><p>Set up the information that you will need if you have to report injuries or illnesses in the workplace.</p></td>
<td><p><a href="set-up-injury-and-illness-information.md">Set up injury and illness information</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up recruitment</p></td>
<td><p>Set up recruitment before you track applications and applicants for job openings. You must set up application bookmarks, create recruitment document types, specify a default recruitment project for unsolicited applications, and create application email.</p></td>
<td><p><a href="set-up-application-bookmarks.md">Set up application bookmarks</a></p>
<p><a href="create-document-types-for-applicant-communication.md">Create document types for applicant communication</a></p>
<p><a href="select-a-default-recruitment-project-for-unsolicited-applications.md">Select a default recruitment project for unsolicited applications</a></p>
<p><a href="create-application-email-templates.md">Create application email templates</a></p></td>
</tr>
<tr class="even">
<td><p>Set up performance information</p></td>
<td><p>Create goal headings, goal types, discussion types, and at least one rating model before you track performance elements and rate the performance of workers.</p></td>
<td><p><a href="create-goal-headings.md">Create goal headings</a></p>
<p><a href="create-goal-types.md">Create goal types</a></p>
<p><a href="create-discussion-types.md">Create discussion types</a></p>
<p><a href="create-a-rating-model.md">Create a rating model</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up benefits</p></td>
<td><p>Create benefits eligibility policies, benefit plans, and eligibility events before workers can be enrolled in benefits.</p></td>
<td><p><a href="key-tasks-benefit-eligibility-policies.md">Key tasks: Benefit eligibility policies</a></p>
<p><a href="set-up-benefits.md">Set up benefits</a></p>
<p><a href="key-tasks-determine-benefit-eligibility.md">Key tasks: Determine benefit eligibility</a></p></td>
</tr>
<tr class="even">
<td><p>Set up Time and attendance</p></td>
<td><p>Set up time and attendance policies. The specific steps you complete, and the sequence in which they’re completed will vary depending on the specific Time and attendance options you use.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa582300(v=ax.60)">Time and attendance configuration wizard (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa634266(v=ax.60)">Time and attendance parameters (form)</a></p>
<p><a href="about-parameters-for-calculations.md">About parameters for calculations</a></p>
<p><a href="about-registration-groups-for-time-and-attendance.md">About registration groups for time and attendance</a></p>
<p><a href="set-up-indirect-activities-for-time-and-attendance.md">Set up indirect activities for time and attendance</a></p>
<p><a href="about-profiles-for-time-and-attendance-registrations.md">About profiles for time and attendance registrations</a></p>
<p><a href="set-up-profiles-for-time-and-attendance-registrations.md">Set up profiles for time and attendance registrations</a></p>
<p><a href="set-up-profile-groups-for-time-and-attendance-registrations.md">Set up profile groups for time and attendance registrations</a></p>
<p><a href="about-payroll-in-time-and-attendance.md">About payroll in Time and attendance</a></p>
<p><a href="https://technet.microsoft.com/library/aa616991(v=ax.60)">Configure registration forms (form)</a></p>
<p><a href="https://technet.microsoft.com/library/aa585567(v=ax.60)">Terminals (form)</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up absence management</p></td>
<td><p>Set up absence management before you specify absence information for a worker, create absence journals, or register absences. You must create absence setups, absence groups, and absence codes, and specify a color for absence transactions.</p></td>
<td><p>“Create absence setups” section in <a href="key-task-set-up-absence-information.md">Key task: Set up absence information</a></p>
<p>“Create absence groups” section in <a href="key-task-set-up-absence-information.md">Key task: Set up absence information</a></p>
<p>“Create absence codes” section in <a href="key-task-set-up-absence-information.md">Key task: Set up absence information</a></p>
<p>“Specify a color for open absence transactions” section in <a href="key-task-set-up-absence-information.md">Key task: Set up absence information</a></p></td>
</tr>
<tr class="even">
<td><p>Set up course training</p></td>
<td><p>Set up instructors, course types, courses, course descriptions, agendas, tracks, and sessions before you assign an instructor to a course or register someone for a course.</p>
<p>Instructors must already exist as workers, applicants, or contacts. Therefore, you will probably have to return to this step after the necessary workers, applicants, or contacts have been created.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa618160(v=ax.60)">Course types (form)</a></p>
<p>“Create a course record” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Create a course agenda” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Specify a course description for a course” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Create a course track” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Create a course session” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p><a href="set-up-course-instructors.md">Set up course instructors</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up position budgeting and forecast positions</p></td>
<td><p>Set up position budgeting so you can work with forecast positions.</p></td>
<td><p><a href="set-up-position-budgeting.md">Set up position budgeting</a></p>
<p><a href="position-budgeting-setup-issues.md">Position budgeting setup issues</a></p>
<p>“Define budget purpose types” in <a href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Use

The following table provides links to key information and step-by-step instructions that help you make the best use of Human resources. This table provides links to most tasks that you have to perform in Human resources.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Recruit workers</p></td>
<td><p>Use recruitment projects to save and edit the text used when advertising for open positions and to accept applications for job openings.</p>
<p>Track responses to job postings for a specific recruitment project, or specific applicants, and update the status of open positions.</p></td>
<td><p><a href="about-recruitment-projects.md">About recruitment projects</a></p>
<p><a href="record-developments.md">Record developments</a></p>
<p><a href="about-applicants-and-applications.md">About applicants and applications</a></p></td>
</tr>
<tr class="even">
<td><p>Hire workers</p></td>
<td><p>Hire a single applicant or manage a mass hire project.</p></td>
<td><p><a href="hire-an-applicant.md">Hire an applicant</a></p>
<p><a href="about-mass-hire-projects.md">About mass hire projects</a></p></td>
</tr>
<tr class="odd">
<td><p>Onboard workers</p></td>
<td><p>Record general worker information, enter worker employment information, and request or grant accommodations requests for workers.</p>
<p>In the United States, before a person can start working, you must confirm that person’s legal eligibility to work using the Form I-9 verification process. In certain cases, you might have to designate an individual as a contractor instead of a worker.</p></td>
<td><p><a href="key-tasks-workers.md">Key tasks: Workers</a></p>
<p><a href="about-form-i-9-verification.md">About Form I-9 verification</a></p>
<p><a href="workplace-accommodations.md">Workplace accommodations</a></p>
<p><a href="contractors.md">Contractors</a></p></td>
</tr>
<tr class="even">
<td><p>Manage worker absence information</p></td>
<td><p>Track information about worker absences. You can record absence information for workers, create absence journals, and set up absence approval workflows.</p></td>
<td><p><a href="specify-absence-information-for-a-worker.md">Specify absence information for a worker</a></p>
<p><a href="create-absence-journals.md">Create absence journals</a></p>
<p><a href="register-absences.md">Register absences</a></p>
<p><a href="transfer-absence-journals-for-approval.md">Transfer absence journals for approval</a></p>
<p><a href="approve-or-reject-absences.md">Approve or reject absences</a></p>
<p><a href="delete-absence-journals.md">Delete absence journals</a></p></td>
</tr>
<tr class="odd">
<td><p>Train workers</p></td>
<td><p>Assign instructors to courses, update course statuses, register people for courses, and drop people from courses.</p></td>
<td><p>“Assign an instructor to a course” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Update the status of a course” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Register a person for a course” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p>
<p>“Drop a participant from a course” section in <a href="key-tasks-courses.md">Key tasks: Courses</a></p></td>
</tr>
<tr class="even">
<td><p>Manage worker competencies</p></td>
<td><p>Track competency information for workers, applicants, and contacts. You can also perform gap analysis and skill profile analysis.</p></td>
<td><p><a href="record-competencies.md">Record competencies</a></p>
<p><a href="create-a-skill-gap-analysis-or-a-skill-profile-analysis.md">Create a skill gap analysis or a skill profile analysis</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage organization information for workers</p></td>
<td><p>Update existing positions, such as changing the reporting relationships, relocating positions to a different department, retiring multiple positions at the same time, retiring a position when terminating employment, and placing one or more positions on hold at the same time. You can also view a list of the positions in a specific department and export a position hierarchy to Microsoft Visio. Create teams if you’re using them.</p></td>
<td><p>“Modify the reporting relationships for a position” section in <a href="key-tasks-existing-worker-positions.md">Key tasks: Existing worker positions</a></p>
<p>“Relocate positions to a different department” section in <a href="key-tasks-existing-worker-positions.md">Key tasks: Existing worker positions</a></p>
<p>“Retire multiple positions at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3” section in <a href="key-tasks-existing-worker-positions.md">Key tasks: Existing worker positions</a></p>
<p>“Terminate a worker and retire their position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3” section in <a href="key-tasks-existing-worker-positions.md">Key tasks: Existing worker positions</a></p>
<p>“Place one or more positions on hold at the same time in Microsoft Dynamics AX 2012 R2 or AX 2012 R3” section in <a href="key-tasks-existing-worker-positions.md">Key tasks: Existing worker positions</a></p>
<p><a href="view-a-list-of-the-positions-within-a-specific-department.md">View a list of the positions within a specific department</a></p>
<p><a href="export-a-position-hierarchy-to-microsoft-visio.md">Export a position hierarchy to Microsoft Visio</a></p>
<p>“Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3” section in <a href="key-tasks-new-worker-positions.md">Key tasks: New worker positions</a></p>
<p>“Create one or more new positions from an existing position in Microsoft Dynamics AX 2012 R2 or AX 2012 R3 when personnel actions are enabled” section in <a href="key-tasks-new-worker-positions.md">Key tasks: New worker positions</a></p>
<p>“Add a department to the department hierarchy” section in <a href="key-tasks-departments.md">Key tasks: Departments</a></p>
<p><a href="calculate-worker-distribution.md">Calculate worker distribution</a></p>
<p><a href="create-a-team.md">Create a team</a></p></td>
</tr>
<tr class="even">
<td><p>Manage worker performance</p></td>
<td><p>Set worker goals, maintain activities for goals, add comments to goals, and monitor performance discussions.</p></td>
<td><p><a href="set-a-goal.md">Set a goal</a></p>
<p><a href="maintain-activities-for-goals.md">Maintain activities for goals</a></p>
<p><a href="add-comments-to-goals.md">Add comments to goals</a></p>
<p><a href="key-tasks-discussions.md">Key tasks: Discussions</a></p>
<p><a href="key-tasks-discussions.md">Key tasks: Discussions</a></p>
<p><a href="key-tasks-discussions.md">Key tasks: Discussions</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage worker compensation</p></td>
<td><p>Enroll workers in fixed or variable compensation plans and rate workers who are enrolled in a pay for performance compensation plan. Change a worker’s fixed compensation plan and add exceptions to a worker’s variable compensation plan. Create and run compensation events and view the results. Use recommendations to adjust fixed increases or awards.</p></td>
<td><p>“Enroll an employee in a fixed compensation plan” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Maintain or change the fixed compensation of an employee” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Enroll an employee in a variable compensation plan” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Add exceptions to an employee’s variable plan enrollment” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Create and run a process event” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“View the results of a process event for an employee” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Enable recommendations on fixed or variable plans” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Use recommendations to adjust fixed increases or awards” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Approve an employee’s compensation change” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Update compensation from a compensation process event” section in <a href="key-tasks-compensation-plans.md">Key tasks: Compensation plans</a></p>
<p>“Enable pay for performance” section in <a href="key-tasks-pay-for-performance.md">Key tasks: Pay for performance</a></p>
<p>“Rate an employee” section in <a href="key-tasks-pay-for-performance.md">Key tasks: Pay for performance</a></p></td>
</tr>
<tr class="even">
<td><p>Manage benefits for workers</p></td>
<td><p>Enroll workers in benefits and remove benefits they’re currently enrolled in, enroll multiple workers in a benefit at the same time, create benefits, maintain dependent and beneficiary information, and maintain expiration dates for benefits.</p></td>
<td><p><a href="enroll-and-remove-benefits-for-workers.md">Enroll and remove benefits for workers</a></p>
<p><a href="enroll-multiple-workers-in-a-benefit-at-the-same-time.md">Enroll multiple workers in a benefit at the same time</a></p>
<p><a href="maintain-information-for-dependents-and-beneficiaries.md">Maintain information for dependents and beneficiaries</a></p>
<p><a href="create-a-new-benefit.md">Create a new benefit</a></p>
<p><a href="maintain-benefit-expiration-dates.md">Maintain benefit expiration dates</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage the workplace</p></td>
<td><p>Maintain employee injury and illness information and maintain information about equipment or items that are loaned to workers.</p></td>
<td><p><a href="maintain-employee-injury-and-illness-information.md">Maintain employee injury and illness information</a></p>
<p><a href="loan-an-item-to-a-worker-contact-or-applicant.md">Loan an item to a worker, contact, or applicant</a></p>
<p><a href="record-a-returned-loan-item.md">Record a returned loan item</a></p></td>
</tr>
<tr class="even">
<td><p>Manage time and attendance for workers</p></td>
<td><p>Enter and process time and attendance registrations. Some of these tasks might not apply, depending on the functionality you use.</p></td>
<td><p><a href="enable-workers-to-register-time-and-attendance.md">Enable workers to register time and attendance</a></p>
<p><a href="create-pay-types-in-time-and-attendance.md">Create pay types in time and attendance</a></p>
<p><a href="set-up-payroll-statistics-for-time-and-attendance.md">Set up payroll statistics for time and attendance</a></p>
<p><a href="set-up-pay-periods-for-time-registration-workers.md">Set up pay periods for time registration workers</a></p>
<p><a href="set-up-and-apply-piecework-in-production.md">Set up and apply piecework in production</a></p>
<p><a href="set-up-dimension-control-for-time-and-attendance.md">Set up dimension control for time and attendance</a></p>
<p><a href="synchronize-the-job-table.md">Synchronize the job table</a></p>
<p><a href="updating-payroll-data-for-time-and-attendance.md">Updating payroll data for time and attendance</a></p>
<p><a href="apply-profiles-using-work-planner.md">Apply profiles using work planner</a></p>
<p><a href="about-calculating-approving-and-transferring-registrations.md">About calculating, approving and transferring registrations</a></p>
<p><a href="modify-registrations-before-or-after-calculation.md">Modify registrations before or after calculation</a></p>
<p><a href="calculate-time-and-attendance-for-workers.md">Calculate time and attendance for workers</a></p>
<p><a href="modify-registrations-before-or-after-approval.md">Modify registrations before or after approval</a></p>
<p><a href="add-clock-out-registrations-for-workers.md">Add clock-out registrations for workers</a></p>
<p><a href="approve-time-and-attendance-registrations.md">Approve time and attendance registrations</a></p>
<p><a href="transfer-time-and-attendance-registrations.md">Transfer time and attendance registrations</a></p>
<p><a href="create-absence-registrations-for-planned-absences.md">Create absence registrations for planned absences</a></p>
<p><a href="send-messages-to-workers-during-registration.md">Send messages to workers during registration</a></p>
<p><a href="temporary-group-assignment.md">Temporary group assignment</a></p>
<p><a href="second-workers-to-another-group.md">Second workers to another group</a></p>
<p><a href="post-indirect-activities-costs.md">Post indirect activities costs</a></p>
<p><a href="adjust-flex-time-unit-count-and-statistical-payroll-balances.md">Adjust flex time, unit count, and statistical payroll balances</a></p>
<p><a href="about-registrations-with-future-timestamps.md">About registrations with future timestamps</a></p>
<p><a href="clean-up-old-time-and-attendance-registrations.md">Clean up old time and attendance registrations</a></p>
<p><a href="deactivate-past-workers.md">Deactivate past workers</a></p></td>
</tr>
<tr class="odd">
<td><p>Manage forecast positions</p></td>
<td><p>Create position forecasts to create a budget for filled or vacant positions, and to estimate payroll expenses for each position. You can create budget amounts by budget cycle, account, and dimension, and then import forecast data into a budget plan.</p></td>
<td><p>“Add an existing position to the forecast with a small modification” section in <a href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</a></p>
<p>“Create a new forecast position” section in <a href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</a></p>
<p><a href="https://technet.microsoft.com/jj729760">Enter budget defaults for a position</a></p>
<p>“Copy a forecast position to the forecast” section in <a href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</a></p>
<p>“Update multiple forecast positions” section in <a href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</a></p></td>
</tr>
<tr class="even">
<td><p>Create reports about workers and worker associated information</p></td>
<td><p>Generate various types of Human resources reports. Use the Human resources cube, which provides many of the reports that you will need. You can also create custom reports after the data cube has been deployed and processed.</p></td>
<td><p><a href="microsoft-dynamics-ax-reports.md">Microsoft Dynamics AX reports</a></p>
<p><a href="human-resources-reports.md">Human resources reports</a></p>
<p><a href="human-resources-cube-humanresourcecube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Human resources cube (HumanResourceCube) for Microsoft Dynamics AX 2012 R2 and R3</a></p>
<p><a href="generating-custom-reports-for-human-resources.md">Generating custom reports for Human resources</a></p></td>
</tr>
<tr class="odd">
<td><p>Retire a worker or terminate employment</p></td>
<td><p>Capture information if a worker retires or is terminated from your organization.</p></td>
<td><p><a href="terminate-employment.md">Terminate employment</a></p></td>
</tr>
</tbody>
</table>


Back to top

## Integration

Human resources can integrate with Payroll for Microsoft Dynamics AX 2012, and the Project management and accounting, Travel and expense, and General ledger modules in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Integrating module</p></th>
<th><p>Details</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Payroll for Microsoft Dynamics AX 2012</p></td>
<td><p>Human resources must be installed and configured before you use Payroll. Payroll uses information that is entered in Human resources, such as workers, positions information, and benefits information.</p></td>
<td><p><a href="payroll.md">Payroll</a></p></td>
</tr>
<tr class="even">
<td><p>Project management and accounting</p></td>
<td><p>Project management and accounting requires Human resources information. For example, workers in Human resources are assigned to projects in Project management and accounting.</p></td>
<td><p><a href="project-management-and-accounting.md">Project management and accounting</a></p></td>
</tr>
<tr class="odd">
<td><p>Travel and expense</p></td>
<td><p>Travel and Expense lets you create an integrated workflow where you can track the money that workers spend when they incur expenses for your business.</p></td>
<td><p><a href="travel-and-expense.md">Travel and expense</a></p></td>
</tr>
<tr class="even">
<td><p>General ledger</p></td>
<td><p>Payroll financial data can be moved into General ledger.</p></td>
<td><p><a href="general-ledger.md">General ledger</a></p></td>
</tr>
</tbody>
</table>


Back to top



