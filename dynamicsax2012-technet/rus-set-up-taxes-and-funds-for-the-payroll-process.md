---
title: (RUS) Set up taxes and funds for the payroll process
TOCTitle: (RUS) Set up taxes and funds for the payroll process
ms:assetid: 2eb6cb1d-69ae-4eb7-bee3-d48d778a5b09
ms:mtpsurl: https://technet.microsoft.com/library/Dn435983(v=AX.60)
ms:contentKeyID: 56732184
author: tonyafehr
ms.date: 07/04/2014
mtps_version: v=AX.60
f1_keywords:
- retention
- payroll
- discounts
- funds
- fund
- discount
- tax
- deduction
- deductions
- income tax
- taxes
- tax base
- income code
- Forms.RpayFundDeductionTable
- Forms.RpayTaxDeductionTable
- Forms.RPayTaxFund
- Forms.RPayTaxIncomeCode
- Forms.RpayTaxParameters
- Forms.RPayTaxTable
- income group
- income taxes
- individual contribution
- individual contributions
- off-budget fund
- off-budget funds
- relief
- taxable base
- MsDynAx060.Forms.RpayFundDeductionTable
- MsDynAx060.Forms.RpayTaxDeductionTable
- MsDynAx060.Forms.RPayTaxFund
- MsDynAx060.Forms.RpayTaxParameters
- MsDynAx060.Forms.RPayTaxTable
- MsDynAx060.Forms.RPayTaxIncomeCode
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up taxes and funds for the payroll process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can configure Microsoft Dynamics AX to allow a legal entity to act as a tax agent and an insurance agent for employees.

  - Set up a deduction, discount, and relief code to calculate tax deductions to reduce the taxable base.

  - Set up an income group to be used to calculate income taxes for a combination of a particular tax residence status and income type.

  - Set up an income code to be used to calculate income taxes and display earnings based on different types of income types in tax-related statements.

  - Set up a deduction, discount, and relief code to calculate individual contribution to off-budget funds to reduce the taxable base.

  - Set up off-budget funds to be used to calculate individual contributions to off-budget funds.

  - Set up parameters for income tax and individual contribution calculations.

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
<li><p>Set up payroll calculations, payroll groups, rates and dependencies for payroll calculations, payroll posting profiles, pay types, and funds. For more information, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></li>
<li><p>Set up calculation procedures, their sequences and counters, and calculation methods to calculate the salaries for workers. For more information, see <a href="rus-set-up-calculation-procedures-for-the-payroll-process.md">(RUS) Set up calculation procedures for the payroll process</a>.</p></li>
<li><p>Set up sales tax codes. For more information, see <a href="rus-set-up-sales-tax-codes-for-tax-calculation.md">(RUS) Set up sales tax codes for tax calculation</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up a tax deduction code for income tax calculation

Use the **Deduction, discount, and relief codes** form to set up a deduction, discount, and relief code to calculate tax deductions to reduce the taxable base.

To set up a tax deduction code for income tax calculation, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Income tax** \> **Deduction, discount, and relief codes**.

2.  Click **New** or press CTRL+N to create a tax deduction code.

3.  In the **Deduction code** and **Name** fields, enter an identification code and a name for the deduction code.

4.  In the **Deduction type** field, select the deduction code type.
    
    Select from the following options:
    
      - **Standard** – The deduction code applies to incomes of any pay type.
    
      - **Others** – The deduction code applies only to incomes of the pay types that use the income code to which you assign the deduction code.
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX applies the <STRONG>Others</STRONG> deductions to calculate tax deductions to reduce the taxable base before applying the <STRONG>Standard</STRONG> deductions.</P>



5.  Select the **For relative** check box to indicate that the deduction amount applies to the income of employees who have specific relatives, such as a brother, sister, son, daughter, mother, father, wife, or husband. For more information, see “1. Create and post a payroll journal” and “4. Verify worker payments and deductions” in [(RUS) Generate pay statements](rus-generate-pay-statements.md).

