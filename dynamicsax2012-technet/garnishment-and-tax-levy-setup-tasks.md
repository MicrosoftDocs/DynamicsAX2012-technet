---
title: Garnishment and tax levy setup tasks
TOCTitle: Garnishment and tax levy setup tasks
ms:assetid: 19e1f07f-79fa-469e-83b7-179479282a55
ms:mtpsurl: https://technet.microsoft.com/library/JJ682089(v=AX.60)
ms:contentKeyID: 49655576
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- child support
- tax levy
- garnishment
- Menu_Items.Display.PayrollDisposableIncome
- alimony
- bankruptcy
- creditor
- student loan
- spousal support
- support order
- garnishments
- tax levies
- wage garnishment
audience: Application User
ms.search.region: USA
---

# Garnishment and tax levy setup tasks 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up garnishments, tax levies, and any associated administrative fees. In Microsoft Dynamics AX, garnishments and tax levies are created and managed by using the benefit framework. This framework helps make sure that the payroll impact of garnishments and tax levies is handled correctly.

If you have questions about garnishments and tax levies that are not answered in this topic or in [Garnishment and tax levy enrollment tasks](garnishment-and-tax-levy-enrollment-tasks.md) or [Garnishments, tax levies, and administrative fees](garnishments-tax-levies-and-administrative-fees.md), contact your legal advisors.

When you set up the system to process garnishments and tax levies, you must complete the tasks that are shown in this illustration and summarized in list that follows. The numbers correspond to the procedures later in this topic.

![Steps for setting up garnishments and tax levies](images/JJ682089.Payroll_Garnishment_setup_overview(AX.60).gif "Steps for setting up garnishments and tax levies")

  - **Set up disposable income definitions.** When the court imposes an order to garnish a worker’s wages, the actual amount of the garnishment is limited to a percentage of the worker’s disposable income. The federal disposable income definition is built into the payroll calculation engine. However, some states require additional reductions to disposable income. You can use disposable income definitions to identify those reductions and help make sure that the correct earnings and deductions are included when the worker’s disposable income is calculated.

  - **Set up benefit elements for garnishments, tax levies, and administrative fees.** Because garnishments and tax levies are processed as benefits, each garnishment or tax levy consists of a benefit type, plan, and option. These elements combine to create a single instance of a garnishment or tax levy. For more information, see [Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\)).
    
    Administrative fees aren’t permitted in every state. Where they are permitted, they are never mandatory. It is up to your organization to decide whether to charge them.

  - **Create benefits for garnishments, tax levies, and administrative fees.** You must have at least one benefit for garnishments and one for tax levies. If a worker has more than one garnishment of the same type, you must have more than one garnishment benefit of that type.
    
    If your organization charges an administrative fee for handling garnishments and tax levies, you must have at least one benefit for the fee. You can also have additional benefits for other administrative fees, but this is optional.


> [!NOTE]
> <P>In this topic, <EM>garnishment</EM> implies both garnishments and tax levies, unless otherwise specified.</P>



## What do you want to do?

Learn more about...

Review the prerequisites

1\. Set up disposable income definitions

2\. Set up benefit elements

3\. Create benefits for garnishments and tax levies

Next step

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
<div class="alert">

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

## 1\. Set up disposable income definitions

When the court imposes an order to garnish a worker’s wages, the actual amount of the garnishment is limited to a percentage of the worker’s disposable income. Under the federal definition, the disposable income is determined by subtracting all deductions that are required by law from a worker’s gross earnings or income. Gross earnings include wages, commissions, bonuses, paid time off (PTO) pay, and periodic pension payments. These are some of the deductions that are required by law:

  - Federal, state, and local income tax

  - Social Security and Medicare tax

  - State unemployment or disability tax

  - State-mandated payments for state employee retirement systems

Under the federal formula, voluntary deductions — such as those for life insurance, union dues, and retirement plan contributions — are not subtracted from earnings. The federal formula has been built into the Payroll system.

Many states use the federal definition for disposable income. Some states have their own definitions, which exempt certain additional earnings from total wages and subtract other deductions, further reducing what is considered disposable income. You don’t have to create a definition using the federal formula; that formula is built into the Payroll system. But you do have to create additional disposable income definitions to comply with each state’s formula.


> [!IMPORTANT]
> <P>State definitions are subject to change every year. Because it can be difficult to match your organization’s earning codes and benefits to the definitions that are used by a specific state, we recommend that your legal advisors determine the earning codes and benefits to include in each disposable income definition. We also recommend that your advisors review the definitions each year.</P>



