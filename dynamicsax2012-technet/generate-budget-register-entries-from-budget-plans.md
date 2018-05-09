---
title: Generate budget register entries from budget plans
TOCTitle: Generate budget register entries from budget plans
ms:assetid: 0a60643e-df9a-4126-a7e1-4c900b574aac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677321(v=AX.60)
ms:contentKeyID: 49384094
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Generate budget register entries from budget plans 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This procedure explains how to generate draft budget register entries from a budget plan and scenario. The financial dimension values on the budget plan lines must include at least the same segments as the segments that are enabled for Budgeting and budget control.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to create, maintain, deploy, and view financial reports that include budget planning data. Management Reporter lets you design financial reports based on ledger accounts and financial dimensions, drill down to transaction-level detail, and use web-based report viewing. For more information about how to print financial reports by using Management Reporter, see <A href="http://go.microsoft.com/fwlink/?linkid=324762">Management Reporter for Microsoft Dynamics ERP</A>.</P>
> <P>You can use Management Reporter to report on budget planning data only if you have rollup 4 or later for Management Reporter 2012 installed.</P>



## Example

The budget class for all budget plan lines is **Expense**. The following financial dimensions are used:

  - OU\_2310 (Department)

  - OU\_3566 (Cost center)

  - 600150 (Main account)

Main account is the only financial dimension that is enabled for Budgeting.

The following table shows two budget plan lines and the budget register entry lines, called budget account entries, that are generated when the budget plan lines are not aggregated and when they are aggregated.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Date
  </p> </th>
    <th> <p>
   
	 Financial dimensions
  </p> </th>
    <th> <p>
   
	 Amount
  </p> </th>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Budget plan lines that are used to generate the budget account entries</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 07/10/2013
  </p> </td>
    <td> <p>
   
	 600150-OU_2310-OU_3566 
  </p> </td>
    <td> <p>
   
	 100
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 07/10/2013
  </p> </td>
    <td> <p>
   
	 600150-OU_2310
  </p> </td>
    <td> <p>
   
	 200
  </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Budget account entries that are generated when the budget plan lines are not aggregated</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 07/10/2013
  </p> </td>
    <td> <p>
   
	 600150
  </p> </td>
    <td> <p>
   
	 100
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 07/10/2013
  </p> </td>
    <td> <p>
   
	 600150
  </p> </td>
    <td> <p>
   
	 200
  </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p> <strong xmlns="http://www.w3.org/1999/xhtml">Budget account entry that is generated when the budget plan lines are aggregated</strong> </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 07/10/2013
  </p> </td>
    <td> <p>
   
	 600150
  </p> </td>
    <td> <p>
   
	 300
  </p> </td>
  </tr>
</table>


## Generate budget register entries from budget plans

1.  Click **Budgeting** \> **Periodic** \> **Generate budget register entry**.

2.  On the **Source** FastTab, enter or select the budget planning process, responsibility center, document number, and budget plan scenario.
    
    To include advanced criteria such as source information, click **Select** to open an inquiry form. After you close the inquiry form, the financial dimensions that you selected in the inquiry form are displayed in the **Selection criteria** field group in the **Generate budget register entry** form.

3.  On the **Target** FastTab, enter or select the default date, budget model, and budget code for the budget register entry.

4.  Select the **Aggregate lines** check box to aggregate the budget plan lines by the dimensions that are enabled for Budgeting. When this check box is selected, lines that have the same effective date, ledger account, and budget class will be aggregated and totaled.

5.  Change the multiplication factor and rounding format, if you have to.

6.  To create budget register entries by using a batch process, complete the fields on the **Batch** FastTab.
    
    For information about the batch options in this form, and about how to submit a batch processing job, see [Batch tasks (form)](https://technet.microsoft.com/en-us/library/hh209494\(v=ax.60\)) and [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

7.  Click **Generate**.


> [!NOTE]
> <P>If the <STRONG>Public Sector</STRONG> configuration key is selected, you can generate budget register entries for a preliminary budget and for apportionments. For preliminary budget amounts, the budget plan does not have to be approved. For apportionments, original budget amounts must be generated before the apportioned amounts.</P>



## See also

[Generate budget register entry (form)](https://technet.microsoft.com/en-us/library/jj710365\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