6.  In the **Rate (reference)** field, select the identification code of a payroll rate for the deduction code that is used by an employee.

7.  In the **Rate (value)** field, select the identification code of a payroll rate that determines the deduction amount.

8.  In the **Sequence** field, select the identification code of a sequence in which the deduction amount is calculated in the tax calculation procedure.
    

    > [!NOTE]
    > <P>This field is available only if you specify a rate in the <STRONG>Rate (reference)</STRONG> field and leave the <STRONG>Rate (value)</STRONG> field blank.</P>



9.  In the **Period of validity** field, select the duration that the deduction is valid for.

10. Select the **Tax refund** check box to allow a tax refund related to this deduction provision retroactively if the tax was already deducted at the beginning of the year.
    

    > [!NOTE]
    > <P>You can select this check box only if you select <STRONG>Standard</STRONG> in the <STRONG>Deduction type</STRONG> field.</P>



11. Select the **Financial interest storno adjustment** check box to allow the storno adjustment of the loan-related financial interest along with this deduction provision.
    

    > [!NOTE]
    > <P>When an employee receives financial interest on borrowed amounts, the related taxes are deducted from the employee’s pay. If the employee confirms that this borrowed money is spent to purchase a house or a flat, all of the interest that is calculated is storno adjusted, and the employee gets a tax refund. For more information about borrowing deductions, see “2. Create borrowing deductions and calculate standard deductions” in (RUS) Configure standard deductions calculation.</P>



## 2\. Set up an income group for income tax calculations

Use the **Income groups for NDFL** to set up an income group that is used to calculate income taxes for a particular tax residence status and income type combination.

To set up an income group for income tax calculations, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Income tax** \> **Income groups for NDFL**.

2.  Click **New** or press CTRL+N to create an income group.

3.  In the **Income group code** and **Name** fields, enter an identification code and a name for the income group.

4.  In the **Tax status** field, select the tax status of the employees that the income group applies to.
    
    Select from the following options:
    
      - **Resident** – The tax group applies to residents.
    
      - **Non-resident** – The tax group applies to non-residents.
    
      - **High paid non-resident** – The tax group applies to highly paid non-residents.

5.  In the **System rate** field, select a rate to apply to all of the employees of the legal entity.

6.  In the **Group rate** field, select a rate to apply to all of the employees in a payroll group instead of applying the value that you specify in the **System rate** field.

7.  In the **Fund** field, select a calculation base code for the income group.
    

    > [!NOTE]
    > <P>You cannot select the same calculation base for different income groups that have the same tax residence status. This ensures that a single pay type in a calculation base appears only once in the tax base.</P>



8.  Select the **Standard deductions** check box to apply standard deductions to the income group.

9.  Select the **Other deductions** check box to apply other deductions to the income group.

10. In the **Sales tax code** field, select the sales tax code that applies to the income group.
    

    > [!NOTE]
    > <P>This sales tax code is assigned to the head office of the legal entity. The sales tax codes for each separate division are determined based on the codes that are assigned to the same sales tax group that contains the head office sales tax code.</P>



11. In the **Pay type** field, select the pay type that is used to register payroll transactions that are related to this income group for the tax that is calculated for the current fiscal year.

12. On the **General** tab, specify values in the following fields:
    
    1.  In the **Future period tax** field, select the pay type that is used to register payroll transactions that are related to this income group for the tax that is calculated for the future fiscal year.
    
    2.  In the **Last year’s debts repayment** field, select the pay type that is used to register payroll transactions that are related to this income group for the tax that is calculated for the previous fiscal year.
    
    3.  In the **Budget revenue code** field, select the classification code for budget revenue.
        

        > [!NOTE]
        > <P>You cannot select the same budget revenue code for multiple sales tax codes. This ensures that the selected budget revenue code tax payment document is unambiguously linked to a particular income group and the tax liability that is related to the document is used in the tax settlement.</P>



