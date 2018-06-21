---
title: Maintain benefit expiration dates
TOCTitle: Maintain benefit expiration dates
ms:assetid: 7fdb9475-0e61-41a2-927e-20deba9b6034
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn282390(v=AX.60)
ms:contentKeyID: 54906704
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- benefit end date
- benefit ending date
- benefit expiration
- benefit expiration date
- coverage ending date
- coverage expiration date
- Forms.HcmMassBenefitExpiration
- MsDynAx060.Forms.HcmMassBenefitExpiration
- benefit effective date
- benefit effective dates
- benefit expiration dates
- benefit end dates
- benefit ending dates
- coverage effective date
- coverage effective dates
- coverage end dates
- coverage end date
- coverage ending dates
- coverage expiration dates
---

# Maintain benefit expiration dates [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Mass benefit expiration allows you to change the expiration date of a benefit and of the enrollments of workers enrolled in that benefit at the same time. You can also select multiple workers who are enrolled in a benefit and change the ending date of their coverage. Depending on your version of Microsoft Dynamics AX 2012, the date when a worker’s coverage in a benefit expires may be called the enrollment end date or the coverage end date.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



Mass benefit expiration is available only when you select a single benefit that is active or that becomes active in the future. It is not available for tax levies or garnishments.


> [!TIP]
> <P>If the time zone that is set for the legal entity differs from the time zone where the benefit was created, the mass benefit expiration process might result in some dates being off by one calendar day. If this occurs, you can adjust the dates by running the process again.</P>



## Expire a benefit and end benefit coverage for all affected workers at the same time

When you change the expiration date of a benefit to an earlier date, all worker enrollments that end after the new date are changed so that they expire on the earlier date. Any worker enrollments that end before the new benefit expiration date are not affected. Any worker enrollments that are scheduled to begin after the new benefit expiration date are deleted.


> [!NOTE]
> <P>To expire a benefit that has no enrolled workers, use the <STRONG>Maintain versions</STRONG> form. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227640(v=ax.60)">Maintain benefit versions (form)</A>.</P>



1.  Click **Human resources** \> **Common** \> **Benefits** \> **Benefits**.

2.  Select a benefit, and then click **Mass benefit expiration**.

3.  In the **Update option** field, select **Expire the benefit and affected worker enrollments**.

4.  In the **New benefit expiration date** field, enter the date when the benefit will expire.

5.  Click **Expire**.
    
    The expiration date of the benefit and the coverage ending date for all affected workers are changed to the new benefit expiration date.

6.  When the process is complete, review the **Mass benefit expiration results** form to verify that all changes have been made. The results can be exported to Microsoft Excel for future reference or analysis.

## Extend a benefit and benefit coverage for multiple workers at the same time

When you change the benefit expiration date to a later date, you can change the coverage ending date of selected workers to the new date at the same time.

1.  Click **Human resources** \> **Common** \> **Benefits** \> **Benefits**.

2.  Select a benefit, and then click **Mass benefit expiration**.

3.  In the **Update option** field, select **Extend the benefit and selected worker enrollments**.

4.  In the **New benefit expiration date** field, enter the date when the benefit will expire.

5.  Select the workers to extend the coverage ending date for.
    

    > [!TIP]
    > <P>To open a filter at the top of each column, press Ctrl+G. For more information, see <A href="advanced-filtering-and-query-options.md">Advanced filtering and query options</A>.</P>



6.  Click **Extend**.
    
    The expiration date of the benefit and the coverage ending date for all selected workers are changed to the new benefit expiration date.

7.  When the process is complete, review the **Mass benefit expiration results** form to verify that all changes have been made. The results can be exported to Excel for future reference.

## Change the coverage ending date for multiple workers at the same time without changing the benefit expiration date

You can change the date when benefit coverage ends for selected workers without changing the expiration date of the benefit.

1.  Click **Human resources** \> **Common** \> **Benefits** \> **Benefits**.

2.  Select a benefit, and then click **Mass benefit expiration**.

3.  In the **Update option** field, select one of the following options:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Update option</strong></p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Expire selected worker enrollments</strong></p></td>
    <td><p>Change the coverage ending date to an earlier date for selected workers.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Extend selected worker enrollments</strong></p></td>
    <td><p>Change the coverage ending date to a later date for selected workers.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the **New coverage end date** field, enter the date when coverage in the benefit will end for the selected workers.

5.  Select the workers to change the coverage ending date for.
    

    > [!TIP]
    > <P>To open a filter at the top of each column, press Ctrl+G. For more information, see <A href="advanced-filtering-and-query-options.md">Advanced filtering and query options</A>.</P>



6.  If you selected **Expire selected worker enrollments**, click **Expire**.
    
    –or–
    
    If you selected **Extend selected worker enrollments**, click **Extend**.
    
    The coverage ending date for the selected workers is changed to the new coverage ending date.

7.  When the process is complete, review the **Mass benefit expiration results** form to verify that all changes have been made. The results can be exported to Excel for future reference or analysis.

## Change the coverage ending date for an individual worker

Use the **Maintain versions** form to change the ending date of a benefit for an individual worker.

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, and then click **Personal information**.

3.  Click **Benefits**.

4.  Select the benefit from the list of enrolled benefits, and then click **Maintain versions**.

5.  In versions prior to Microsoft Dynamics AX 2012 R2, in the **Enrollment end** field, enter the last date when the benefit is available to the worker.
    
    –or–
    
    In Microsoft Dynamics AX 2012 R2 or AX 2012 R3, in the **Coverage end date** field, enter the last date when the benefit is available to the worker.

6.  Close the form.

## Related tasks

[Enroll and remove benefits for workers](enroll-and-remove-benefits-for-workers.md)

[Enroll multiple workers in a benefit at the same time](enroll-multiple-workers-in-a-benefit-at-the-same-time.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To maintain benefit expiration dates, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p><strong>Enable benefits process</strong></p></li>
</ul>
<p>This duty includes the required privileges, <strong>Expire benefits and worker enrollments</strong> and <strong>Maintain the expiration date of benefits and worker enrollments</strong>.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