When you create a disposable income definition, you specify the earnings and the benefits to reduce the worker’s disposable income by. You don’t have to specify the taxes; all mandatory taxes are automatically subtracted from the total wages.

Tax levies and other garnishments aren’t automatically excluded from disposable income. If you have to exclude them from the worker’s disposable income, you must specify them in the benefit section of the disposable income definition.


> [!IMPORTANT]
> <P>Disposable income definitions don’t have date-effective versions. Therefore, when you change a definition, the change takes effect immediately. We recommend that you don’t change existing disposable income definitions that you have used. Instead, create a new disposable income definition, and then complete this step, depending on whether the garnishment enhancement hotfix is installed:</P>
> <UL>
> <LI>
> <P>If the garnishment enhancement hotfix isn’t installed, use the version settings in the <STRONG>Maintain benefits</STRONG> form to change from the old definition to the new definition on the required date for each worker that it applies to.</P>
> <LI>
> <P>If the garnishment enhancement hotfix is installed, select the new definition in the <STRONG>Garnishment and tax levy rules</STRONG> form for each worker that it applies to.</P></LI></UL>



To set up disposable income definitions, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Disposable income definition**.

2.  Click **New**.

3.  Enter the name and description for the disposable income definition.
    
    Because disposable income definitions are typically defined for each state, consider using the two-letter state abbreviation as the first two letters of the name of each disposable income definition. For example, when you create a disposable income definition for garnishments from Texas, enter a name that starts with TX. When you receive a new garnishment order, you can see whether you already have the necessary disposable income definition, or if you have to create a new one.

4.  Click the **Add** button above the **Reduce total wages by the following earnings:** grid. Select an earning code that represents the earnings that have been identified by the state as being exempt from disposable income. When total wages are calculated, earning lines that are designated by the earning code are excluded.
    
    Repeat this step to add more earning codes.
    

    > [!IMPORTANT]
    > <P>It can be difficult to match your organization’s earning codes to the definitions that are used by a specific state. Therefore, we recommend that your legal advisors determine the earning codes to include in each disposable income definition.</P>



5.  Click the **Add** button above the **Reduce disposable income by deductions for the following benefits:** grid. Select a benefit that has been identified by the state as being exempt from disposable income. When total wages are calculated, deductions for the selected benefits are excluded.
    
    Repeat this step to add more benefits.
    
    Consider that the system handles garnishments and tax levies as if they were benefits. Therefore, to exclude the amount of garnishments or tax levies from a disposable income definition, you must add the garnishment or tax levy benefits here.
    

    > [!IMPORTANT]
    > <P>We recommend that your legal advisors determine the benefits to include in each disposable income definition.</P>



If you delete an earning code or benefit, it is automatically removed from all disposable income definitions. New earning codes and benefits that are created aren’t automatically added. When you maintain earning codes and benefits, you must consider the effect of any changes on the disposable income definitions.

Back to top

## 2\. Set up benefit elements

Garnishments and tax levies are handled as benefits in Microsoft Dynamics AX. A benefit is a unique combination of a benefit type, plan, and option. Use this set of tasks to create the following benefit elements that are required to create garnishment and tax levy benefits:

  - **Benefit types** – You must create two benefit types — one for garnishments and one for tax levies. If your organization charges administrative fees for garnishments and tax levies, you must also create a benefit type for the administrative fees.

  - **Benefit plans** – Most organizations create a benefit plan for each type of garnishment and tax levy. You can create additional benefit plans. For example, you might create a separate benefit plan for tax levies from each state.

  - **Benefit options** – When you create benefit options, we recommend that you create a set of numbered options to use for garnishments and tax levies. For example, you might create options 01, 02, and 03. When you number the options in this manner, you can quickly see the order in which the garnishments were entered.

When you set up the benefit elements for garnishments and tax levies, consider that a worker can have multiple garnishments in effect at the same time, but the worker can have only one enrollment in each benefit at any time. Therefore, you must create multiple garnishment benefits. To do this, you can set up multiple benefit plans or multiple benefit options. The simpler method is to set up multiple benefit options, as described in the following set of tasks.

### Set up benefit types for garnishments, tax levies, and any administrative fees

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit elements**. The form opens in the **Types** area and is called **Define benefit types**.

2.  Click **New** to create a benefit type.

3.  Enter the name and description of the garnishment benefit type. For example, you might enter Garnishment and Court-ordered garnishment.

4.  In the **Concurrent enrollment** column, select **Multiple enrollments per type**. This is required so that you can enroll a worker in more than one garnishment benefit or more than one tax levy benefit at the same time.

