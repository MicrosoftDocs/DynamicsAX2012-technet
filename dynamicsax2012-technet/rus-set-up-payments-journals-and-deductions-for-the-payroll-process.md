---
title: (RUS) Set up payments, journals, and deductions for the payroll process
TOCTitle: (RUS) Set up payments, journals, and deductions for the payroll process
ms:assetid: 3fd4cc75-bbc8-4a26-83c3-051017598c77
ms:mtpsurl: https://technet.microsoft.com/library/Dn435984(v=AX.60)
ms:contentKeyID: 56732185
author: Khairunj
ms.date: 07/04/2014
mtps_version: v=AX.60
f1_keywords:
- payroll
- salary
- payments
- parameter
- parameters
- payment
- pay
- journal names
- journal
- journals
- deduction
- deductions
- payroll journal
- Forms.RPayJournalSetup
- Forms.RPayPaymentParameters
- Forms.RPayStandardDeductionParameters
- Forms.RPayStandardDeductionTable
- journal name
- payroll journals
- salaries
- standard deduction
- standard deductions
- MsDynAx060.Forms.RPayJournalSetup
- MsDynAx060.Forms.RPayPaymentParameters
- MsDynAx060.Forms.RPayStandardDeductionTable
- MsDynAx060.Forms.RPayStandardDeductionParameters
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up payments, journals, and deductions for the payroll process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up parameters for salary payments and standard deductions. The topic also explains how to set up payment journal names.

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
<li><p>Set up bank accounts. For more information, see <a href="rus-set-up-bank-accounts.md">(RUS) Set up bank accounts</a>.</p></li>
<li><p>Set up cash accounts. For more information, see <a href="rus-set-up-a-cash-account.md">(RUS) Set up a cash account</a>.</p></li>
<li><p>Create tax registration numbers, social insurance information, and the organizational structure for a legal entity. Create departments in an organization, assign each department to a branch, and reserve a position for a department. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Set up parameters for payroll calculations, payroll groups, rates and dependencies for payroll calculations, payroll posting profiles, pay types, and funds. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up parameters for salary payments

Use the **Salary payment setup** form to set up parameters for salary payments and payments that are made in the middle of a period for employees. You can set up parameters for cash payments, bank payments, and deposits.

To set up parameters for salary payments, follow these steps:

1.  Click **Payroll (Russia)** \> **Salary payment** \> **Setup** \> **Setup**.

2.  In the **Petty cash** area, in the **Name** field, select the name of the journal that is used to register cash payment slips.

3.  In the **Cash** field, select a cash account to make payments to.

4.  Select the **Automatic** check box to post the cash transaction to the general ledger automatically.

5.  In the **Default financial dimensions** field group, set up the financial dimension codes for cash payments.

6.  Click **Bank**, and then in the **Bank** area, in the **Name** field, select the name of the bank transaction journal. You can select a journal of type **Daily** in this field.

7.  Select the **Automatic** check box to post the bank transaction to the general ledger automatically.

8.  In the **Account type** and **Account** fields, select the account type and account code for the bank payments.

9.  In the **Default financial dimensions** field group, set up the financial dimension codes for the bank payments.

10. Click **Deposit**, and then in the **Deposit** area, in the **Corr. account for deposit** field group, in the **Account type** field, the account type is updated to **Ledger**. An account of type **Ledger** is used to record the liabilities of a legal entity to employees. In the **Account** field, select a ledger account code for the deposits.

11. In the **Pay type** field, select the pay type for the accounting of deposited amounts when a deposit that is not received by an employee is closed using payroll.

12. In the **Against profit** field group, in the **Account type** field, the account type is updated to **Ledger**. An account of type **Ledger** is used when a deposit that is not received by an employee is written off against profit on maturity of the deposited amount. In the **Account** field, select a ledger account code.

## 2\. Set up payroll journal names

Use the **Setup payroll journals** form to set up journal names for payroll. Journal names are used to categorize the registered vouchers. For example, you can set up a journal name to accrue bonuses by March 8 of each year, or to accrue the annual bonus for the top managers of a legal entity.

To set up payroll journal names, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Payroll journal** \> **Journal names**.

2.  In the **Name** field, enter a payroll journal name.

3.  In the **Description** field, enter a description for the payroll journal.

4.  Select the **Delete lines after posting** check box to delete the journal lines after you post the journal.

5.  Select the **Use rate value per employee** check box to use the date effective rate values that you specified for each employee or group in the **Value** field on the **Overview** tab in the **Set up rate values** form for each journal line. If you clear this check box, the default rate value that you specified in the **Value** field on the **Value** tab in the **Rates** form is used for all of the employees or groups in all of the journal lines.

6.  In the **Private for user group** field, select a user group to provide private access to the journal name.

## 3\. Set up standard deduction parameters

Use the **Standard deduction calculation settings** form to set up parameters for standard deductions, and use the **Standard deductions** form to set up codes that are used for standard deductions. Standard deductions refer to all deductions from the paycheck of an employee, excluding individual income tax. Deductions from the wages and other incomes of an employee are calculated based on the amount that is to be paid after the individual income tax is deducted.

To set up standard deduction parameters that are used as default values for the attributes that are used to register employees’ liabilities, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Standard deductions** \> **Setup** \> **General settings**.

2.  In the **Amount to pay** field, select the basis to calculate the amount of pay. For more information about the basis of calculation and how to set up the basis of calculation, see “7. Set up off-budget and labor remuneration funds” in [(RUS) Set up parameters for the payroll process](rus-set-up-parameters-for-the-payroll-process.md).

