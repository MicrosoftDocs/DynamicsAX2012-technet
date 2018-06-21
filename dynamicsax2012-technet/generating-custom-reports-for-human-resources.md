---
title: Generating custom reports for Human resources
TOCTitle: Generating custom reports for Human resources
ms:assetid: 7f05681c-cb75-4d7f-8f7d-37ac098e4890
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527697(v=AX.60)
ms:contentKeyID: 59626229
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- custom report
- ad hoc reports
- custom reports
- ad hoc report
- ad hoc report HR
- ad hoc reports HR
- custom report HR
- data cube reports
- data cube report
- custom reports HR
- human resources report
- human resources reports
---

# Generating custom reports for Human resources [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The tables in this topic provide examples of common questions you might ask, and the measures and dimensions in the data cube for Human Resources that you can use to answer those questions.

After the data cube has been deployed and processed at least one time, you can use Microsoft Excel, Microsoft SQL Server Analysis Services, or other tools to create custom reports based on the data in the cube. As you become more familiar with the data cube, you’ll be able to find answers to more and more of your questions.

If you have Power View configured, you can also use the **Analyze data** button in the **Workers** list page to access the data cube. Power View provides quick and easy visualization of your data. When you use Power View, you can access the same measures and dimensions you would access by using Excel or SQL Server Analysis Services. After you select the dimensions and measures, you can quickly visualize raw data, adjust it to make multiple charts that correspond to each other, and save the charts to a library. You can access that library in a list format or place any chart from the library into any Role Center.


> [!TIP]
> <P>The data in the custom reports will be accurate as of the last time the cube was processed. To keep the data current, the cube should be processed frequently, for example, each night.</P>



For more information about how to create custom reports from the data in a cube, see [Create a report by using Power View to connect to a cube](create-a-report-by-using-power-view-to-connect-to-a-cube.md), [Create a report by using SQL Server Report Builder to connect to a cube](create-a-report-by-using-sql-server-report-builder-to-connect-to-a-cube.md), or [Create a report by using the Excel data connection wizard to connect to a cube](create-a-report-by-using-the-excel-data-connection-wizard-to-connect-to-a-cube.md).


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Demographic information

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and dimension attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>How much of the workforce is female versus male?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Gender</strong> dimension attribute under the <strong>Worker details</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Which ethnicities are represented at our organization?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Ethnic origin</strong> dimension attribute under the <strong>Worker details</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>What are the ages of our employees?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Birth date</strong> dimension attribute under the <strong>Worker details</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Are employees who were hired more than 10 years ago being promoted?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>The following dimension attributes under the <strong>Employment</strong> dimension:</p>
<ul>
<li><p><strong>Employment start date</strong></p></li>
<li><p><strong>Assignment start date</strong></p></li>
<li><p><strong>Assignment end date</strong></p></li>
</ul></li>
<li><p>The <strong>Position description</strong> dimension attribute under the <strong>Positions</strong> dimension</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>To see all of the positions that a worker has had, see the <STRONG>Worker position assignments</STRONG> table later in this topic.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>What are the names of workers in particular job types and departments?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>The <strong>Department</strong> - <strong>Name</strong> attribute under the <strong>Departments</strong> dimension</p></li>
<li><p>The <strong>Job type</strong> attribute under the <strong>Jobs</strong> dimension</p></li>
</ul>
<p></p></td>
</tr>
</tbody>
</table>