## 3\. Set up an income code for income tax calculations

Use the **Income codes** form to set up an income code that is used to calculate income taxes and display earnings based on different types of income in the tax statements.

To set up an income code for income tax calculations, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Income tax** \> **Income codes for NDFL**.

2.  Click **New** or press CTRL+N to create an income code.

3.  In the **Income code** and **Name** fields, enter an identification code and a name for the income code.

4.  In the **Deduction code** field, select the deduction, discount, and relief code that has a type of **Others** to apply to the income of this code.

## 4\. Set up a deduction code to calculate individual contribution to off-budget funds

Use the **Reliefs and deductions on off-budget funds** form to set up a deduction, discount, and relief code to calculate individual contribution to off-budget funds to reduce the taxable base.

To set up a deduction code for individual contribution calculation, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Off-budget funds** \> **Deduction, discount, and relief codes**.

2.  Click **New** or press CTRL+N to create a tax deduction code.

3.  In the **Deduction code** and **Name** fields, enter an identification code and a name for the deduction code.

4.  In the **Deduction type** field, select the type of the deduction code.
    
    Select from the following options:
    
      - **Fund deduction** – The deduction code is used for fund deductions only.
    
      - **Tax deduction** – The deduction code is configured by reusing the setup information for a tax deduction.
    
      - **Deductions in income types** – The deduction code applies to the earnings of specific pay types.

5.  Select the **For relative** check box to indicate that the deduction amount applies to the income of employees that have specific relatives, such as a brother, sister, son, daughter, mother, father, wife, or husband.

6.  In the **Rate (reference)** field, select the identification code of a payroll rate for the deduction code that is used by an employee.

7.  In the **Rate (value)** field, select identification code of a payroll rate that determines the deduction amount.

8.  In the **Sequence** field, select the identification code of a sequence in which the deduction amount is calculated in the tax calculation procedure.

9.  In the **Period of validity** field, select the duration that the deduction is valid for.

10. Optional: In the **Tax value** field, select the rate that is used to calculate the discount for fund contribution calculations from the value of the deductions.

11. If you select **Tax deduction** in the **Deduction type** field, then on the **Tax deduction** tab, add deduction code records to the deduction code. Select the deduction code records in the **Remaining** list, and then click **\<** to move the selected deduction code records to the **Selected** list. Alternatively, click **\<\<** to move all of the deduction code records from the **Remaining** list to the **Selected** list.

12. If you select **Deductions in income types** in the **Deduction type** field, then on the **Means of payments** tab, add means of payment records to the deduction code. Select the means of payment records in the **Remaining** list, and then click **\<** to move the selected means of payment records to the **Selected** list. Alternatively, click **\<\<** to move all of the means of payment records from the **Deductions in income types** list to the **Selected** list.

## 5\. Set up off-budget funds for individual contribution calculations

Use the **Off-budget funds and labor remuneration fund taxes** form to set up off-budget funds that are used to calculate the individual contributions to off-budget funds.

To set up off-budget funds for individual contribution calculations, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Off-budget funds** \> **Off-budget funds**.
    

    > [!NOTE]
    > <P>The funds of type <STRONG>Off-budget fund</STRONG> that you created in the <STRONG>Off-budget funds and labor remuneration fund taxes</STRONG> form are displayed in the form.</P>



2.  In the **Rate (value)** field, select the rate code to determine the rate that is used to calculate the amount that is contributed to the fund.
    

    > [!NOTE]
    > <P>If you specify a value in this field, you cannot specify a value in the <STRONG>Rate (percentage)</STRONG> field.</P>



3.  In the **Rate (reference)** field, select the rate code that is used to determine the employees for whom this fund calculation is performed.

4.  In the **Rate (percentage)** field, select the rate code to determine the amount that is contributed to the fund. If you select this option for a period, and then in a later period you change the rate and recalculate the fund, the existing line is storno adjusted and a new line that has the new rate is created for this calculation.
    

    > [!NOTE]
    > <P>If you specify a value in this field, you cannot specify a value in the <STRONG>Rate (value)</STRONG> field.</P>



