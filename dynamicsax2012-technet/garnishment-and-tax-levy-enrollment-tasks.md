---
title: Garnishment and tax levy enrollment tasks
TOCTitle: Garnishment and tax levy enrollment tasks
ms:assetid: 1aacc99e-b198-42fe-8da8-ee633c8076f4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497724(v=AX.60)
ms:contentKeyID: 62200038
ms.date: 11/15/2014
mtps_version: v=AX.60
f1_keywords:
- tax levy
- garnishment
- garnishments
- tax levies
- administrative fee
- administrative fees
---

# Garnishment and tax levy enrollment tasks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to enroll workers in garnishments, tax levies, and any associated administrative fees. In Microsoft Dynamics AX, garnishments and tax levies are managed by using the benefit framework. This framework helps make sure that the payroll impact of garnishments and tax levies is handled correctly.

If you have questions about garnishments and tax levies that are not answered in this topic or in [Garnishment and tax levy setup tasks](garnishment-and-tax-levy-setup-tasks.md) or [Garnishments, tax levies, and administrative fees](garnishments-tax-levies-and-administrative-fees.md), contact your legal advisors.

## What do you want to do?

Learn more about...

Review the prerequisites

Enroll a worker in a garnishment or tax levy

Optional: Enroll workers in administrative fees

Additional setup requirements when a worker is enrolled in multiple garnishments or tax levies and the garnishment enhancement hotfix is not installed

Technical information for system administrators

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Garnishments, tax levies, and administrative fees](garnishments-tax-levies-and-administrative-fees.md)

## Review the prerequisites

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 or Microsoft Dynamics AX 2012 R2</p>
<div>

> [!IMPORTANT]
> <P>If you’re using AX 2012 R2, we strongly recommend that you install the garnishment enhancement hotfix.</P>
> <P>The garnishment enhancement hotfix may have been installed automatically if you installed a different hotfix that shares dependencies with the garnishment enhancement hotfix.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>(USA) The primary address for the legal entity must be in the following countries/regions: United States</p></td>
</tr>
</tbody>
</table>


Back to top

## Enroll a worker in a garnishment or tax levy

When the payroll department receives notice of a court-ordered garnishment or tax levy, the federal government requires that deductions begin within a specific number of days. As with other garnishment rules, some states might use the federal rules, or they might set their own requirements. For example, a state might require that deductions begin with the first payroll payment at least three days after the order is received, which could be the current pay period. Therefore, make sure that you get workers correctly enrolled as quickly as possible.

When you enroll a worker, you will set up payroll information together with garnishment or tax levy details. The steps to enter the garnishment or tax levy details vary, depending on whether the garnishment enhancement hotfix is installed. Make sure that you use the correct steps.

To enroll a worker in a garnishment or tax levy, follow these steps:

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, click **Personal information**, and then click **Benefits**.

3.  Click **Add**.

4.  In the **Benefit** field, select **Eligibility bypassed**.

5.  Select the benefit for the garnishment or tax levy.
    
    Dependent and beneficiary information isn’t required for a garnishment. You don’t have to do anything on the **Dependents** or **Beneficiaries** FastTabs.

