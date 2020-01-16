---
title: 'Key task: Set up absence information'
TOCTitle: 'Key task: Set up absence information'
ms:assetid: 2ad57f5f-78c0-41d3-88c4-1f6a55ddbb4f
ms:mtpsurl: https://technet.microsoft.com/library/Hh496453(v=AX.60)
ms:contentKeyID: 37072035
author: Khairunj
ms.date: 09/02/2014
mtps_version: v=AX.60
f1_keywords:
- implementation
- absence
- employee
- worker
- implementing
audience: Application User
ms.search.region: Global
---

# Key task: Set up absence information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides key information about setting up the absence functionality in Human resources.

## What do you want to do?

Learn more about...

Create absence setups

Create absence groups

Create absence codes

Specify a color for open absence transactions

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About absence administration](about-absence-administration.md)

 

## Create absence setups

For some companies, or for groups of workers in the same company, it is necessary to have multiple absence periods, multiple absence administrators, and different working times to track workers’ absences. To allow for this differentiation, you can create absence setups.

### Create an absence setup

1.  Click **Human resources** \> **Setup** \> **Absence** \> **Absence setup**.

2.  Click **New**.

3.  Enter a name and description for the absence setup.

4.  Select the length of the period in which absences must be registered for workers who will be assigned to the absence setup.
    
    For example, to track a worker’s absences on a monthly basis, select **Calendar month**. Any worker who is assigned to the absence setup must transfer their absence registrations monthly for approval.
    
    To use a flexible registration period, select **No period**. This enables the person assigned to the absence setup to register absence, as needed, and reduces how often absence journals must be created.

5.  Select the absence administrator for the absence setup. The absence administrator approves or rejects absences for workers who are assigned to the absence setup.

6.  Select the period when absences will be registered from the following options:
    
      - **Days**
    
      - **Hours**
    
    For example, to track absences by the days that a worker missed, select **Days**.

7.  Click **Close**.

Back to top

 

## Create absence groups

Absence groups are logical groups of absence codes. For example, an absence group titled Personal might include the following absence codes:

  - Dentist

  - Doctor

  - Funeral

  - Wedding

### Create an absence group

1.  Click **Human resources** \> **Setup** \> **Absence** \> **Absence groups**.

2.  Click **New**.

3.  Enter a name and description for the absence group.

4.  If you use time and attendance, and you have workers with flexible work hours, select the **Reduce flex** check box to reduce the balance of flexible hours for workers who register an absence by using an absence code in the absence group.

5.  If you use time and attendance, and you have workers who work overtime hours, select the **Deduct overtime** check box to reduce overtime hours for workers who register an absence by using an absence code in the absence group.

6.  Select the **Registration** check box to enable workers to enter an absence registration by using the absence codes in the absence group.

7.  Click **Close**.

Back to top

 

## Create absence codes

Absence codes indicate the reasons for worker absences. For each absence code, you can also set up validation rules that indicate how often during a specific period that a worker can be absent for the same reason.

For example, you could create an absence code titled Doctor Visit for when a worker has to miss work to visit a doctor. By using validation rules, you could also specify that workers can only be absent from work for two doctor visits per month.

### Create an absence code

1.  Click **Human resources** \> **Setup** \> **Absence** \> **Absence codes**.

2.  Click **New**.

3.  Enter a name and description for the absence code.

4.  If you plan to use absence validation rules, select the text color and the background color for the absence code.
    
    The color codes that you specify are used in the **Absence administration** form, where you can view a list of the workers who have violated absence validation rules.

5.  Select the absence group to include this absence code in.
    

    > [!NOTE]
    > <P>In cumulative update 7 or later for Microsoft Dynamics AX 2012 R2, if you use <STRONG>Time and attendance</STRONG>, on the <STRONG>Time and attendance</STRONG> FastTab, in the <STRONG>Icon</STRONG> field, you can specify the identifier for an icon for the absence code. The icon is displayed for the absence code when a worker clocks in or clocks out at a time that is outside typical working hours. However, before you can enter the identifier, the icon must be added to the list of embedded resources in Microsoft Dynamics AX. For assistance, contact your system administrator.</P>



### Add validation rules to an absence code

1.  Click **Human resources** \> **Setup** \> **Absence** \> **Absence codes**.

2.  In the left pane, select the absence code to add validation rules to.

3.  Expand the **Validations** FastTab.

4.  To create a **Max. in series** validation rule, read the example, and then complete the following steps.
    
    **Example**
    
    The rule is that only three consecutive absence days are allowed in a two-month period.
    
    1.  Select the **Active** check box to activate this rule.
    
    2.  To indicate that the rule only applies to work days, select the **Work days** check box.
    
    3.  Enter the number of consecutive absence days that are allowed. For the example rule, you would enter 3.
    
    4.  Enter the number of period units. For the example rule, you would enter 2.
    
    5.  Select the period code. For the example rule, you would select **Months**.

5.  To create a **Max. days in a period** validation rule, read the example, and then complete the following steps.
    
    **Example**
    
    The rule is that a worker can only have 10 absences that span multiple days in a one-year period.
    
    1.  Select the **Active** check box to activate this rule.
    
    2.  Enter the number of multiple-day absences that are allowed. For the example rule, you would enter 10.
    
    3.  Enter the number of period units. For the example rule, you would enter 1.
    
    4.  Select the period code. For the example rule, you would select **Year**.

6.  To create a **Max. series in a period** validation rule, read the example, and then complete the following steps.
    
    **Example**
    
    The rule is that a worker can only have five instances of multiple-day absences in a 52-week period.
    
    1.  Select the **Active** check box to activate this rule.
    
    2.  To indicate that the rule only applies to work days, select the **Work days** check box.
    
    3.  Enter the number of occurrences of multiple-day absences that are allowed. For the example rule, you would enter 10.
    
    4.  Enter the number of period units. For the example rule, you would enter 52.
    
    5.  Select the period code. For the example rule, you would select **Weeks**.

Back to top

 

## Specify a color for open absence transactions

To make it easier for workers and absence administrators to notice open absence transactions in the **Register absences** form, you can specify a color for open absence transactions. In the **Register absences** form, the rows in the grid that represent open absence transactions are displayed in the color that you select for open absence transactions.

1.  Click **Human resources** \> **Setup** \> **Parameters** \> **Human resources parameters**.

2.  Click **General** to display the **Set up Human resources** page.

3.  Select a color to apply to all open absence transactions.

Back to top

## Find form help

[Absence groups (form)](https://technet.microsoft.com/library/aa553840\(v=ax.60\))

[Absence setup (form)](https://technet.microsoft.com/library/aa583231\(v=ax.60\))

[Absence codes (form)](https://technet.microsoft.com/library/aa571804\(v=ax.60\))

[Absence status (form)](https://technet.microsoft.com/library/aa600265\(v=ax.60\))

[Human resource parameters (form)](https://technet.microsoft.com/library/aa596451\(v=ax.60\))

## Find related tasks

[Specify absence information for a worker](specify-absence-information-for-a-worker.md)

[Create absence journals](create-absence-journals.md)

[Register absences](register-absences.md)

  