3.  In the **Maximum deduction percentage** field, select the rate that contains the percentage that is used to calculate the maximum amount of deductions from the employee’s pay that you specify in the **Amount to pay** field.

4.  In the **Sequence** field, select the sequence to calculate the deduction amount for alimony postage charges. Close the form.

5.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Standard deductions** \> **Setup** \> **Deduction codes**.

6.  Click **New** or press CTRL+N to create a deduction code, and then specify the type, code, and name of the deduction.
    
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
    <td><p><strong>Deduction type</strong></p></td>
    <td><p>Select the type of deduction that the code is created for.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Alimony</strong> – The deduction code is for alimony payments.</p></li>
    <li><p><strong>Borrowing</strong> – The deduction code is for borrowing deductions.</p></li>
    <li><p><strong>Other deductions</strong> – The deduction code is for other deductions.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Deduction code</strong></p></td>
    <td><p>Enter an identification code for the deduction.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the deduction.</p></td>
    </tr>
    </tbody>
    </table>


7.  On the **General** tab, specify the sequence, amount control, and storno adjustment details for the deduction code.
    
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
    <td><p><strong>Sequence number</strong></p></td>
    <td><p>The number of the deduction code.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Sequence</strong></p></td>
    <td><p>Select the identification code for the sequence to be used by default when you calculate the selected deduction type.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Amount control</strong></p></td>
    <td><p>Select this check box to validate the deduction amount.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you select this check box, the calculated deduction amount for the selected deduction code for an employee cannot be greater than the amount that is calculated using the following formula:</P>
    > <P>The standard deduction amount * The maximum deduction percentage - Other calculated deductions</P>
    > <UL>
    > <LI>
    > <P>The standard deduction amount indicates the amount that is calculated using the basis for the calculation that you select in the <STRONG>Amount to pay</STRONG> field in the <STRONG>Standard deduction calculation settings</STRONG> form.</P>
    > <LI>
    > <P>Maximum deduction percentage indicates the deduction percentage that you specify in the <STRONG>Maximum deduction percentage</STRONG> field in the <STRONG>Standard deduction calculation settings</STRONG> form.</P>
    > <LI>
    > <P>Other calculated deductions indicates any other previously calculated deductions.</P></LI></UL>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Financial interest storno adjustment</strong></p></td>
    <td><p>Select this check box to adjust storno in the loan-related financial interest along with this deduction provision.</p></td>
    </tr>
    </tbody>
    </table>


8.  On the **Calculation order** tab, you can view the details of created standard deduction codes in the order in which they were created in the form. To change the order of a deduction code, select a deduction code, and then click **Up** or **Down** to arrange the deduction codes in the required order.
    

    > [!NOTE]
    > <P>This automatically updates the value of the deduction code sequence number in the <STRONG>Sequence</STRONG> field on the <STRONG>General</STRONG> tab.</P>



## Next step

You have finished setting up payments, journals, and deductions for the payroll process. Continue to set up additional parameters for the payroll process. For more information, see the following topics:

  - [(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md)

  - [(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

  - [(RUS) Set up taxes and funds for the payroll process](rus-set-up-taxes-and-funds-for-the-payroll-process.md)

After you complete all of the setup tasks for the payroll process, continue to calculate payments for workers. For more information, see the following topics:

  - [(RUS) Create and post a vacation resolution](rus-create-and-post-a-vacation-resolution.md)

  - [(RUS) Create and post a business trip resolution](rus-create-and-post-a-business-trip-resolution.md)

  - (RUS) Register vacations, business trips, and calculate compensation

  - [(RUS) Create and post an incentive resolution](rus-create-and-post-an-incentive-resolution.md)

  - (RUS) Configure standard deductions calculation

  - [(RUS) Generate pay statements](rus-generate-pay-statements.md)

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
<td><p>To set up payments, journals, and deductions for the payroll process, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Enable compensation process</strong> (HcmJobTypeMaintain)</p></li>
<li><p><strong>Enable payroll process</strong> (HcmPayrollProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into earning entry</strong> (PayrollEarningStatementGenerationInquire)</p></li>
<li><p><strong>Inquire into payments to workers</strong> (RPayWorkerInquire)</p></li>
<li><p><strong>Inquire into payroll payments</strong> (PayrollPayStatementGenerationInquire)</p></li>
<li><p><strong>Inquire into payroll process</strong> (HcmPayrollProcessInquire)</p></li>
<li><p><strong>Issue payments to workers</strong> (PayrollIssueWorkerPaymentsMaintain)</p></li>
<li><p><strong>Set up time management master data</strong> (RPaySetupTimeMasterData)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up payments, journals, and deductions for the payroll process, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Maintain pay sheets (payroll)</strong> (RPayPayrollPaySheetsMaintain)</p></li>
<li><p><strong>Maintain payroll earnings</strong> (RPayAvgPayrollMaintain)</p></li>
<li><p><strong>Maintain salary deduction types</strong> (HcmPayrollDeductionTypeMaintain)</p></li>
<li><p><strong>View and update vacation pay-sheets</strong> (RPayPaySheetView)</p></li>
<li><p><strong>View payroll earnings</strong> (PayrollEarningsView)</p></li>
<li><p><strong>View salary deduction types</strong> (HcmPayrollDeductionTypeView)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