## Headcount, tenure, and turnover

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and dimension attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>What is our total headcount?</p></td>
<td><ul>
<li><p>The <strong>Number of active workers</strong> measure in the <strong>Employment turnover</strong> measure group</p></li>
<li><p>The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many hires did we have this month, quarter, or year?</p></td>
<td><ul>
<li><p>The <strong>Number of hired workers</strong> measure in the <strong>Employment turnover</strong> measure group</p></li>
<li><p>The <strong>Employment end date</strong>.<strong>Month</strong>, <strong>Employment end date</strong>.<strong>Quarter</strong>, or <strong>Employment end date</strong>.<strong>Year</strong> dimension attribute</p></li>
<li><p>(Optional) The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>(Optional) The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
<li><p>(Optional) A filter for the <strong>Employment end date</strong>.<strong>Year</strong> to equal a specific calendar year</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>Instead of using the employment start date, if you use the <STRONG>Employment end date</STRONG> dimension attributes with the <STRONG>Number of hired workers</STRONG> measure, the count displayed is the number of workers hired during the specified period.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>What are our turnover percentages this month, quarter, or year?</p></td>
<td><ul>
<li><p>The <strong>Employment turnover rate</strong> measure in the <strong>Employment turnover</strong> measure group</p></li>
<li><p>The <strong>Employment end date</strong>.<strong>Month</strong>, <strong>Employment end date</strong>.<strong>Quarter</strong>, or <strong>Employment end date</strong>.<strong>Year</strong> dimension attribute</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many employees are leaving versus staying at our organization? What are the reasons employees are leaving?</p></td>
<td><ul>
<li><p>The Number of workers terminated measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Termination reason</strong> dimension attribute under the <strong>Employment details</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>How many people are in each department?</p></td>
<td><ul>
<li><p>The <strong>Number of workers</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Department</strong> - <strong>Name</strong> attribute under the <strong>Departments</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Is turnover higher at different legal entities?</p></td>
<td><ul>
<li><p>The <strong>Employment turnover rate</strong> measure in the <strong>Employment turnover</strong> measure group</p></li>
<li><p>The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>How many employees have worked at the organization under six years, from 6 to 10 years, from 11 to 15 years, and more than 15 years?</p></td>
<td><ul>
<li><p>The measure with the years of service you want in the <strong>Workers</strong> measure group, for example, <strong>Workers with years of service 0-5 count</strong></p></li>
<li><p>(Optional) The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>(Optional) The <strong>Company</strong> dimension attribute under the <strong>Company</strong> dimension</p></li>
<li><p>(Optional) The <strong>Department</strong> – <strong>Name</strong> dimension attribute under the <strong>Departments</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many months has a particular worker worked here?</p></td>
<td><ul>
<li><p>The <strong>Number of months of service for a worker</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Skills, competencies, and training

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and dimension attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>What skills does a particular worker have?</p></td>
<td><ul>
<li><p>The <strong>Count of workers</strong> measure in the <strong>Competencies</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>The <strong>Skill</strong> dimension attribute under the <strong>Skills</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>What education does a particular worker have?</p></td>
<td><ul>
<li><p>The <strong>Count of workers</strong> measure in the <strong>Competencies</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>The <strong>Education disciplines</strong> and <strong>Description</strong> dimension attributes under the <strong>Education</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>What are the names of the courses that we track at our organization?</p></td>
<td><ul>
<li><p>The <strong>Count of workers</strong> measure in the <strong>Competencies</strong> measure group</p></li>
<li><p>The <strong>Course description</strong> dimension attribute under the <strong>Courses</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>What are the training courses that we are currently conducting?</p></td>
<td><ul>
<li><p>The <strong>Count of participants with training status</strong> in the <strong>Course participants</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Courses</strong> dimension:</p>
<ul>
<li><p><strong>Courses</strong></p></li>
<li><p><strong>Course description</strong></p></li>
<li><p><strong>Status</strong></p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>What are the names of the instructors and students for each course?</p></td>
<td><ul>
<li><p>The <strong>Count of participants with training status</strong> in the <strong>Course participants</strong> measure group</p></li>
<li><p>The <strong>Instructor</strong> dimension attribute under the <strong>Course instructors</strong> dimension</p></li>
<li><p>The <strong>Participants</strong> dimension attribute under the <strong>Course participants</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>What is the status of each possible course attendee?</p></td>
<td><ul>
<li><p>The <strong>Count of participants with training status</strong> in the <strong>Course participants</strong> measure group</p></li>
<li><p>The <strong>Status</strong> dimension attribute under the <strong>Course participants</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Which courses have started and ended this year and last year?</p></td>
<td><ul>
<li><p>The <strong>Count of participants with training status</strong> in the <strong>Course participants</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Media</strong> dimension:</p>
<ul>
<li><p><strong>Course start date</strong>.<strong>Date</strong></p></li>
<li><p><strong>Course end date</strong>.<strong>Date</strong></p></li>
</ul></li>
</ul></td>
</tr>
</tbody>
</table>


## Recruitment projects, applications, and applicants

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and dimension attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>What are the recruitment projects that we are currently recruiting for?</p></td>
<td><ul>
<li><p>The <strong>Count of applications</strong> measure in the <strong>Applications</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Recruitment projects</strong> dimension:</p>
<ul>
<li><p><strong>Recruitment projects</strong></p></li>
<li><p><strong>Recruitment project description</strong></p></li>
<li><p><strong>Open date</strong></p></li>
<li><p><strong>Close date</strong></p></li>
</ul></li>
</ul></td>
</tr>
<tr class="even">
<td><p>What are the names of the recruiter and hiring manager for the recruitment projects that we have open or that are completed within the past two years?</p></td>
<td><ul>
<li><p>The <strong>Applicants hired count</strong> measure in the <strong>Applications</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Recruitment projects</strong> dimension:</p>
<ul>
<li><p><strong>Recruitment projects</strong></p></li>
<li><p><strong>Recruitment project description</strong></p></li>
<li><p><strong>Open date</strong></p></li>
<li><p><strong>Close date</strong></p></li>
</ul></li>
<li><p>The <strong>Hiring manager</strong>.<strong>Worker</strong> dimension attribute under the <strong>Hiring manager</strong> dimension</p></li>
<li><p>The <strong>Recruiter</strong>.<strong>Worker</strong> dimension attribute under the <strong>Recruiter</strong> dimension</p></li>
</ul>
<div class="alert">