5.  On the **Deductions and reliefs** tab, select the deduction code records in the **Remaining** list, and then click **\<** to move the selected deduction code records to the **Selected** list. Alternatively, click **\<\<** to move all of the deduction code records from the **Remaining** list to the **Selected** list.

6.  Click **Funds totals** to open the **Payments to off-budget funds (totals)** form, where you can view the amount, calculation base, payments to the fund, and the benefits provided for each fund line across calculation periods. Close the form.

7.  On the **Posting profile** tab, you can define the type and the code for main, offset, and deviation accounts. If required, in the **Cost accounts** field group, modify the default rules when the same account that is used for the fund base calculation is used to book the off-budget funds.

8.  On the **Dimension**, **Offset dimension**, and **Deviation dimension** tabs, configure the specific dimensions for the non-ledger accounts that you select on the **Posting profile** tab.

## 6\. Set up parameters for tax calculations

Use the **Tax calculation settings** form to set up parameters for income tax and individual contribution calculations.

To set up parameters for tax calculations, follow these steps:

1.  Click **Payroll (Russia)** \> **Settlements with tax authorities** \> **Setup** \> **Tax calculation settings**.

2.  On the **General** tab, specify the general parameters for tax calculations.
    
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
    <td><p><strong>Income tax</strong></p></td>
    <td><p>Enter the degree of precision to use to round off the tax amount.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Non-resident</strong></p></td>
    <td><p>Select the rate that is used to determine the status of an employee as a non-resident.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>High paid non-resident</strong></p></td>
    <td><p>Select the rate that is used to determine the status of an employee as a high paid non-resident.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number of days for resident</strong></p></td>
    <td><p>Select a rate that is used to determine the number of days that an employee must stay in the country to qualify as a resident.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Period for defining status</strong></p></td>
    <td><p>Select the period that is used to determine the tax resident status of an employee.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reimbursement method</strong></p></td>
    <td><p>Select the method that is used to pay the tax reimbursements.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Reckoning</strong> – The excessive tax amount that is withheld is not refunded and is used to compensate taxes from future income.</p></li>
    <li><p><strong>Tax refund via payroll pay-sheet</strong> – The tax refund is processed in payroll pay sheets.</p></li>
    <li><p><strong>Tax refund via separate pay-sheet</strong> – The tax refund is processed in separate pay sheets.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Refund by status changing</strong></p></td>
    <td><p>Indicate whether the excessive tax amount that is withheld from an employee is refunded after the tax residence status of the employee changes to <strong>Resident</strong>.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>Yes</strong> – The withheld tax amount is refunded when the status of the employee changes to <strong>Resident</strong>.</p></li>
    <li><p><strong>No</strong> – The withheld tax amount is not refunded when the status of the employee changes to <strong>Resident</strong>.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Claim for tax refund</strong></p></td>
    <td><p>Select the rate that is used to determine the availability of the employee application that requests the tax refund after the tax residence status changes.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Staying days in fiscal year</strong></p></td>
    <td><p>Select the rate that is used to calculate the number of days that an employee must stay in the country, starting on the first of January to qualify for a tax refund for the current fiscal year.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Separate divisions handling</strong></p></td>
    <td><p>Select this check box to calculate and report taxes for each branch separately.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Tax for refund</strong></p></td>
    <td><p>Select the method to determine the date to settle tax refunds.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>On charge</strong> – The tax refund is paid on the tax refund accrual date.</p></li>
    <li><p><strong>On payment</strong> – The tax refund is paid on the date when you pay the employee using a pay sheet.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Pay-sheet set-off</strong></p></td>
    <td><p>Select the method that is used for pay sheet accounting for tax refund settlements.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>All</strong> – All of the pay sheets are taken into account for the settlement.</p></li>
    <li><p><strong>Paid</strong> – Only the pay sheets that are already paid are taken into account for the settlement.</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Max number of documents per file</strong></p></td>
    <td><p>Select a rate that determines the maximum number of statements that can be included in a file.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Settled payments handling</strong></p></td>
    <td><p>Select this check box to use settled payments for income tax reporting.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum deduction percentage</strong></p></td>
    <td><p>Select a rate code that determines the maximum deduction percentage of withholding tax for employees.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Counting of all children</strong></p></td>
    <td><p>Select this check box to count all of the children of an employee regardless of whether deductions that are related to children are applied to the employee.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Property deduction</strong></p></td>
    <td><p>Select the list of deduction codes that are used as property deductions for tax reporting. Use a comma to separate multiple property deductions.</p></td>
    </tr>
    </tbody>
    </table>


