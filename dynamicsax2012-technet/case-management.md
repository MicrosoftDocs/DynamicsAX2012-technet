---
title: Case management
TOCTitle: Case management
ms:assetid: 14cfee9d-9a37-4b29-8869-ddc9486401d6
ms:mtpsurl: https://technet.microsoft.com/library/Hh242147(v=AX.60)
ms:contentKeyID: 36056057
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Case management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



You can use case management in Microsoft Dynamics AX and in Enterprise Portal for Microsoft Dynamics AX to record, update, track, follow up on, and close issues that are raised by your customers, vendors, or workers, or that are created through your audit processes. By planning, tracking, and analyzing cases, you can develop efficient resolutions that can be used for similar issues.

For example, when customer service representatives or human resources generalists create cases, they can find information in knowledge articles about how to work with or resolve a case more efficiently. For more information about knowledge articles, see [Store a knowledge article](store-a-knowledge-article.md).

Because you can use case management for customer, vendor, or worker issues, the **Cases** form is located in **Home** in Microsoft Dynamics AX. Audit cases are always managed in **Compliance and internal controls**, even when they relate to documents that are created in other modules.

## Additional case management features for production in cumulative update 7 for Microsoft Dynamics AX 2012 R2

In cumulative update 7 for Microsoft Dynamics AX 2012 R2, additional case management features can help manufacturing companies document changes to products. Product changes can include changes to a bill of materials, formulas, and routes. For more information, see [About product change cases](about-product-change-cases.md).

## Setup

Vince, the operations manager for Fabrikam, wants customer service representatives and human resources generalists to be able to create cases for customers, vendors, and employees. Before any one of these cases can be created, Vince must set up case categories and case processes.

Cassie, an internal auditor at Fabrikam, wants audit cases to be generated automatically when the audit policy is run against expense reports. Each audit case contains a group of audit policy violations.

Cassie also wants to have the option to create audit cases manually. For these cases, she can use the categories that are created when an audit policy is run, or she can create special categories to use for cases that are manually created.

For more information about how to create case processes and categories, see [Create case processes and categories](create-case-processes-and-categories.md).

## Case grouping and categories

The first step for Cassie is to determine how audit violations should be grouped into cases. By default, each audit case contains all of the audit violations that were created for a particular document type and audit policy rule. Cassie can specify other case grouping criteria if she chooses. For more information about audit case grouping, see [Key tasks: Audit policies](key-tasks-audit-policies.md).

The first thing Vince must do is create categories for cases. Case categories group similar case types together. For example, Vince might create categories for sales, employee benefits, or deliveries. He might also create child categories that group the cases at a more detailed level. For example, under a sales category, Vince could add child categories for pre-sale issues and post-sale issues.

Cassie can decide to create categories for cases that are created manually. She does not have to create categories for audit cases that are created automatically.

Every case must be assigned to a case category.

Grouping cases by category can help Fabrikam employees identify known solutions, such as knowledge articles, if similar issues occur over time.

## Processes

After they create case groupings and categories, Vince and Cassie can create the processes that every case must follow from beginning to resolution. For example, a process might require that a case issue be assigned to a Fabrikam employee within 24 hours of when the case is created.

## Working with cases

After setup is complete, Fabrikam employees with the appropriate permissions can create cases as issues are raised. Cases can be created in Microsoft Dynamics AX and in Enterprise Portal.

The following table describes tasks that Fabrikam employees can perform when they work with case management.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="create-a-case.md">Create a case</a></p></td>
<td><p>Create a new case record for a customer, vendor, or employee, or for the results of an audit of business documents.</p></td>
</tr>
<tr class="even">
<td><p><a href="add-details-to-a-case.md">Add details to a case</a></p></td>
<td><p>Add detailed information such as activities to a case.</p></td>
</tr>
<tr class="odd">
<td><p><a href="close-a-case.md">Close a case</a></p></td>
<td><p>Change the status of an open case to <strong>Closed</strong> to indicate that the issue has been resolved.</p></td>
</tr>
<tr class="even">
<td><p><a href="store-a-knowledge-article.md">Store a knowledge article</a></p></td>
<td><p>Create and store a knowledge article that includes tips, solutions, and other important information about an issue.</p></td>
</tr>
<tr class="odd">
<td><p><a href="rank-a-knowledge-article.md">Rank a knowledge article</a></p></td>
<td><p>Rate a knowledge article to indicate if it was successful in helping to close a case.</p></td>
</tr>
</tbody>
</table>


## Example: How Fabrikam uses case management for customers in the private sector

Lisa, a customer service representative at Fabrikam, receives a telephone call from Lionel, a Fabrikam customer. Lionel is having trouble setting the correct volume level on the new sound system that Fabrikam just installed in Lionel’s music store. Lisa creates a case for Lionel and assigns the category Volume to the case. Because Lisa knows that it is important for Lionel to have music in his store, she elevates the priority and assigns a one-day service level agreement (SLA) to the case. She also enters the case details in the case log. Lisa notices that there are several knowledge articles that are associated with the Volume category and that three of them are marked as helpful in resolving cases.