6.  On the **Payroll details** FastTab, enter this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Paid by</strong></p></td>
    <td><p>The legal entity that the worker is employed by and that pays for the worker position. By default, the current legal entity is displayed. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa590982(v=ax.60)">Positions (form)</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position</strong></p></td>
    <td><p>This field isn’t available if the garnishment enhancement hotfix has been installed.</p>
    <p>If the garnishment enhancement hotfix hasn’t been installed, leave this field blank.</p>
    <p>If you select a position, the deduction for the garnishment is based only on the earnings from the position. It is unlikely that a garnishment is based on earnings from a specific position. If you don’t select a position, the deductions for the garnishment are based on all the worker’s earnings.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor</strong></p></td>
    <td><p>The vendor that the garnishment is paid to. This is usually a state agency. The agency is listed on the garnishment order. If you don’t already have a vendor record for the agency, you must create one. For more information, see <a href="create-a-vendor-account.md">Create a vendor account</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation priority</strong></p></td>
    <td><p>The order that deductions for the garnishment are calculated in, relative to other benefits. The deductions and contributions for the benefit that have the lowest calculation priority number are calculated first, starting with 0 (zero). When multiple benefits have the same number, the calculations for those benefits are completed in alphabetical order.</p>
    <p>The calculation order is important when the result of the calculation for one benefit is used in the calculation for another benefit. For example, in some states, the deductions for union dues and health plans reduce disposable income. To make sure that the garnishment is calculated correctly, you must make sure that union dues and health plans have a lower calculation priority number than the garnishment does.</p>
    <p>For tax levies, voluntary benefit enrollments that were in place before the tax levy typically have a higher priority than the tax levy. Those benefits must therefore have a lower calculation priority number than the tax levy.</p>
    <div>

    > [!IMPORTANT]
    > <P>Your legal advisors should help you determine the correct calculation priority for all benefits.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deduction priority</strong></p></td>
    <td><p>The order that deductions for the garnishment are made in, relative to other deductions.</p>
    <p>The deduction for the benefit that has the lowest deduction priority number is made first, starting with 0 (zero). When multiple benefits have the same number, the deductions for those benefits are made in alphabetical order.</p>
    <p>Garnishments often must be deducted from pay before other voluntary benefits, although some states require specific deductions to take precedence, such as union dues or term life deductions.</p>
    <p>The default value for this field is set in the <strong>Benefit elements</strong> form. For more information about this field, see <a href="https://technet.microsoft.com/en-us/library/hh209498(v=ax.60)">Benefit elements (form)</a>.</p>
    <div>

    > [!IMPORTANT]
    > <P>Your legal advisors should help you determine the correct deduction priority for all benefits.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate source</strong></p></td>
    <td><p>This field is automatically set to <strong>Custom</strong>. Because you must manually maintain the amount of a garnishment, you can’t change this value. For more information, see “Set up payroll information for benefits” in <a href="worker-and-position-payroll-tasks.md">Worker and position payroll tasks</a>.</p>
    <p>This field isn’t available for tax levies.</p>
    <p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis</strong></p>
    <p><strong>Deduction</strong></p></td>
    <td><p>The court order indicates whether the deduction should be a fixed amount (for example, 350.00 per pay period) or a percentage of earnings (for example, 15 percent of earnings). Select the basis and enter the deduction amount that is specified on the court order.</p>
    <p>These fields aren’t available for tax levies. The tax levy deduction is calculated based on the information on the <strong>Tax levy details</strong> FastTab.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Notes</strong></p></td>
    <td><p>Enter detailed information about the garnishment order, such as the date received, date entered, and communication with the worker.</p></td>
    </tr>
    </tbody>
    </table>


7.  In most cases, garnishment orders don’t have limit amounts or periods; the garnishment continues until the court sends a notification to stop.
    
    If a limit is indicated on the support order, on the **Payroll limits** FastTab, enter a value in the **Limit amount** field. Then set the limit period and enter the initial amount of the order in the **Remaining** field.