3.  On the **General** tab, specify the general parameters for off-budget funds contribution calculations.
    
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
    <td><p><strong>Off-budget funds</strong></p></td>
    <td><p>Enter the degree of precision to use to round off the individual contribution amount.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Base for FSS</strong></p></td>
    <td><p>Select a counter that is used to determine the base for Social Insurance Fund contribution calculations.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fund base limit</strong></p></td>
    <td><p>Select a deduction code that is used to limit the maximum yearly base for Social Insurance Fund contribution calculations.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Disability deduction code</strong></p></td>
    <td><p>Select a deduction code that is used to limit the yearly base for Social Insurance Fund contribution calculations for employees that have a disability.</p></td>
    </tr>
    </tbody>
    </table>


4.  On the **Future period tax** tab, select the calculation method that is used to calculate individual income tax for future period accruals.
    
    Select from the following options:
    
      - **Not calculated** – The income for future periods is accounted for in the month in which it is accrued. Individual income tax is deducted in the same month. In this case, no debt is created for the tax agency or for the employee.
    
      - **In month when income was earned** – The income for future periods is accounted for in the month in which it is calculated. Individual income tax is deducted in the month in which the income is accrued. In this case, monthly debt is created for the tax agency.
    
      - **In month for which income was accrued** – The income for future periods is accounted for in the month in which it is accrued. Individual income tax is deducted in the same month. In this case, a monthly debt is created for the employee in the tax record.
        

        > [!NOTE]
        > <P>These options are applicable only if you clear the <STRONG>Separate divisions handling</STRONG> check box.</P>



5.  On the **Pension fund export** tab, specify the general details, payment details, and individual details that are used for the Pension fund reporting.
    
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
    <td><p><strong>Country/region</strong></p></td>
    <td><p>Select the country/region that is used as the default country/region in the employee’s address in the Pension fund related reporting forms.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Cumulative</strong></p></td>
    <td><p>Select the counter code that is used to calculate the tax base for contributions for the cumulative part of the Pension fund. This calculation is performed for the cumulative portion of the labor pension,</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Insurance</strong></p></td>
    <td><p>Select the counter code that is used to calculate the tax base for contributions for the insurance part of the Pension fund. This calculation is performed for the insurance portion of the labor pension.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Voluntary</strong></p></td>
    <td><p>Select the counter code that is used to calculate the tax base for voluntary Pension fund contributions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Additional (p.1 art.58.3 212-FZ)</strong></p></td>
    <td><p>Select the counter code that is used to calculate the tax base for additional Pension fund contributions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Additional (p.2 art.58.3 212-FZ)</strong></p></td>
    <td><p>Select the counter code that is used to calculate the tax base for additional Pension fund contributions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Storno counting type</strong></p></td>
    <td><p>Select the counting type for storno that is used in the Pension fund correction reports.</p>
    <p>Select from the following options:</p>
    <ul>
    <li><p><strong>All</strong> – All of the storno adjustments are displayed on the correction reports.</p></li>
    <li><p><strong>Increasing and non-compensable</strong> – The storno adjustments that increase the contribution base and the fund’s contributions, as well as the storno adjustments that can’t be compensated by the calculations that are made in the current period are displayed on the correction reports.</p></li>
    <li><p><strong>Non-compensable only</strong> – Only the storno adjustments that can’t be compensated by the calculations that are made in the current period are displayed on the correction reports.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Limit by payroll period</strong></p></td>
    <td><p>Select the ending date in the payroll period for off-budget fund data selection that is used for the Pension fund reporting.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Pension fund</strong></p></td>
    <td><p>Select the counter code that is used to calculate the contributions to the insurance part of the Pension fund.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Deduction code for people with disability</strong></p></td>
    <td><p>Select the deduction code that is used to calculate the base of contributions to the insurance part of the Pension fund for an employee that has a disability.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Fund base limit</strong></p></td>
    <td><p>Select a deduction code that is used to limit the maximum yearly base for the calculation of the insurance portion of the Pension fund.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Insured foreign citizens</strong></p></td>
    <td><p>Select the rate code that is used to identify a foreign citizen to be insured.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum number of documents per file</strong></p></td>
    <td><p>Select a rate code that is used to determine the maximum number of documents that can be included in an electronic document file that is submitted to the Pension fund.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Maximum quantity of persons per package</strong></p></td>
    <td><p>Select a rate code that is used to determine the maximum number of people whose details can be included in a package of electronic documents that is submitted to the Pension fund.</p></td>
    </tr>
    </tbody>
    </table>


