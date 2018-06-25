---
title: (RUS) Set up calculation parameters for employee income tax
TOCTitle: (RUS) Set up calculation parameters for employee income tax
ms:assetid: ce114798-8da2-489e-968a-b0506461c744
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn781409(v=AX.60)
ms:contentKeyID: 62807374
ms.date: 08/19/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RpayTaxParameters
- Forms.RPayTaxTable
- MsDynAx060.Forms.RpayTaxParameters
- MsDynAx060.Forms.RPayTaxTable
- Forms.RPayTaxCountry
- MsDynAx060.Forms.RPayTaxCountry
---

# (RUS) Set up calculation parameters for employee income tax [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up income tax calculation parameters for employees who are residents, non-residents, or highly-paid non-residents. You can set up income tax exemptions for dependents and off-budget funds.

At the end of the fiscal year, the employee, who is the taxpayer, submits tax declarations to claim tax deductions. The legal entity, acting as a tax agent, pays tax to the tax authorities for employees. The legal entity calculates the tax amount for the employee, withholds the calculated amount from the employee salary, and pays the tax amount to the tax authority.

If the legal entity has multiple branches in different regions of the country, the legal entity employs tax agents to pay the tax amounts to regional tax authorities for employees who work in these branches. The regional tax authority is allocated depending on the branch location.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Enter tax registration identification numbers for a legal entity, a branch, and an employee. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Set up tax rate values and status codes for employees who are residents and highly paid non-residents. For more information, see “Set up rates and dependencies for payroll calculation” in <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
<li><p>Set up and assign income codes for pay types to mark them as taxable.</p></li>
<li><p>Set up deductions, discounts, and relief codes. For more information, see “Set up a tax deduction code for income tax calculation” in <a href="rus-set-up-taxes-and-funds-for-the-payroll-process.md">(RUS) Set up taxes and funds for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Assign a region and tax authority to an employee

You can assign regions and a tax authority to an employee by selecting a payroll group for regions that have particular NDFL rates.

To assign a region and tax authority to an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Groups for countries having particular NDFL rates for RF**.

2.  In the **Country/region** field, select the country/region.

3.  In the **Group** field, select the payroll group.

4.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee record, and then click **Edit**.

5.  On the **Profile** tab, on the **Personnel data** FastTab, in the **Country/region** field, select the region.

6.  On the **Tax** FastTab, in the **STI code** field, enter the code of the tax authority where the employee is registered as a taxpayer.

## 2\. Set up the tax residential status of an employee for NDFL calculation

Use the **Tax calculation settings** form to determine the tax residential status of an employee automatically or manually. You can change the residential status of an employee to non-resident status or highly paid non-resident status.

To determine the tax residential status automatically, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee record, and then click **Edit**.

2.  On the **Tax** tab, click **Periods of stay of employee in RF**.

3.  In the **Start date** and **End date** fields, select the starting date and ending date of the employee’s stay in the Russian Federation. The residential status of the employee is automatically calculated when you run the tax calculation for an employee in the Russian federation.

To determine the residential status manually, follow these steps:

1.  In the **Periods of stay of employee in RF** form, clear all the records with non-empty **Start date** and **End date** fields. Close the form.

2.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Tax calculation settings**.

3.  In the **Non-residents** field group, select the rate codes for the non-resident and highly paid non-resident status.

To modify the tax status of the employee from resident to non-resident, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee whose tax resident status is **Resident**, and then click **Edit**.

2.  On the **Action Pane**, in the **Rates** group, click **Employee** to open the **Set up rate values** form.

3.  Select a non-resident rate attribute. Click **New**, and then select an employee.

4.  In the **Date** and **Value** fields, enter the date, and then select **Yes** to define the selected resident employee as a non-resident.
    

    > [!NOTE]
    > <P>You can also perform similar changes to the rate attribute of a highly paid non-resident employee.</P>



5.  Close the form. On the **Action Pane**, in the **Payroll** group, click **Payments and deductions**.

6.  In the **Payments and deductions registration** form, click **Calculation** to recalculate the payroll transaction. You can see that the tax percentage value is increased for non-resident status.

7.  Close the form. On the **Tax** tab, click **Income tax**. In the **Income tax** form, you can see that the employee’s tax status is updated to **Non-resident** and the rate is updated to the tax percentage for non-residents.

## 3\. If required: Update income tax information of an employee from a previous employer

Use the **Employees** form to update the income tax information of an employee from a previous employer, and to calculate the employee’s income tax rate accordingly.

To update the income tax information of an employee from a previous employer, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee whose tax resident status is **Resident**, and then click **Edit**.

2.  On the **Payroll** tab, click **Payments and deductions** to verify the salary amount and run the calculation of income tax for the selected resident employee.

3.  On the **Tax** tab, click **Income tax** to verify the personal income tax percentage at which the income tax is calculated.

