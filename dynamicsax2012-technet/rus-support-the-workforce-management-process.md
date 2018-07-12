---
title: (RUS) Support the workforce management process
TOCTitle: (RUS) Support the workforce management process
ms:assetid: e699ac0d-728b-4e20-b785-d004911883cc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn502639(v=AX.60)
ms:contentKeyID: 59361494
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- bank
- bank account
- terms of employment
- bank groups
- bank accounts
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- Forms.RHRMWorkerListPage
- bank group
- Forms.RHRMEmployee
- Forms.RHRMPersonBankAccounts
- Forms.RPayParmTable
- kind of work
- seasonal
- seniority
- seniority of an employee
- temporary
- type of seniority
- types of seniorities
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.RHRMOrderTrans
- MsDynAx060.Forms.RHRMWorkerListPage
- MsDynAx060.Forms.RHRMEmployee
- MsDynAx060.Forms.RHRMPersonBankAccounts
- MsDynAx060.Forms.RPayParmTable
audience: Application User
ms.search.region: Russia
---

# (RUS) Support the workforce management process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to support the workforce management process in the following ways:

  - Determine employment terms for an employee to specify the rules of work compensation calculation such as working schedules, form of payments, kinds of labor relation, and seniorities.

  - Transfer the wage payment details of an employee using employee bank details and mode of payment.

## 1\. Define the terms of employment

The employment terms are defined at the hiring stage. You can also change the employment terms during the employment period. You can use the **Employment resolution lines** form to specify whether an employee is a permanent employee or a contractual worker. You can also set up the employee’s working schedule, mode of payment, and bank account by using the **Employees** list page.

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Employment**.

2.  In the **Employment resolutions** form, click **New** to create an employment resolution journal. For more information, see "Hire and assign a new employee for a position" in [(RUS) Hire, transfer, and dismiss a worker](rus-hire-transfer-and-dismiss-a-worker.md).

3.  Click **Lines** to open the **Employment resolution lines** form.

4.  On the **General** tab, in the **Kind of work** field, select one of the following employment types:
    
      - **Permanent** – The terms of employment pertain to fixed working schedules and payment. The agreement for permanent employment is for an unlimited duration.
    
      - **Temporary** – The terms of employment pertain to a fixed time period.
    
      - **On a specific term** – The terms of employment pertain to a fixed contract.
    
      - **Seasonal** – The terms of employment pertain to employees who work only during certain seasons.

5.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee, and then click **Edit**.

6.  In the **Worker** form, in the left pane, click the **Payroll** tab.

7.  In the **Payroll** area, on the **Details** FastTab, in the **Payment form** field, select the code for the payment form. In the **Calendar** field, select the working schedule for the employee.
    
    For more information, see "Create a payment form and assign a list of time codes" and "Create a calendar and copy the schedule" in [(RUS) Configure parameters for time management](rus-configure-parameters-for-time-management.md).

8.  Select the **Salary payment via bank** check box to transfer the salary to the employee through a bank. If you clear this check box, you can pay the salary in cash through the cash office.

9.  Optional: If you selected the **Salary payment via bank** check box, on the **Payroll** tab, click **Bank accounts** to set up a bank account for the employee. You can automate the salary payments to the employee. For more information, see 2. Set up the bank account details of a worker.

## 2\. Set up the bank account details of a worker

You must set up a bank account for employees for payroll and standard deductions payments made though a bank. The bank account information is used in pay sheets and in the standard deduction recipient details. For more information, see [(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md).


> [!NOTE]
> <P>The bank account is defined for a worker and can be used again for payments of any employee instance of this worker.</P>



To set up the bank details of an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee from the list, and then click **Edit**.

2.  On the **Payroll** tab, click **Bank accounts**.

3.  Click **New** to enter a new bank account record.

4.  In the **Bank groups** field, select a bank group that refers to a group of banks.
    

    > [!NOTE]
    > <P>To pay an employee through bank, you should introduce the groups of banks using Cash and bank management.</P>



5.  In the **Bank account number** field, enter the bank account number.

## 3\. Set up the seniority of an employee

The seniority of an employee refers to the period of time that an employee is registered for a service. For example, serving seniority is the period of time that an employee has worked for a company and social insurance seniority is the period of time that an employee is insured in the social fund.

Seniority is nominated in years, months, and days and may affect salary, vacation time, insurance compensation, and other related accruals. For example, you can find the employee's social insurance seniority that is calculated at the start date of the registered sick list in the sick list protocol report.

To set up the seniority of an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Setup** \> **Text fields**. Click **New** to set up a seniority record.

2.  In the **Field** field, enter the seniority type.

3.  In the **Name** field, enter a description of the seniority record.

4.  Click **Payroll (Russia)** \> **Common** \> **Employees**. Select an employee from the worker list, and then click **Edit**.

5.  On the **Text fields** tab, in the **Field** field, select the type of seniority.

6.  In the **Value** field, enter the starting date of the seniority.

7.  On the **Payroll** tab, in the **Seniority** FastTab, select one of the predefined seniority types in the **Seniority of work on a specialty**, **Seniority of work in harmful conditions**, and **Seniority of work in regions of the Far North** fields. This is to mark a particular seniority code as dedicated to a certain type of seniority.

## Next step

[(RUS) Set up competency information for workers and employees](rus-set-up-competency-information-for-workers-and-employees.md)

[(RUS) Record and maintain competency information for workers and employees](rus-record-and-maintain-competency-information-for-workers-and-employees.md)

## Related tasks

[(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md)

[(RUS) Set up payments, journals, and deductions for the payroll process](rus-set-up-payments-journals-and-deductions-for-the-payroll-process.md)

(RUS) Create and calculate standard deductions for borrowing and alimony

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
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p>Compensation and Benefits manager</p></li>
<li><p>Human resources manager</p></li>
<li><p>Payroll assistant</p></li>
</ul>
<p>To manage the workforce process, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
<li><p><strong>Enable project accounting process</strong> (ProjProjectAccountingProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Inquire into workers</strong> (HcmWorkerInquire)</p></li>
<li><p><strong>Maintain audit policies</strong> (ComplianceMgmtAuditPoliciesMaintain)</p></li>
<li><p><strong>Maintain project master</strong> (ProjProjectMasterMaintain)</p></li>
<li><p><strong>Enable human resource process</strong> (HcmHREnable)</p></li>
<li><p><strong>Set up payroll master data</strong> (PayrollMasterDataMaintain)</p></li>
<li><p><strong>Inquire into human resources process</strong> (RPayHumanResourcesProcessInquire)</p></li>
<li><p><strong>Inquire into payroll master data</strong> (PayrollMasterDataInquire)</p></li>
</ul></td>
</tr>
<tr class="odd">
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
<td><p><strong>Edit workers</strong></p></td>
<td><p>HcmWorkerEdit</p></td>
<td><p>Define terms of employment.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain workers</strong></p></td>
<td><p>HcmWorkerMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain contact information</strong></p></td>
<td><p>LogisticsContactInfoMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Create worker employment</strong></p></td>
<td><p>HcmEmploymentNewCreate</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain employment terms</strong></p></td>
<td><p>HcmEmploymentTermMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>HcmWorkerTerminationMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain worker bank accounts</strong></p></td>
<td><p>HcmWorkerBankAccountMaintain</p></td>
<td><p>Set up the bank account details of a worker.</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


