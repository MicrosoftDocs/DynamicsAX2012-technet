---
title: (RUS) Settle tax liabilities
TOCTitle: (RUS) Settle tax liabilities
ms:assetid: d7c6cf1a-f3df-44e8-93e1-66e03a47e458
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn771649(v=AX.60)
ms:contentKeyID: 62553201
ms.date: 07/11/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RPayPaySheetSum
- Forms.RpayTaxListTable
- Forms.RPayTaxOpenTrans
- Forms.RPayTaxOpenTransReverse
- Forms.RPayTaxPeriodicSettlement
- Forms.RPayTaxSettlement
- liability
- tax liability
- settle tax liabilities
- reverse settlement
audience: Application User
ms.search.region: Russia
---

# (RUS) Settle tax liabilities 


Tax liability is the unpaid amount of tax the employees owe to the tax authority. This tax is paid by the legal entity on behalf of the employee. Use the **NDFL payment settlement** form to filter tax payments and tax liabilities, and to settle the tax liabilities. Tax liabilities can be settled for different kinds of pay-sheets using the **Deducted NDFL on interim pay-sheets** form. You can also reverse settlements that are made for tax liabilities.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<li><p>Create a sales tax authority in the <strong>Sales tax authorities</strong> form. For more information, see <a href="set-up-sales-tax-authorities.md">Set up sales tax authorities</a>.</p></li>
<li><p>Set up a Russian Classification of Objects and Administrative Division (RCOAD) code for a sales tax authority in the <strong>RCOAD codes</strong> form. For more information, see <a href="rus-set-up-an-rcoad-code-for-a-sales-tax-authority.md">(RUS) Set up an RCOAD code for a sales tax authority</a>.</p></li>
<li><p>Create a sales tax group to group the sales tax codes. For more information, see <a href="rus-set-up-sales-tax-groups-for-tax-calculation.md">(RUS) Set up sales tax groups for tax calculation</a>.</p></li>
<li><p>Set up sales tax codes for the legal entity and its branches, if any, in the <strong>Sales tax codes</strong> form. Include the sales tax codes in the created sales tax group. Link the sales tax code to the created tax authority. For more information, see <a href="rus-set-up-sales-tax-codes-for-tax-calculation.md">(RUS) Set up sales tax codes for tax calculation</a>.</p></li>
<li><p>Assign the sales tax codes to an income group that is used to calculate the income tax of an employee. Configure the tax settlement parameters in the <strong>Tax calculation settings</strong> form. For more information, see <a href="rus-set-up-taxes-and-funds-for-the-payroll-process.md">(RUS) Set up taxes and funds for the payroll process</a>.</p></li>
<li><p>Set up a branch to identify groups of departments as individual taxpayers. Make sure that the tax registration number and type for the vendor and the branch of the legal entity is the same. Create departments and assign them to a branch or to the legal entity. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Set up payments, journals, and deductions for the payroll process. For more information, see <a href="rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md">(RUS) Set up payments, journals, and deductions for the payroll process</a>.</p></li>
<li><p>Create payroll journals, calculate average earnings, calculate salaries, calculate funds, and create a salary journal. For more information, see <a href="rus-generate-pay-statements.md">(RUS) Generate pay statements</a>.</p></li>
<li><p>Verify payroll calculation results, create and pay salary pay sheets, close the current payroll period, and generate a payment for the tax authority in the <strong>Payment journals</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa599011(v=ax.60)">Journal voucher - Vendor payment journal (form)</a>.</p></li>
<li><p>Verify that the calculation period for which the tax settlement is to be done is a closed payroll period in the <strong>Payroll parameters</strong> form. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Settle tax liabilities

Before you can settle tax liabilities, you must specify criteria in the **Open transaction update** form to identify the tax payments and liabilities for settlement. When these criteria are applied, an entry that consists of the list of unsettled tax liabilities is displayed and is ready for settlement in the **NDFL payment settlement** form. To settle liabilities, use one of the following methods:

  - Automatic: Use the **Periodic settlement** form to automatically settle the tax liabilities.

  - Manual: Use the **Settle open transactions** form to mark and settle the tax liabilities.


> [!NOTE]
> <P>The settled liabilities are listed in the <STRONG>Closed transaction editing</STRONG> form.</P>



You can also settle tax liabilities for interim pay-sheets. To view the details of the tax liabilities that are to be paid for interim pay-sheets, use the **Deducted NDFL on interim pay-sheets** form (Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Deducted NDFL on interim pay-sheets**.). For more information on how to set up the interim payrolls, see “Create an interim pay-sheet” in the (RUS) Issue payments to workers topic.

To identify the tax payments and tax liabilities, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **NDFL payment settlement**. Click **Settlement** \> **Open transaction update**.

2.  In the **Payments** field group, in the **Date interval code** field, select a code from the date interval directory. The date interval code indicates the interval for which the tax payment is made to the authority. The starting and ending dates of the date interval are updated automatically.
    
    –or–
    
    Enter the starting and ending dates of the date intervals if the date interval code has not been selected.