6.  On the **PF reports submission periods** tab, click **New** to create a record.

7.  In the **Period** field, select the reporting period type for the Pension fund reports.

8.  In the **Submission date** field, select the date when you submit the reports for the selected reporting period.

## Next step

You have finished setting up taxes and funds for the payroll process. Continue to set up additional parameters for the payroll process. For more information, see the following topics:

  - [(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md)

  - [(RUS) Set up vacations, business trips, and incentives for the payroll process](rus-set-up-vacations-business-trips-and-incentives-for-the-payroll-process.md)

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
<td><p>To set up taxes and funds for the payroll process, you must be a member of a security role that includes the following duties.</p>
<ul>
<li><p><strong>Enable payroll process</strong> (HcmPayrollProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Inquire into compensation process</strong> (HcmCompensationInquire)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Inquire into payroll process</strong> (HcmPayrollProcessInquire)</p></li>
<li><p><strong>Inquire into time management process</strong> (RPayTimeProcessInquire)</p></li>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up taxes and funds for the payroll process, you must be a member of a security role that includes the following privileges.</p>
<ul>
<li><p><strong>Maintain base payroll information</strong> (HcmPayrollBasisMaintain)</p></li>
<li><p><strong>Maintain income tax codes</strong> (HcmIncomeTaxCodeMaintain)</p></li>
<li><p><strong>Query other tax settings</strong> (RPayOtherTaxSettingsQuery)</p></li>
<li><p><strong>View groups of pay types (funds)</strong> (RPayFundGroupView)</p></li>
<li><p><strong>View income or expense calculation sequences</strong> (RPayCalcSeqView)</p></li>
<li><p><strong>View pay adjustment pay types</strong> (JmgPayAdjustCostTypeView)</p></li>
<li><p><strong>View the list of dependent elements</strong> (RPayDependentListView)</p></li>
<li><p><strong>View groups of calculation procedures</strong> (RPayCalcProcGroupView)</p></li>
<li><p><strong>View base payroll information</strong> (HcmPayrollBasisView)</p></li>
<li><p><strong>View income tax codes</strong> (HcmIncomeTaxCodeView)</p></li>
<li><p><strong>Maintain calculation sequences</strong> (RPayCalcSeqMaintain)</p></li>
<li><p><strong>Maintain groups of calculation procedures</strong> (RPayProcGroupMaintain)</p></li>
<li><p><strong>Maintain groups of pay types (funds)</strong> (RPayFundGroupMaintain)</p></li>
<li><p><strong>Maintain pay types</strong> (RPayTypeMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