4.  Click **Form 2 - NDFL** to print the Form 2 - NDFL report that the company issues to the employee when the employee resigns. This form is provided to the new employer or another authority by the employee. The new employer uses this as an opening balance for tax calculation for that fiscal year.

5.  Click **OK** to close the form. Click **New**, and then in the **Income group code** field, select the income group code.

6.  In the **Calculation period** field, specify the year and month of the current calculation period.

7.  In the **Corrected period** field, specify the year and month of the original transaction period.

8.  Select the **Source** check box to indicate that the income or deductions for the employee are received from previous or other workplaces.

9.  On the **Income/deduction numbers** tab, enter the amount for which income code or tax deduction code is assigned.

## 4\. If required: Apply income tax exemptions for dependents

You can specify an employee’s dependents to benefit dependent related deductions as tax exemptions. Add the employee with information about the dependents in the **Payroll groups** form. The employee can benefit the tax exemptions for dependents, since the dependent related deductions are applicable only for the income of residents.

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee from the worker list.
    

    > [!NOTE]
    > <P>Make sure that the selected employee is a resident. If you selected a non-resident employee, select <STRONG>No</STRONG> in the <STRONG>Value</STRONG> field in the <STRONG>Set up rate values</STRONG> form.</P>



2.  On the **Resume** tab, click **Relatives**, and then specify the name, relationship, and date of birth of the dependent.

3.  In the **Birth time** field, enter the time of birth of the child. The birth time field is used to distinguish twins.

4.  In the **Adoption date** field, enter the date of adoption of the child for the deduction calculation. The adoption date should be greater than the birth date.

5.  In the **Apply deduction** field, select the rate code of the dependent for tax deduction. This field is available if you select **Son** or **Daughter** in the **Relationship** field.

6.  In the **Disability status** field, select the rate code to specify that the child has a disability. This status is used to increase the deduction amount for a child with a disability.

7.  In the **Deduction type code** field, select the rate code to specify the deduction type to be applied to the employee, based on the government rules. In the **Rates** form, configure the rate value type based on the elements for tax calculations.

8.  In the **Full-time education status** field, select the rate code to specify if the child has enrolled for full-time education.
    

    > [!NOTE]
    > <P>If the full-time education status is <STRONG>Yes</STRONG>, the employee is given an income tax deduction for a longer time according to the government rules.</P>



9.  In the **Deduction termination date** field, select the date when the tax deduction stops.

10. On the **Employees** list page, select a worker record, and then click **Employee** to open the **Set up rate values** form.

11. Select the resident rate attribute. In the **Date** and **Element** fields, update the values to calculate tax exemptions for a relative. Close the form.

12. Click **Payments and deductions**. In the **Payments and deductions registration** form, click **Calculation** to recalculate the payroll transaction. Make sure that the taxable revenue is sufficient to apply this deduction. You can see that the tax value is reduced.

13. On the **Tax** tab, click **Income tax**. In the **Income tax** form, you can see that the employee’s **Tax status** is updated to **Resident**. On the **Income/deduction numbers** tab, you can view the tax deduction amount.

## 5\. Set up off-budget funds

In addition to personal income taxes, you can calculate off-budget funds for employees. The legal entity transfers amounts as off-budget funds for the employee to cover employee pensions, medical coverage, social coverage, and insurance for any adverse working conditions.

To set up off-budget funds, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee, and then click **Edit**.

2.  In the **Worker** form, in the left pane, click **Profile**.

3.  In the **Profile** area, on the **Pension fund** FastTab, in the **Category of the insured person** field, select the category of the insured person.

4.  In the **Pension assignment date** field, select the retirement date of the retired employee.

5.  In the **Address** field, enter the address of the employee.
    

    > [!NOTE]
    > <P>This is the address that is used in the pension fund. The company sends the pension amount to this address after the retirement of the employee.</P>



6.  On the **Tax** tab, click **Payments to off-budget funds** to calculate the payments to the off-budget funds after the configuration of the contributions to the social funds in the **Off-budget funds** form. For more information, see "Set up off-budget and labor remuneration funds" in [(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md) and "Calculate taxes and funds" in [(RUS) Generate pay statements](rus-generate-pay-statements.md).

7.  Optional: On the **Base to compute allowances** tab, you can set up information about the prior earnings of the employee to calculate social allowances. Follow these steps:
    
    1.  Click **New**, and then in the **Amount** field, enter the amount that the employee earned in the previous year.
    
    2.  In the **Vendor account** field, select the previous company. For more information, see (RUS) Register sick lists manually and calculate compensation.

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following role:</p>
<ul>
<li><p>Payroll assistant</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To manage the workforce process, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privileges</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain RF residence periods for taxation purposes</strong></p></td>
<td><p>RPayResidenceTaxMaintain</p></td>
<td><p>Set up income tax attributes</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