3.  In the **Tax authority** field, select a tax authority to which the payment is made. If the **Tax authority** field is blank, payments that are made to all tax authorities are filtered.

4.  Optional: In the **Shared** field group, select a code to filter the tax payments and liabilities that pertain to the budget revenue code.

5.  In the **Liabilities** field group, in the **Taxation period** field, enter the fiscal year for which the taxes are paid from the employee salary, and for which the liability is settled.

6.  In the **Selection type** field, select a criterion to filter the liabilities.
    
    Select from the following options:
    
      - **All** — Filter employee liabilities for all branches.
    
      - **Only main company** — Filter employee liabilities for the head office.
    
      - **By query** — Filter liabilities for a particular branch. Click **Select** to open the **Inquiry** form, and specify the criteria for the **Separate division ID** field.

7.  Click **OK**. A transaction line to be settled is created in the **NDFL payment settlement** form.

To settle the tax liabilities automatically, follow these steps:

1.  In the **NDFL payment settlement** form, click **Settlement** \> **Periodic settlement**.

2.  In the **Considered date** field, select a date until which the taxes are calculated for the fiscal year entered in the **Taxation period** field.

3.  Click **OK** to settle the liabilities automatically. You can verify whether the transactions are settled in the **Closed transaction editing** form according to the filter criteria.

To settle the tax liabilities manually, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **NDFL payment settlement**. Click **Functions** \> **Settle open transactions**.

2.  Select **Mark** \> **Mark all** to select all of the transactions, or select the **Mark** check box for a specific transaction.

3.  Click **Update** to settle the selected tax liabilities. The **Amount settled** field displays the settled liability or payment amount. Click **Close**.
    

    > [!NOTE]
    > <P>You can verify whether transactions are settled in the <STRONG>Closed transaction editing</STRONG> form according to the filter criteria.</P>



4.  Optional: Click **Delete** to delete the settlement transaction line. You can delete the transaction line only after you delete the open transactions in the **Settle open transactions** form.

## Optional: Reverse the settlement of a tax liability

You can reverse the settlement of a tax liability when the legal entity has entered incorrect selection criteria in the **Periodic settlement** or **Open transaction update** forms.

To reverse the settlement of a tax liability, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **NDFL payment settlement**. Click **Functions** \>**Closed transaction editing**.

2.  Select **Mark** \> **Mark all** to select all of the transactions, or select the **Mark** check box for a specific transaction.

3.  Click **Reverse** to reverse the selected tax liabilities. Click **Close**.

4.  To verify the reversed tax liabilities, click **Functions** \> **Settle open transactions**. The **Amount settled** field displays zero, which indicates that the transactions are reversed.

## Generate and print the payment settlement reports

You can generate reports that contain details about settled tax liabilities. The reports can be generated either in printable or electronic formats and transferred to the tax authority.


> [!NOTE]
> <P>Your tax authority might require you to generate the settled payments and their tax details electronically when the number of employees in your legal entity exceeds a specific number.</P>



To generate the settled payments and their tax details, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Income data register**.

2.  Click **New** to create a new record.

3.  Specify the details for the period for which the settlement is done.

4.  Click **Create register** and specify the selection criteria to create an income data register that contains tax details about employees.

5.  Click **Create a file** to generate an XML file that contains the tax details for the employees from the created income data register.
    
    –or–
    
    Click **Print** \> **Natural persons' income data register** to print a summary of the tax details and yearly income statements for all employees of the selected income data register.
    

    > [!NOTE]
    > <P>Use the <STRONG>Form 1 - NDFL</STRONG> and <STRONG>Form 2 - NDFL</STRONG> to generate and print reports that contain details about the personal income tax that is levied for an employee. For more information, see <A href="rus-taxation-contributions-and-compensation-reports.md">(RUS) Taxation, contributions, and compensation reports</A>.</P>



## Related tasks

(RUS) Configure standard deductions calculation

[(RUS) Payroll accounting reports](rus-payroll-accounting-reports.md)

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>CIS Payroll</strong> and <strong>CIS Staff administration</strong> configuration keys.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following role:</p>
<ul>
<li><p><strong>Payroll administrator</strong></p></li>
</ul>
<p>To settle the tax liabilities, you must be a member of a security role that includes the following duty:</p>
<ul>
<li><p><strong>Enable tax settlement</strong>(RPayTaxSettlementEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To settle the tax liabilities, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Maintain tax settlement</strong></p></td>
<td><p>RPayTaxSettlementMaintain</p></td>
<td><p>Settle tax liabilities.</p></td>
</tr>
<tr class="even">
<td><p><strong>View tax settlement</strong></p></td>
<td><p>RPayTaxSettlementView</p></td>
<td><p>Generate and print the payment settlement reports.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