> [!TIP]
> <P>The hiring manager is often the new hire’s manager. If hiring managers are specified, they appear in the <STRONG>Hiring manager</STRONG> field in the <STRONG>Recruitment project</STRONG> form.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>What is the trend over the past 10 years for the average days to recruit?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Applicant employment start date</strong>.<strong>Year</strong> dimension attribute under the <strong>Applicant employment start date</strong> dimension</p></li>
<li><p>(Optional) The <strong>Recruitment projects</strong> dimension attribute under the <strong>Recruitment projects</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Did it take longer to recruit for certain positions or jobs?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Position</strong> dimension attribute under the <strong>Positions</strong> dimension or the <strong>Job</strong> dimension attribute under the <strong>Jobs</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Did it take longer to recruit if a particular recruiter was assigned?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Recruiter</strong>.<strong>Worker</strong> dimension attribute under the <strong>Recruiter</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Did it take longer to recruit if a particular hiring manager was involved?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Hiring manager</strong>.<strong>Worker</strong> dimension attribute under the <strong>Hiring manager</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Did it take longer to recruit for the same position in one year versus another year?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Position</strong> dimension attribute under the <strong>Positions</strong> dimension</p></li>
<li><p>The <strong>Applicant employment start date</strong>. <strong>Year</strong> dimension attribute under the <strong>Applicant employment start date</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Did it take longer if the project involved recruiting for multiple openings?</p></td>
<td><ul>
<li><p>The <strong>Average days to recruit</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Recruitment projects</strong> dimension:</p>
<ul>
<li><p><strong>Recruitment projects</strong></p></li>
<li><p><strong>Number of openings</strong></p></li>
</ul></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>How many applicants have we hired this year, last year, and in previous years?</p></td>
<td><ul>
<li><p>The <strong>Applicants hired count</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Recruitment project description</strong> under the <strong>Recruitment projects</strong> dimension</p></li>
<li><p>The <strong>Applicant name</strong> dimension attribute under the <strong>Applicant</strong> dimension</p></li>
<li><p>The <strong>Applicant employment start date</strong>.<strong>Year</strong> dimension attribute under the <strong>Applicant employment start date</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many applications did we receive today, this week, or this past month?</p></td>
<td><ul>
<li><p>The <strong>Count of applications</strong> measure in the <strong>Applications</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Applications</strong> dimension:</p>
<ul>
<li><p><strong>Date of receipt</strong></p></li>
<li><p><strong>Applications</strong></p></li>
</ul></li>
<li><p>(Optional) The <strong>Applicant name</strong> dimension attribute under the <strong>Applicant</strong> dimension</p></li>
<li><p>(Optional) The <strong>Recruitment project description</strong> under the <strong>Recruitment projects</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>How many recruitment projects are currently interviewing?</p></td>
<td><ul>
<li><p>The <strong>Count of applications</strong> measure in the <strong>Applications</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Applications</strong> dimension:</p>
<ul>
<li><p><strong>Application status</strong></p></li>
<li><p><strong>Applications</strong></p></li>
</ul></li>
<li><p>The following dimension attributes under the <strong>Recruitment projects</strong> dimension:</p>
<ul>
<li><p><strong>Recruitment projects</strong></p></li>
<li><p><strong>Recruitment project description</strong></p></li>
</ul></li>
<li><p>(Optional) The <strong>Applicant name</strong> dimension attribute under the <strong>Applicant</strong> dimension</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>How many applications do we receive from particular online job sites, newspapers, or trade magazines?</p></td>
<td><ul>
<li><p>The <strong>Count of applications</strong> measure in the <strong>Applications</strong> measure group</p></li>
<li><p>The following dimension attributes under the <strong>Media</strong> dimension:</p>
<ul>
<li><p><strong>Media</strong></p></li>
<li><p><strong>Description</strong></p></li>
<li><p><strong>Media type</strong></p></li>
</ul></li>
</ul>
<div class="alert">