5.  Select one of these payroll categories for the benefit type:
    
      - For garnishments, select **Garnishment**.
    
      - For tax levies, select **Tax levy**.
    
      - Optional: For administrative fees, select **Standard**.
    
    The payroll category makes sure that the benefit follows the processing requirements that are defined by the government for garnishments or tax levies. The payroll category also determines which settings are available in the **Plans** area of this form. Settings that don’t apply to the selected payroll category aren’t available.

6.  After you create the benefit type for garnishments, repeat this procedure to create a benefit type for tax levies. If your organization uses administrative fees, repeat the procedure again to create a benefit type for administrative fees.

When you have created the necessary benefit types, you can close the form, or continue with “Set up benefit plans” in this topic.

### Set up benefit plans

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  At the side of the form, click **Plans** to display the **Define benefit plans** area.

3.  Click **New** to create a benefit plan.
    
    You must create at least one benefit plan for garnishments and one for tax levies. However, we recommend that you create one benefit plan for each garnishment type and one for each tax levy type. If you use this approach, create these benefit plans:
    
      - Support order
    
      - Bankruptcy
    
      - Federal administrative
    
      - Student loan
    
      - Creditor
    
      - Federal tax levy
    
      - State tax levy
    
      - Local tax levy
    
      - Optional: Administrative fees

4.  Enter the name and a description of the benefit plan. For example, for the bankruptcy plan, you might enter Bankruptcy and Bankruptcy order. For an administrative fee plan, you might enter Admin fee and garnishments.

5.  Select the appropriate benefit type. This is one of the benefit types that you created in the previous procedure.

6.  Select the **Deduction only** payroll impact option.

7.  On the **Tax rule** FastTab, in the **Pretax basis** field, select **None**.

8.  On the **Payroll details** FastTab, set up this information:
    
      - To prevent pay statement lines that include the garnishment or tax levy from being changed, select the **Lock pay statement** check box. When this check box is selected, you can add lines that include the garnishment or tax levy to the pay statement, or delete them from the pay statement, but you can’t change garnishment or tax levy lines that are on the pay statement.
        
        If you don’t select this check box, you can change garnishment and tax levy lines directly on the pay statement.
    
      - The **Deduction method** field is automatically set to **Partial**. This means that part of the garnishment amount is automatically deducted from a worker’s pay if the whole amount can’t be deducted legally.
    
      - Make sure that at least one of these payment types is selected:
        
          - **Primary**
        
          - **Additional**
        
          - **Gross up**
        
        Deductions for the garnishment or tax levy are included in payroll runs of the selected type.
        

        > [!IMPORTANT]
        > <P>Many states have laws that specify how garnishments for child support are handled when a worker receives a lump-sum payment, such as a bonus, severance pay, or a vacation payout. The laws vary, but they typically include a provision that the state must be notified before a lump-sum payment is made. The state then gives the employer specific instructions about whether to calculate the garnishment, and how it should be calculated. In some cases, the whole lump-sum payment is subject to garnishment.</P>

    
      - The **Deduction priority** field determines the order that the garnishment or tax levy is deducted from pay, relative to other deductions. The default value is 100. Don’t change the value here. The value must be adjusted in the **Maintain benefits** form for each worker when the worker is enrolled in the garnishment or tax levy.
    
      - The limit period and limit amount differ for each worker and each garnishment or tax levy, and are set for a worker when the worker is enrolled. Leave the **Limit period** field empty and the **Limit amount** field set to 0.00.

9.  On the **Accounting** FastTab, set up accounting information for each legal entity that has workers enrolled in the garnishment or tax levy. Select the first legal entity, and then complete these steps:
    
      - Leave the **Category** field empty.
    
      - Leave the **Vendor** field empty. You select the vendor when you enroll the worker.
    
      - Optional: Enter the default financial dimension values for the benefit plan.
    
      - In the **Main account** field, select the general ledger account to apply the payroll deductions to for this benefit plan.
    
    If there is more than one legal entity in your organization, repeat this step for each legal entity.

10. Because garnishments and tax levies aren’t reported in boxes 10, 11, 12, or 14 of the worker’s Form W-2, leave the **Reporting** FastTab blank.

Repeat these steps to set up additional benefit plans. When you finish, you can close the form, or continue with “Set up benefit options” in this topic.

### Set up benefit options

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefit elements**.

2.  At the side of the form, click **Options** to display the **Define benefit options** area.

