---
title: Create case processes and categories
TOCTitle: Create case processes and categories
ms:assetid: f2b47520-5705-49db-9e5d-9ebf4997842b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh370706(v=AX.60)
ms:contentKeyID: 36811440
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create case processes and categories 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you start to create cases, you must set up case processes and case categories.

For audit cases, you might want to set up user-defined case grouping criteria. By default, audit policy violations are grouped by document type and audit policy rule, and each group of violations forms a single audit case.

## Create a case process

1.  Click **Sales and marketing** \> **Setup** \> **Cases** \> **Case processes**.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Cases** \> **Case processes**.

2.  Click **New** to create a new case. To copy an existing case, click **Functions** \> **Copy from**, and then in the **Copy from** form, on the **General** tab, select the process that you want to copy.

3.  Enter a name and a description for the case process and select the process type.

4.  Click the **Actions** button and select whether to create a level or activity for the process.
    
    A level is a set of steps to follow when you are working with a case. An activity is a task that is associated with a level.

5.  Enter information about the level or activity that you are adding to the case process.

6.  On the **General** FastTab, in the **Responsibility** and **Responsible** fields, select the role and the worker assigned to the level or activity that you are creating. You can also enter any applicable notes in the **Notes** field.

7.  On the **Responsibilities** FastTab, add any other responsibility types that will be involved in completing the case process, and remove any that no longer apply.

8.  If you are creating a second-level or child case process, on the **Exit criteria** FastTab, select whether to check for required activities when the case process is completed.

After you create the process, you can save it as a template for other processes by clicking **Functions** \> **Save as template**.

## Customize case grouping criteria for audit cases

1.  Click **Compliance and internal controls** \> **Setup** \> **Audit** \> **Case grouping criteria**.

2.  Select the document type to create case grouping criteria for.

3.  In the **Grouping criteria** field, select **Document attributes**.

4.  In the **Available fields** list, select the fields to group audit cases by, and then click the arrow button to move the fields to the **Selected fields** list.

## Create a case category

1.  Click **Sales and marketing** \> **Setup** \> **Cases** \> **Case categories**.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Cases** \> **Case categories**.

2.  Click **New** \> **Case category**.

3.  Enter a name and a brief description of the category and select the category type.

4.  Select a worker to be the default owner of the category and the department where the worker works.

5.  Select the e-mail type and questionnaire to use for follow-up for cases that are included in this category.

6.  Select a default case process and service level agreement to associate with the category.

7.  After you fill in the category information, press F5 to refresh the form. The new category appears in the tree.

## Create a child case category

1.  Click **Sales and marketing** \> **Setup** \> **Cases** \> **Case categories**.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Cases** \> **Case categories**.

2.  In the tree in the left pane, select the case that you want to create a child case for.

3.  Click **New** \> **Child case category**.

4.  Enter a name for the child case category and fill in the remaining fields.

5.  After you fill in the category information, press F5 to refresh the form. The new child category appears in the tree under the parent category.

## See also

[Case management](case-management.md)

[About audit policy violations and cases](about-audit-policy-violations-and-cases.md)

[Case process (form)](https://technet.microsoft.com/en-us/library/hh242460\(v=ax.60\))

[Case categories (form)](https://technet.microsoft.com/en-us/library/hh209319\(v=ax.60\))

[Case grouping criteria (form)](https://technet.microsoft.com/en-us/library/hh209729\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