> [!TIP]
> <P>Both <STRONG>None</STRONG> and <STRONG>Unknown</STRONG> mean that there is no media or media type for that application.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>How many applicants are subsequently hired from each of those media sources? Have particular media sources had a trend of producing more or fewer hires over the past 10 years?</p></td>
<td><ul>
<li><p>The <strong>Applicants hired count</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Media</strong> dimension attribute under the <strong>Media</strong> dimension</p></li>
</ul>
<p>–or–</p>
<ul>
<li><p>The <strong>Applicants hired count</strong> measure in the <strong>Recruitment projects</strong> measure group</p></li>
<li><p>The <strong>Recruitment project description</strong> under the <strong>Recruitment projects</strong> dimension</p></li>
<li><p>The <strong>Applicant name</strong> dimension attribute under the <strong>Applicant</strong> dimension</p></li>
<li><p>The <strong>Applicant employment start date</strong>.<strong>Date</strong> dimension attribute under the <strong>Applicant employment start date</strong> dimension</p></li>
<li><p>The <strong>Media</strong> dimension attribute under the <strong>Media</strong> dimension</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Worker position assignments

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Questions to answer</p></th>
<th><p>Measures and dimension attributes to use</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>What are the active and past positions that a particular worker has held at our organization?</p></td>
<td><ul>
<li><p>The <strong>Number of position assignments</strong> measure in the <strong>Workers</strong> measure group</p></li>
<li><p>The <strong>Worker</strong>.<strong>Worker - Name</strong> dimension attribute under the <strong>Worker</strong> dimension</p></li>
<li><p>The following dimension attributes under the <strong>Positions</strong> dimension:</p>
<ul>
<li><p><strong>Position</strong></p></li>
<li><p><strong>Position description</strong></p></li>
<li><p><strong>Is position worker assignment active</strong></p></li>
</ul></li>
</ul>
<p>The value of the <strong>Is position worker assignment active</strong> dimension for a current position is <strong>Yes</strong>, and for a past position is <strong>No</strong>.</p>
<div class="alert">

> [!TIP]
> <P>Under the <STRONG>Positions</STRONG> dimension, there are two dimension attributes for the position ID, <STRONG>Position</STRONG> and <STRONG>Positions</STRONG>. <STRONG>Position</STRONG> shows distinct values while <STRONG>Positions</STRONG> shows duplicates. When you create a report by using measures and dimensions, it doesn’t matter which one you use; both attributes produce the same results.</P>


</div></td>
</tr>
</tbody>
</table>


## Tips

  - Some dimensions, such as those related to benefit deductions and contributions, do not contain date attributes. For these dimensions, you can’t answer questions about what a measure was during a particular time period, or how it changed over time.

  - When you work with the **Worker details** dimension and the **Positions** dimension, you see attributes called **ValidFrom** and **ValidTo**. Use these dimension attributes when you analyze date-effective information about positions and workers.
    
    To see which worker details are date effective, click the **Maintain versions** button in the **Worker** or **Position** form to open the date manager form. All these field values have an effective date and an expiration date, which are reflected in the cube as **ValidFrom** and **ValidTo**.

  - Under the **Employment** dimension, you can use the **Is position detail active** and **Is position worker assignment active** dimension attributes that are set to **Yes** to help you view date-effective data. These attributes filter out data that is out of date. For example, if you use the **Number of employments** measure together with the company, department, and worker dimensions, you might see a count of 11 instead of 7 because a worker might have worked in one of the positions in a specific department in the past. The past position adds to the count unless you set **Is position worker assignment active** to **Yes**.

  - A worker can have more than one position assignment and can work in more than one company at the same time. As a result, the **Number of employments** measure and the **Number of position assignments** measure in the **Payroll workers** measure group give different results when they are used with the **Company** dimension. The **Company** dimension attribute represents the legal entity. When you use it with the **Number of employments** measure, it shows the number of past, present, and future workers in the legal entity. When you use it with the **Number of position assignments** measure, it shows the total number of past, present, and future position assignments that have been assigned to workers in a company.

  - When you work with demographic information such as gender, you might wonder about the difference between **Unknown** and **None**. **Gender** is an optional field in the HcmPersonPrivateDetails table, so if a record exists for that worker in that table and this field is not set, it shows as **None**. **Unknown** is displayed if there is no record in that table for that worker. You can use filters to keep these from being displayed.

  - Under the **Worker** dimension, there are two dimension attributes for the names of workers, **Worker**.**Worker** and **Worker**.**Worker - Name**. The **Worker**.**Worker** attribute shows duplicates, and the **Worker**.**Worker - Name** attribute shows distinct values. When you create a report by using measures and dimensions, it doesn’t matter which one that you use; both attributes produce the same results.

  - As you work with dimensions, sometimes you see an **IsNotApplicable** dimension attribute. This attribute is added to every dimension because one row always is retained for records that are not applicable. If a measure contains any values that are not in the dimension, the measure is designated as **IsNotApplicable**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