3.  Click **New** to create a benefit option.
    
    When you create the benefit options for garnishments, we recommend that you create a set of numbered options for garnishments and tax levies. For example, you might create options 01, 02, and 03. When you number the options in this manner, you can quickly see the order in which the garnishments were entered.

4.  Enter the name of the option and a description. For example, you might enter 01 and Garnishment/tax levy.
    
    You can optionally create a separate numbered sequence for each type of garnishment or tax levy.

5.  Dependent coverage and beneficiary designations don’t apply to garnishments or tax levies. Therefore, don’t select the **Allow dependent coverage** and **Allow beneficiary designations** check boxes.

Repeat these steps to set up additional benefit options.

To create the garnishment and tax levy benefits that you can enroll workers in, continue with “Create benefits for garnishments and tax levies” in this topic.

Back to top

## 3\. Create benefits for garnishments and tax levies

After you set up the benefit types, plans, and options, you must create the benefits for garnishments and tax levies. If your organization charges administrative fees for garnishments and tax levies, you must also create a benefit for the administrative fees.

When you create a benefit, you link a benefit plan and an option, designate a benefit period, and assign eligibility rules to the benefit.

To create benefits for garnishments and tax levies, follow these steps:

1.  Click **Payroll** \> **Setup** \> **Benefits** \> **Benefits**.

2.  In the **New** group, click **Benefit**.

3.  In the **Create a new benefit** field, select a plan and an option.

4.  Set the **Effective** and **Expiration** date fields to dates that are appropriate for the benefit, and then click **Create benefit**.

5.  On the **Eligibility rules** FastTab, change the eligibility from **All workers are eligible** to **Bypass eligibility process**. The benefit eligibility process is used to control which workers can enroll in a benefit, and when they can enroll. Because there are no limits on who can be enrolled in a garnishment or when they can be enrolled, there is no reason to use the usual benefit eligibility process.
    

    > [!NOTE]
    > <P>When eligibility is set to <STRONG>Bypass eligibility process</STRONG>, eligibility overrides have no effect. You can skip the fields on the <STRONG>Eligibility overrides</STRONG> FastTab.</P>



6.  On the **Payroll details** FastTab, enter the following payroll information. These values are used as the default values when you enroll a worker in the garnishment or tax levy:
    
      - In the **Frequency** field, select a payroll calculation frequency, which determines the pay periods that the selected benefit is calculated in. Most often, garnishments and tax levies use **All**.
    
      - Leave the **Basis** field set to the default value, **Fixed amount**. This causes the payroll process to start with a fixed deduction amount, regardless of the amount of earnings. If necessary, you can change the value to **Percent of earnings** when you enroll a worker in the garnishment or tax levy.
    
      - For garnishment and tax levy benefits, leave the **Amount or rate** field set to 0.0000. The correct amount or rate is set in the **Maintain benefits** form for a specific worker when the worker is enrolled in the garnishment or tax levy.
    
      - For administrative fee benefits, in the **Amount or rate** field, enter the amount of the fee that your organization charges. If you charge different administrative fees under different circumstances, you might want to create separate administrative fee benefits for each fee amount.

7.  On the **Earning basis** FastTab, enter the earning codes that can be included when the basis is **Percent of earnings**. To enter an earning code, click **Add**, and then select the earning code from the list.
    
    The appropriate earning codes typically are determined by your legal department. Don’t enter earning codes if the basis is **Fixed amount**, or if the benefit is for administrative fees.
    

    > [!WARNING]
    > <P>You can’t change the list of earning codes in the <STRONG>Maintain benefits</STRONG> form for a specific worker, but you can change the basis. If you change the basis to <STRONG>Percent of earnings</STRONG>, but no earning codes are entered here, the calculated amount of the deduction for the garnishment or tax levy is 0 (zero).</P>



Repeat these steps to create all the benefits for garnishments, tax levies, and administrative fees.

Back to top

## Next step

The next step is to enroll workers in garnishments and tax levies. For more information, see [Garnishment and tax levy enrollment tasks](garnishment-and-tax-levy-enrollment-tasks.md).

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
<div class="alert">

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

[Benefit elements (form)](https://technet.microsoft.com/library/hh209498\(v=ax.60\))

[Benefits (form)](https://technet.microsoft.com/library/jj680907\(v=ax.60\))

[Maintain benefits (form)](https://technet.microsoft.com/library/hh209235\(v=ax.60\))

## Find related tasks

[Garnishment and tax levy enrollment tasks](garnishment-and-tax-levy-enrollment-tasks.md)

[Benefit setup tasks](benefit-setup-tasks.md)

[Worker and position payroll tasks](worker-and-position-payroll-tasks.md)

  