Lisa opens each article and discusses the resolution steps with Lionel, but none of the solutions solve the problem that Lionel is encountering with his new sound system. Lisa tells Lionel that within 24 hours an audio technician will call him and will work with him to attempt to solve the problem. Lisa activates the case and a set of activities is created. She assigns the activities to Terrence, a member of the audio engineering team.

Terrence sees that new activities have been assigned to him. He opens the case and reads the case log to learn more about the case. Terrence encountered the same issue the day before, and he developed a solution. Terrence contacts Lionel and offers a solution for the issue. Terrence also enters the solution in the case details. His solution is successful, and he decides to document the solution for others to use if they encounter the same problem. Terrence adds the document to the **Knowledge article** form, assigns the document to the Volume category, and manually elevates the ranking so that other Fabrikam employees will know that this is a successful solution.

Now Terrence elevates the case to the next level. Elevating the case creates a new activity for Marie, who is a quality assurance representative in the customer service department. Marie sees that a new activity is assigned to her, and she opens the case that is associated with the activity. Marie reviews the case and the case details to make sure that the process was followed correctly for the case. She verifies that the actual case time did not exceed the timeframe that was estimated in the SLA. She notes that Terrence contacted the customer and that the issue was resolved. Marie is satisfied with the treatment of the customer and the results of the case. She resolves the case as closed. When Marie closes the case, the open activity that is assigned to her is also closed.

## Example: How City Power and Light uses case management for customers in the public sector

Annie, a customer service representative with City Power and Light, receives a telephone call from a resident of the city that is served by City Power and Light. Annie records the call as an activity and takes notes of the conversation.

The resident tells Annie that his house has no power. Annie informs the resident that City Power and Light will investigate, locate, and resolve the problem as quickly as possible. She then creates a case, associates the telephone call with the case, and creates a service order.

Annie knows that it is likely that other residents will call to report a power outage. To avoid overwhelming the customer service center, and to save time, Annie sends a group instant message to inform the other representatives about the issue and to tell them that a case and service order have been created. She includes the case number and service order number in her instant message. If City Power and Light receives more telephone calls about the power outage, the customer service representatives can create an activity for each telephone call and assign them to the existing case.

## Examples: How Fabrikam uses case management for employees

The following scenarios show how Fabrikam Human Resources generalists in different locations can use case management when they address issues for employees.

## In the United States

Luke, the Human Resources generalist for the United States division of Fabrikam, receives an e-mail message from Shannon, a Fabrikam employee. Shannon is a machine operator who was injured on the job six months ago. She has been working with Humongous Insurance since the accident to have her medical expenses paid.

Shannon contacted Luke regarding this issue four weeks ago. Therefore, a case has already been created. Shannon’s e-mail message explains that Humongous Insurance is still not returning her telephone calls. Luke opens the existing case, adds Shannon’s e-mail message as a document, and reviews the case log.

When Luke created this case, he assigned it to the case category Insurance. He sees that there is a new knowledge article that is associated with the Insurance category. Luke reads the knowledge article and learns that Humongous Insurance’s telephone system is being updated and that all phones are down. The article states that an e-mail message was sent to all insurance customers but that several customers did not receive the message because of a problem with the insurance company’s e-mail system. All customers who have active insurance claims are being asked to send their inquiries by e-mail or by paper mail to Humongous Insurance.

Luke sends Shannon an e-mail message that explains what she must do to have her insurance claim settled. He also ranks the knowledge article that he read as a helpful piece of information.

Luke creates another activity for himself to follow up with both Shannon and Humongous Insurance in four weeks to make sure that the claim has been resolved. After four weeks have passed, Luke checks in with Shannon and learns that Humongous Insurance has paid her claims and that she is happy with the resolution. Luke changes the status of the case to Closed.

## In the United Kingdom

Cristine, the Human Resources generalist for the United Kingdom division of Fabrikam, receives a telephone call from Claus, a Fabrikam employee. Claus informs Cristine that nine weeks ago, immediately after the birth of his son, he changed the number of dependents on his tax withholdings. Claus wants to know why the changes have not become effective.

Cristine creates a case for Claus. She reviews Claus’s tax information and learns that although Claus did enter new dependent information, he did not select a start date for the new tax withholdings. Cristine sends an e-mail message to inform Claus that he must select a start date and resubmit his changes. Claus replies to Cristine’s message and tells her that he has now selected a start date and resubmitted his changes. Cristine attaches the e-mail message from Claus to the case record, verifies that the correct changes were made and submitted, and closes the case.

## See also

[About audit policy violations and cases](about-audit-policy-violations-and-cases.md)

[Case grouping criteria (form)](https://technet.microsoft.com/library/hh209729\(v=ax.60\))

  