8.  If the garnishment enhancement hotfix is installed, skip this step.
    
    If the garnishment enhancement hotfix isn’t installed, on the **Garnishment details** FastTab or the **Tax levy details** FastTab, enter the following information. If you need more information about these fields, see [Maintain benefits (form)](https://technet.microsoft.com/en-us/library/hh209235\(v=ax.60\)) or contact your legal advisors.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Garnishment type</strong> <br />
    or<br />
     <strong>Tax levy type</strong></p></td>
    <td><p>The garnishment or tax levy type.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Case number</strong></p></td>
    <td><p>The case number or reference number that is assigned by the court.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Limit method</strong></p></td>
    <td><p>In most cases, select <strong>Calculate disposable income</strong>.</p>
    <p>Select <strong>Use alternative limit</strong> if your legal advisors direct you to do this. When your legal advisors direct you to select this option, they should provide the amount to enter in the <strong>Alternative limit</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Disposable income definition</strong></p>
    <p><strong>Maximum withholding percent</strong></p></td>
    <td><p>If the state that issued the garnishment requires any changes to the federal rules for defining the worker’s disposable income, select the disposable income definition for this garnishment, and then enter the maximum withholding percentage that is provided in the court order. Otherwise, leave these fields blank.</p>
    <p>These fields are available only for garnishments and only when the limit method is <strong>Calculate disposable income</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Income exempt from levy</strong></p></td>
    <td><p>Enter the amount of wages that are exempt from the tax levy.</p>
    <ul>
    <li><p>For a federal tax levy, use publication 1494, which is updated and issued each year.</p></li>
    <li><p>For state and local tax levies, see the state’s tax levy withholding rules and apply the formulas to determine the amount of the exemption.</p></li>
    </ul>
    <p>This field is available only for tax levies and only when the limit method is <strong>Calculate disposable income</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Alternative limit</strong></p></td>
    <td><p>The maximum amount that can be deducted from a single pay statement for the garnishment. This amount should be provided by your legal advisors.</p>
    <p>This field is available only when the limit method is <strong>Use alternative limit</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Administrative fee</strong></p></td>
    <td><p>The amount to reduce the deduction for the garnishment by when the deduction for the garnishment plus the deduction for the administrative fee exceeds the worker’s disposable income limit.</p>
    <p>This field does not cause the administrative fee to be deducted; it just sets the amount by which to reduce the garnishment deduction. To deduct the administrative fee, you must create a benefit for the administrative fee, and assign that benefit to the worker.</p>
    <div>

    > [!WARNING]
    > <P>The amount in this field must be the same as the amount in the <STRONG>Amount or rate</STRONG> field for the administrative fee benefit that you assign to the worker.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Multiple garnishment method</strong></p></td>
    <td><p>Select the option to use if the amount of the deduction has to be split among multiple garnishments of the same type:</p>
    <ul>
    <li><p><strong>None</strong> – The garnishment should not be included in a group of garnishments.</p></li>
    <li><p><strong>Pro rata</strong> – The deduction is divided so that each garnishment receives a proportionate amount.</p></li>
    <li><p><strong>Equal</strong> – The deduction is divided so that each garnishment receives an equal amount.</p></li>
    <li><p><strong>First in</strong> – The garnishments are satisfied in the order that the worker enrolled in them. This option is typically used for tax levies.</p></li>
    </ul>
    <div>

    > [!IMPORTANT]
    > <P>If the court order does not specify which method to use, check with your legal advisors for clarification. Typically, if the orders have the same type but are from different states, the laws in the state where the worker works apply.</P>
    > <P>For example, a worker who is located in Washington has three support orders — two from California and one from Idaho. The rules for Washington apply to all three orders. If the worker in Washington had two support orders from California and a creditor garnishment from Idaho, the support orders would use the California rules and the creditor garnishment would use the Idaho rules.</P>


    </div>
    <p>If it isn’t clear which method to use, see <a href="https://technet.microsoft.com/en-us/library/hh209235(v=ax.60)">Maintain benefits (form)</a> or check with your legal advisors for clarification.</p></td>
    </tr>
    </tbody>
    </table>
    
    If the worker is enrolled in more than one garnishment or tax levy, you must complete the steps in “Additional setup requirements when a worker is enrolled in multiple garnishments or tax levies and the garnishment enhancement hotfix is not installed” later in this topic.
    
    When you complete this step, if your organization charges an administrative fee for handling garnishments, see “Optional: Enroll workers in administrative fees” later in this topic.

9.  If the garnishment enhancement hotfix is installed, on the **Garnishment and tax levy details** FastTab, enter the following information. If you need more information about these fields, see [Maintain benefits (form)](https://technet.microsoft.com/en-us/library/hh209235\(v=ax.60\)) or contact your legal advisors.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Type</strong></p></td>
    <td><p>The garnishment or tax levy type.</p>
    <p>Don’t select the <strong>Combined garnishments</strong> type. If a worker is enrolled in garnishments and tax levies of more than one type, you set up rules for the <strong>Combined garnishments</strong> type in the <strong>Garnishment and tax levy rules</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Case number</strong></p></td>
    <td><p>The case number or reference number that is assigned by the court.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>State</strong></p></td>
    <td><p>The state that the tax levy is from.</p>
    <p>This field is available only for state and local tax levies. It isn’t available for other garnishment types.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Administrative fee</strong></p></td>
    <td><p>When the garnishment type is <strong>Support order</strong>, if the deduction for the garnishment plus the deduction for the administrative fee exceeds the worker’s disposable income limit, the deduction for the garnishment is reduced by this amount. This guarantees that the total deduction does not exceed the worker’s disposable income limit for support orders.</p>
    <p>For all other garnishment and tax levy types, this field is for your information only.</p>
    <p>This field does not cause the administrative fee to be deducted. To deduct the administrative fee, you must create a benefit for the administrative fee, and assign that benefit to the worker.</p>
    <div>

    > [!WARNING]
    > <P>The sum of all administrative fees that should be charged to the worker should equal the sum of the deductions for all administrative fee benefits that the worker is enrolled in. If the amounts differ, the amount that is deducted from the worker’s pay for administrative fees might be incorrect.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


10. If the garnishment enhancement hotfix is installed, note which garnishment and tax levy types the worker is enrolled in, and then click **Garnishment and tax levy rules**.
    
    You set up each garnishment type only one time for each worker. When a worker has more than one garnishment of the same type, all the garnishments that have the same type use the rules that are set up for that type. State and local tax levies are an exception; you set up one state tax levy type and one local tax levy type for each state.

11. When the **Garnishment and tax levy rules** form opens, click **Add**, and then enter the following information for each garnishment type that the worker is enrolled in.
    
    If you need more information about these fields, see [Garnishment and tax levy rules (form)](https://technet.microsoft.com/en-us/library/dn497842\(v=ax.60\)) or contact your legal advisors.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Grid heading</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Type</strong></p></td>
    <td><p>The garnishment type.</p>
    <div>

    > [!IMPORTANT]
    > <P>When a worker is enrolled in more than one type of garnishment, you must add the <STRONG>Combined garnishments</STRONG> type in addition to the types that the worker is enrolled in. The <STRONG>Combined garnishments</STRONG> type is used to make sure that the garnishment amounts are adjusted correctly, based on the selected disposable income definition and any rules that might apply across garnishment types.</P>
    > <P>The disposable income definition and maximum withholding percentage are the only fields that are used by the <STRONG>Combined garnishments</STRONG> type. All other fields are for your information only.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>State</strong></p></td>
    <td><p>The state that a tax levy is from.</p>
    <p>This field is available only for state and local tax levies. It isn’t available for other garnishment types.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Limit method</strong></p></td>
    <td><p>Select <strong>Calculate disposable income</strong> to calculate the worker’s disposable income for garnishments of this type.</p>
    <p>Select <strong>Use alternative limit</strong> only if you are directed to do this by your legal advisors. If your legal advisors direct you to use this method, they should provide the amount to enter in the <strong>Alternative limit</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Disposable income definition</strong></p></td>
    <td><p>Select the disposable income definition to use for garnishments of this type. If you leave this field blank, the federal rules for defining the worker’s disposable income are used.</p>
    <p>This field is available only when the limit method is <strong>Calculate disposable income</strong>. For more information, see <a href="garnishment-and-tax-levy-setup-tasks.md">Garnishment and tax levy setup tasks</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Maximum withholding percent</strong></p></td>
    <td><p>Enter the maximum percentage of disposable income that can be withheld for garnishments of this type.</p>
    <p>For the <strong>Combined garnishments</strong> type, enter the maximum percentage of disposable income that can be deducted for the combined total of all garnishments except support orders and tax levies.</p>
    <p>If you leave this field set to 0.0000, no deduction is made.</p>
    <p>This field is available only when the limit method is <strong>Calculate disposable income</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Alternative limit</strong></p></td>
    <td><p>Enter the maximum amount that can be deducted from a single pay statement for garnishments of this type. The amount should be provided by your legal advisors.</p>
    <p>This field is available only when the limit method is <strong>Use alternative limit</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Multiple garnishment method</strong></p></td>
    <td><p>Select the option to use if the amount of the deduction has to be split among multiple garnishments of the same type:</p>
    <ul>
    <li><p><strong>None</strong> – The deduction isn’t split among garnishments of this type.</p></li>
    <li><p><strong>Pro rata</strong> – The deduction is divided so that each garnishment receives a proportionate amount.</p></li>
    <li><p><strong>Equal</strong> – The deduction is divided so that each garnishment receives an equal amount.</p></li>
    <li><p><strong>First in</strong> – The garnishments are satisfied in the order that the worker enrolled in them. This option is typically used for tax levies.</p></li>
    </ul>
    <div>

    > [!IMPORTANT]
    > <P>If the court order does not specify which method to use, check with your legal advisors for clarification. Typically, if the orders have the same type but are from different states, the laws in the state where the worker works apply.</P>
    > <P>For example, a worker who is located in Washington has three support orders — two from California and one from Idaho. The rules for Washington apply to all three orders. If the worker in Washington had two support orders from California and a creditor garnishment from Idaho, the support orders would use the California rules and the creditor garnishment would use the Idaho rules.</P>


    </div>
    <p>If it is not clear which method to use, see <a href="https://technet.microsoft.com/en-us/library/dn497842(v=ax.60)">Garnishment and tax levy rules (form)</a> or check with your legal advisors for clarification.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Exempt disposable income</strong></p></td>
    <td><p>Enter the amount that should be used to further reduce the allowable deduction after the worker’s disposable income is calculated.</p>
    <p>The amount should be provided by your legal advisors. It is based on IRS publication 1494 and applicable state requirements.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Exempt earnings</strong></p></td>
    <td><p>Enter the amount that the worker’s earnings should be reduced by before the disposable income is calculated.</p>
    <p>The amount should be provided by your legal advisors.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Minimum wage</strong></p>
    <p><strong>Minimum wage multiplier</strong></p></td>
    <td><p>The weekly minimum wage and minimum wage multiplier to use to calculate the garnishment amount. The minimum wage can be the Federal minimum wage or a state minimum wage.</p>
    <p>For more information, see the state rules for the garnishment type or contact your legal advisors.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Allow reduction</strong></p></td>
    <td><p>Select this check box if deduction amounts for this garnishment type can be reduced to stay within the mandated limit for all garnishment types.</p>
    <p>This check box is usually selected for student loan garnishments and cleared for support orders. If you aren’t sure whether to select this check box, contact your legal advisors.</p></td>
    </tr>
    </tbody>
    </table>


12. If the garnishment enhancement hotfix is installed, on the **Comments** FastTab, click **Add** to enter information about the garnishment or tax levy types you entered or changed.

If your organization charges an administrative fee for handling garnishments, continue with “Optional: Enroll workers in administrative fees” in this topic.

Back to top

## Optional: Enroll workers in administrative fees

Administrative fees, such as garnishments and tax levies, are processed as benefits in AX 2012. Administrative fees aren’t permitted in every state. Where they are permitted, they are never mandatory. It is up to your organization to decide whether to charge them.

The steps to enroll a worker in an administrative fee vary, depending on whether the garnishment enhancement hotfix is installed.

  - If the garnishment enhancement hotfix isn’t installed, enroll the worker in one administrative fee benefit for each administrative fee that the worker is charged. For each administrative fee benefit, the amount in the **Amount or rate** field on the **Payroll details** FastTab of the **Benefit** form must match the amount in the **Administrative fee** field on the **Garnishment details** FastTab or the **Tax levy details** FastTab of the **Maintain benefits** form.

  - If the garnishment enhancement hotfix is installed, enroll the worker in one administrative fee benefit. The amount in the **Amount or rate** field on the **Payroll details** FastTab of the **Benefit** form for the benefit should equal the sum of all the administrative fees that the worker is charged.

### Enroll a worker in an administrative fee if the garnishment enhancement hotfix is not installed

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, click **Personal information**, and then click **Benefits**.

3.  Click **Add**.

4.  In the **Benefit** field, select **Eligibility bypassed**.

5.  Select the benefit for an administrative fee.
    
    Dependent and beneficiary information isn’t required for an administrative fee. You don’t have to do anything on the **Dependents** or **Beneficiaries** FastTabs.

6.  On the **Payroll details** FastTab, enter this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Paid by</strong></p></td>
    <td><p>Select the legal entity that the worker is employed by and that pays for the worker position. By default, the current legal entity is displayed. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa590982(v=ax.60)">Positions (form)</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position</strong></p></td>
    <td><p>Leave this field blank.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor</strong></p></td>
    <td><p>Leave this field blank.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation priority</strong></p></td>
    <td><p>The calculation priority for the administrative fee, which is the same as the calculation priority for the garnishment or tax levy that the fee is charged for.</p>
    <div>

    > [!IMPORTANT]
    > <P>Your legal advisors should help you determine the correct calculation priority for all benefits.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deduction priority</strong></p></td>
    <td><p>The deduction priority for the administrative fee, which is the same as the deduction priority for the garnishment or tax levy that the fee is charged for.</p>
    <div>

    > [!IMPORTANT]
    > <P>Your legal advisors should help you determine the correct deduction priority for all benefits.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate source</strong></p></td>
    <td><p>Select <strong>Benefit</strong>. This lets you use the automated process to update the <strong>Deduction</strong> field for each worker who is enrolled in the administrative fee benefit when you change the <strong>Amount or rate</strong> field in the <strong>Benefit</strong> form. For more information, see <a href="worker-and-position-payroll-tasks.md">Worker and position payroll tasks</a>.</p>
    <p>If you select <strong>Custom</strong>, you must manually maintain the value in the <strong>Deduction</strong> field for each worker.</p>
    <div>

    > [!WARNING]
    > <P>After you change the amount of the deduction, regardless of whether you change it manually or automatically, you must manually change the amount of the administrative fee on the garnishment or tax levy benefit that the fee is charged for. The two amounts must be the same.</P>


    </div>
    <p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis</strong></p></td>
    <td><p>Select <strong>Fixed amount</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Deduction</strong></p></td>
    <td><p>Enter the amount of the administrative fee.</p>
    <div>

    > [!NOTE]
    > <P>The amount in this field must match the amount in the <STRONG>Administrative fee</STRONG> field on the <STRONG>Garnishment details</STRONG> FastTab or the <STRONG>Tax levy details</STRONG> FastTab of the garnishment or tax levy benefit that the fee is charged for.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Notes</strong></p></td>
    <td><p>Enter information about the administrative fee.</p></td>
    </tr>
    </tbody>
    </table>


### Enroll a worker in an administrative fee if the garnishment enhancement hotfix is installed

1.  Click **Payroll** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker, click **Personal information**, and then click **Benefits**.

3.  Click **Add**.

4.  In the **Benefit** field, select **Eligibility bypassed**.

5.  Select the benefit for an administrative fee.
    
    Dependent and beneficiary information isn’t required for an administrative fee. You don’t have to do anything on the **Dependents** or **Beneficiaries** FastTabs.

6.  On the **Payroll details** FastTab, enter this information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Value to enter</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Paid by</strong></p></td>
    <td><p>Select the legal entity that the worker is employed by and that pays for the worker position. By default, the current legal entity is displayed. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa590982(v=ax.60)">Positions (form)</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position</strong></p></td>
    <td><p>Leave this field blank.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Vendor</strong></p></td>
    <td><p>Leave this field blank.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Calculation priority</strong></p></td>
    <td><p>Your legal advisors should determine the correct calculation priority for the administrative fee benefit.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deduction priority</strong></p></td>
    <td><p>Your legal advisors should determine the correct deduction priority for the administrative fee benefit.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Rate source</strong></p></td>
    <td><p>Select <strong>Custom</strong>. You must manually update the deduction amount for each worker when you change the amount you charge for an administrative fee. You must also update the deduction amount when you enroll the worker in an additional garnishment that you charge an administrative fee for.</p>
    <p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Basis</strong></p></td>
    <td><p>Select <strong>Fixed amount</strong>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Deduction</strong></p></td>
    <td><p>Enter the total amount of all administrative fees that are charged to this worker for garnishments and tax levies.</p>
    <div>

    > [!NOTE]
    > <P>You might have to adjust this amount in pay periods when some of the worker’s garnishments or tax levies can’t be taken.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Notes</strong></p></td>
    <td><p>Enter information about the administrative fee.</p></td>
    </tr>
    </tbody>
    </table>


Back to top

## Additional setup requirements when a worker is enrolled in multiple garnishments or tax levies and the garnishment enhancement hotfix is not installed

This section applies only if the garnishment enhancement hotfix isn’t installed.

When a worker has more than one garnishment order or tax levy, it might not be possible to deduct the full amount of every garnishment and tax levy. Federal and state laws dictate the maximum amount that can be deducted for all garnishments, tax levies, and administrative fees combined. State laws dictate how to allocate the total amount among the various garnishments and tax levies, based in part on the garnishment type and the calculation priority.

When a worker’s garnishments have the same type and calculation priority, the amounts are calculated automatically. If a worker has more than one kind of garnishment, you might have to perform some of the calculations manually. Procedures for both situations are described later in this topic.

## Set up multiple garnishments of the same type

When a worker has more than one garnishment of the same type and the same calculation priority, you must specify the **Multiple garnishment method** to use to allocate the amount of the deduction among the garnishments, as described in “Enroll a worker in a garnishment or tax levy” earlier in this topic.

When multiple garnishments must be processed together, make sure that the garnishments have the same values in these fields in the **Maintain benefits** form:

  - **Calculation priority**

  - **Garnishment type**

  - **Multiple garnishment method**

A garnishment that has a different value in any one these fields isn’t included with the garnishments that are processed together.

To make sure that garnishments of the same type are calculated correctly, you might have to adjust the calculation priority on one or more of the garnishments so that they match. You should seek guidance from your legal advisors any time that a worker has more than one garnishment or tax levy of the same type.

## Examples of multiple garnishments of the same type

A worker has the following child support orders. Because the calculation priority, garnishment type, and multiple garnishment method of all three child support orders match, the three garnishments are processed together.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>ChldSup 01</p></th>
<th><p>ChldSup 02</p></th>
<th><p>ChldSup03</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Calculation priority</strong></p></td>
<td><p>20</p></td>
<td><p>20</p></td>
<td><p>20</p></td>
</tr>
<tr class="even">
<td><p><strong>Basis</strong></p></td>
<td><p><strong>Fixed amount</strong></p></td>
<td><p><strong>Fixed amount</strong></p></td>
<td><p><strong>Fixed amount</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Deduction</strong></p></td>
<td><p>450.0000</p></td>
<td><p>225.0000</p></td>
<td><p>200.0000</p></td>
</tr>
<tr class="even">
<td><p><strong>Garnishment type</strong></p></td>
<td><p><strong>Support order</strong></p></td>
<td><p><strong>Support order</strong></p></td>
<td><p><strong>Support order</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maximum withholding percent</strong></p></td>
<td><p>55.0000</p></td>
<td><p>55.0000</p></td>
<td><p>55.0000</p></td>
</tr>
<tr class="even">
<td><p><strong>Multiple garnishment method</strong></p></td>
<td><p><strong>Pro rata</strong></p></td>
<td><p><strong>Pro rata</strong></p></td>
<td><p><strong>Pro rata</strong></p></td>
</tr>
</tbody>
</table>


**Wages and other factors that influence the garnishment amount**

The worker’s gross wages for the pay period are 2,000.00, and the total amount of taxes and benefits that are excluded from the worker’s disposable income is 600.00. Therefore, the worker’s calculated disposable income is 2,000.00 minus 600.00, or 1,400.00.

The maximum amount that can be withheld from the worker’s pay for these garnishments is 55 percent of 1,400.00, or 770.00.

The total amount that is required by the three garnishments is 45.000 + 225.00 + 200.00, or 875.00.

Because 875.00 is more than 770.00, which is the maximum allowed, the multiple garnishment method must be applied.


> [!NOTE]
> <P>If the total garnishments that were requested were less than the maximum withholding allowed, the full amount of each garnishment would be taken and no multiple garnishment method would be applied.</P>



**How the pro rata amount for each garnishment is determined**

In this example, these are the garnishment amounts for the **Pro rata** method:

  - Total amount from all three support orders: 875.00

  - Maximum amount of withholding allowed: 770.00

  - Percentage applicable to the first order: 51 percent (450.00 / 875.00)

  - Percentage applicable to the second order: 26 percent (225.00 / 875.00)

  - Percentage applicable to the third order: 23 percent (200.00 / 875.00)

  - First garnishment amount: 392.70 (770.00 x .51)

  - Second garnishment amount: 200.20 (770.00 x .26)

  - Third garnishment amount: 177.10 (770.00 x .23)

**How the amount is determined by using the Equal method**

Based on the same wages and other factors described above, these are the garnishment amounts for the **Equal** method:

  - Maximum amount of withholding allowed: 770.00

  - Divide by 3 because there are three orders: 256.67

  - Third garnishment amount: 200.00 (the lesser of 256.67 and the requested amount)

  - Second garnishment amount: 225.00 (the lesser of 256.67 and the requested amount)

  - First garnishment amount: 345.00 (the maximum amount of 770.00 reduced by 200.00 from Garn03 and 225.00 from Garn02)

**How the amount is determined by using the First-in method**

Based on the same wages and other factors described above, these are the garnishment amounts for the **First in** method:

  - Maximum amount of withholding allowed: 770.00

  - First garnishment amount: 450.00. This is satisfied in full, and then is subtracted from the maximum amount, which leaves 320.00 for the other two garnishments.

  - Second garnishment amount: 225.00. This is satisfied in full, and then is subtracted from the 320.00 remaining, which leaves 95.00 for the third garnishment.

  - Third garnishment amount: 95.00.

After the amount that is remaining reaches 0 (zero), no additional amounts can be deducted for any garnishment.

## Set up multiple garnishments of different types

When a worker has multiple garnishments of different types, the individual limit that applies to each garnishment can be automatically determined. However, the final deductions against a single limit for the combined total of all of the garnishments can’t be determined. As a result, when there are multiple garnishments of different types, you must manually calculate the total disposable income limit and determine whether the combined amount of all of the garnishments and tax levies exceeds the maximum deduction limit.

If the combined amount exceeds the maximum deduction limit, set the following field values in the **Maintain benefits** form for each garnishment and tax levy that the worker is enrolled in.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field</p></th>
<th><p>Value to enter</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Basis</strong></p></td>
<td><p>Select <strong>Fixed amount</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Deduction</strong></p></td>
<td><p>Enter the amount of the garnishment that is specified on the court order.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Limit method</strong></p></td>
<td><p>Select <strong>Use alternative limit</strong>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Alternative limit</strong></p></td>
<td><p>Enter the amount to deduct for this garnishment on each paycheck, based on the calculated disposable income, type of garnishment, and deduction priority. Your legal advisors should provide this amount.</p>
<div>

> [!NOTE]
> <P>When there are multiple garnishments and tax levies, the deduction amount for one or more of the garnishments or tax levies can be 0 (zero).</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Multiple garnishment method</strong></p></td>
<td><p>Select <strong>None</strong>.</p></td>
</tr>
</tbody>
</table>


Back to top

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
<td><p><strong>Payroll - USA</strong></p>
<div>

> [!IMPORTANT]
> <P>When you use Payroll, we highly recommend that you turn off the <STRONG>Payroll information</STRONG> configuration key under the <STRONG>Human resource I</STRONG> configuration key. The forms and tables that are enabled by that configuration key are not used by Payroll. If Payroll is installed and the configuration key is enabled, it might be difficult to make sure that your data is entered and tracked correctly.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To work with garnishments and tax levies, you must be a member of a security role that includes these duties:</p>
<ul>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
<li><p><strong>Set up payroll positions and workers</strong>(PayrollPositionWorkerSetupMaintain)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To work with garnishments and tax levies, you must be a member of a security role that includes these privileges:</p>
<ul>
<li><p><strong>Maintain benefit setup</strong> (HcmBenefitElementSetupMaintain)</p></li>
<li><p><strong>Maintain benefits</strong> (HcmBenefitInquiryMaintain)</p></li>
<li><p><strong>Maintain worker enrollment</strong> (HcmWorkerEnrollmentMaintain)</p></li>
<li><p><strong>Maintain the date effective information for the selected rate structures</strong> (PayrollBenefitCalcRateDateMaintain)</p></li>
<li><p><strong>Maintain contribution calculation rates</strong> (PayrollBenefitCalcRateSetupMaintain)</p></li>
<li><p><strong>Maintain versions</strong> (PayrollBenefitReportingDateMgrMaintain)</p></li>
<li><p><strong>Maintain payroll calculation frequencies</strong> (PayrollCalculationFrequencyMaintain)</p></li>
<li><p><strong>Maintain disposable income definitions</strong> (PayrollDisposableIncomeMaintain)</p></li>
<li><p><strong>Maintain earning codes</strong> (PayrollEarningCodeMaintain)</p></li>
<li><p><strong>Maintain payroll earning code groups</strong> (PayrollEarningCodeGroupMaintain)</p></li>
<li><p><strong>Maintain worker garnishment and tax levy rules</strong> (PayrollGarnishmentRuleMaintain)</p></li>
<li><p><strong>Maintain payroll parameters</strong> (PayrollParametersMaintain)</p></li>
<li><p><strong>Maintain workers</strong> (HcmWorkerMaintain)</p></li>
</ul></td>
</tr>
</tbody>
</table>


Back to top

## Find form help

[Garnishment and tax levy rules (form)](https://technet.microsoft.com/en-us/library/dn497842\(v=ax.60\))

[Maintain benefits (form)](https://technet.microsoft.com/en-us/library/hh209235\(v=ax.60\))

[Positions (form)](https://technet.microsoft.com/en-us/library/aa590982\(v=ax.60\))

## Find related tasks

[Garnishment and tax levy setup tasks](garnishment-and-tax-levy-setup-tasks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

