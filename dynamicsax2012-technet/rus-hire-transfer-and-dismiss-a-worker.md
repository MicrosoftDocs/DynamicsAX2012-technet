---
title: (RUS) Hire, transfer, and dismiss a worker
TOCTitle: (RUS) Hire, transfer, and dismiss a worker
ms:assetid: 94fa02a8-4f93-4e90-8efd-e27af9e73781
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn435991(v=AX.60)
ms:contentKeyID: 56732191
ms.date: 07/02/2014
mtps_version: v=AX.60
f1_keywords:
- dismiss
- resolution
- transfer
- Forms.SysQueryForm
- Forms.GlobalAddressBookListPage
- contract
- reason code
- Forms.OfficialsTable_RU
- Forms.RHRMOrderTable
- Forms.RHRMOrderTrans
- Forms.RHRMWorkerListPage
- Forms.RPaySumEmpl
- civil
- civil contract
- dismissal resolution
- employment resolution
- Forms.RHRMStaffList
- Forms.RHRMStaffListTotal
- Forms.RHRMVirtualNetworkDismiss
- Forms.RHRMVirtualNetworkEmploy
- Forms.RHRMVirtualNetworkHistoryLine
- Forms.RHRMVirtualNetworkMove
- Forms.RPayCivilContracts
- Forms.RPayCivilContractType
- Forms.RPaySumModule
- hire
- transfer resolution
- MsDynAx060.Forms.OfficialsTable_RU
- MsDynAx060.Forms.SysQueryForm
- MsDynAx060.Forms.RHRMOrderTable
- MsDynAx060.Forms.GlobalAddressBookListPage
- MsDynAx060.Forms.RHRMOrderTrans
- MsDynAx060.Forms.RHRMStaffList
- MsDynAx060.Forms.RHRMVirtualNetworkEmploy
- MsDynAx060.Forms.RHRMStaffListTotal
- MsDynAx060.Forms.RHRMVirtualNetworkDismiss
- MsDynAx060.Forms.RHRMVirtualNetworkMove
- MsDynAx060.Forms.RPaySumModule
- MsDynAx060.Forms.RPayCivilContracts
- MsDynAx060.Forms.RPaySumEmpl
- MsDynAx060.Forms.RPayCivilContractType
- MsDynAx060.Forms.RHRMVirtualNetworkHistoryLine
- MsDynAx060.Forms.RHRMWorkerListPage
audience: Application User
ms.search.region: Russia
---

# (RUS) Hire, transfer, and dismiss a worker 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to hire an employee, transfer an employee to a position, and dismiss an employee from a position. You can hire or transfer an employee for full-time employment or for contractual employment. Payroll is calculated based on employment type. You can also employ a person as a civil contract worker.

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
<th><p>Prerequisites</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R2 Payroll for Russia Feature Pack</p></td>
</tr>
<tr class="even">
<td><p>Country/region</p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Configuration task</p></td>
<td><ul>
<li><p>Make sure that the required position is created in the company that the employee is hired for. For more information, see <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a> and <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a>.</p></li>
<li><p>Make sure that the payment forms and calendars are created and assigned to employees. For more information, see <a href="rus-configure-parameters-for-time-management.md">(RUS) Configure parameters for time management</a>.</p></li>
<li><p>Make sure that the organizational structure and scale of charges are set up. For more information, see <a href="rus-configure-organizational-information.md">(RUS) Configure organizational information</a> and <a href="rus-set-up-employee-compensation-parameters.md">(RUS) Set up employee compensation parameters</a>.</p></li>
<li><p>Make sure that a worker has been created for a person registered in the <strong>Global address book</strong>. For more information, see <a href="rus-create-a-worker.md">(RUS) Create a worker</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Hire and assign a new employee for a position

An employment resolution is the document that confirms the relationship between a company as an employer and a physical person as an employee. This relationship is established in accordance with a labor agreement.

To hire an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Employment**.

2.  In the **Employment resolutions** form, click **New** to create a new recruiting journal.

3.  In the **Name** field, select **Recruiting**.

4.  In the **Resolution date** field, enter the date on which to create the employment resolutions.

5.  On the **Reason** tab, enter the reason to create the employment resolution.

6.  Click **Lines** to open the **Employment resolution lines** form.

7.  Click **New** to create an employment resolution line. In the **Employee** field, select an employee to be hired.
    

    > [!NOTE]
    > <P>You can register employees in the <STRONG>Employees</STRONG> form before hiring them.</P>



8.  To select the budgeted department and position for the employee in the **Organization** field, select the **By staff list** check box.

9.  Clear the **By staff list** check box to select the department and position separately in the **Organization** and **Position** fields, which are not included in the staff list structure.

10. In the **Start date** field, enter the starting date for the employee.

11. In the **End date** field, enter the ending date for the employee if the employee is hired for a temporary period.

12. You can use the fields on the **General** tab that are described in the table below to enter the details of the employee.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Employment</strong></p></td>
    <td><p>Select the rate value for full-time employment or contractual employment of an employee for the payroll calculation. For more information about rate and rate values, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Salary</strong></p></td>
    <td><p>The salary amount is displayed with the value that is specified for the position in the <strong>Organizational chart</strong> form, if the employee is hired after the approval of the staff list to a position that is configured to use scale of charges. You cannot modify the salary amount in this case. If this employee is assigned to a different budgeted position that is configured to use salary as a value, in the <strong>Salary</strong> field, the maximum salary amount is displayed with the value that is specified for the position in the <strong>Organizational chart</strong> form. You can also modify the salary amount, if necessary.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document date</strong></p></td>
    <td><p>Enter the employment contract date.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document number</strong></p></td>
    <td><p>Enter the employment contract number.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Kind of work</strong></p></td>
    <td><p>Select <strong>Permanent</strong>, <strong>Temporary</strong>, <strong>On a specific term</strong>, or <strong>Seasonal</strong> as the employment type.</p></td>
    </tr>
    </tbody>
    </table>


13. Click **Validate** to validate the resolution lines.

14. Click **Post** to post the journal.

15. Optional: In the **Timesheet generation** dialog box, click **Yes** to update the timesheet. For more information about timesheets, see [(RUS) Create a timesheet for an employee](rus-create-a-timesheet-for-an-employee.md).

16. Click **Close** to close the **Employment resolution lines** form. You can verify the following information:
    
      - A new record is generated in the **History** form.
    
      - In the **Organizational chart** form, click **Total** to verify the reduction of **Vacant** positions.

17. Click **Restore** to reverse the changes that you have made in the employee details in the **Employment resolutions** form.
    

    > [!NOTE]
    > <P>You can restore a resolution journal only if the payroll transaction is not created for the hired employee and if there are no other resolutions already posted for this employee. For example, if you hire and post an employee to position A, and then make a change to hire the same employee to a different department, you can restore the first recruitment resolution only after you have restored the second recruitment resolution.</P>



18. Click **Print** \> **Form T-1a** to print the employment resolution for all employees from the employment resolution journal or **Print** \> **Form T-1** to print the employment resolution for an employee from a single resolution line. For more information, see [(RUS) Staff administration reports](rus-staff-administration-reports.md).

19. Optional: If the hired employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the already created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Alternative method: Hire an employee by using the Employees form

If you are a staff administrator you can hire one employee at a time by using the **Employees** form. Follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select the worker record, and then click **Hire** to open the **Hire the employee** form.

3.  Enter the necessary details on the **Resolution** tab and the **Agreement** tab.

4.  Click **OK** to hire the employee.

5.  Optional: If the hired employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the previously created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## 2\. Maintain civil contracts

You can create and manage civil contracts in the **Civil contracts** form. You can employ a person as a civil contract worker based on rules that are regulated by the Civil code. Civil contract workers are not hired permanently by the company, and their working period is for the agreed time period that is specified in the signed agreement. You do not need to specify payment form codes and working schedules when you hire employees for civil contracts. You can set up contract groups, and for each contract group you can configure specific methods of compensation calculation. You can also select a particular insurance seniority code for each contract group. You can register a contract using one of these groups that specifies the agreement attributes, such as the code, date of signing, duration, and compensations for the contract. You can also print the contract details and the Acts of acceptance report. The work that is completed according to the contract can be registered and marked as work that is related to the contract acts. The registered act contains the amount of the compensation that can be included in the current payroll to calculate the compensation as part of the employee salary.

## Set up a contract group

To set up a contract group for a civil contract worker, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Civil contracts** \> **Setup** \> **Contract groups**.

2.  In the **Contracts group** field, enter the contract group code.

3.  In the **Insurance seniority type** field, select the seniority code to be used in the personified report that is submitted to the pension fund.

4.  On the **General** FastTab, in the **Sequence** field, select a calculation sequence for the payroll calculation.

5.  In the **Number sequences** FastTab, in the **Reference** field, select a number sequence reference for the contract group.

## Set up a civil contract

To set up a civil contract, follow these steps:

1.  Click **Payroll (Russia)** \> **Calculation procedures** \> **Civil contracts** \> **Civil contracts**. Click **New** to create a contract.

2.  On the **Contract list** tab, in the **Contracts group** field, select a contract group code.

3.  In the **Contract number** and **Contract date** fields, enter the contract number and the date of contract.

4.  In the **Employee** field, select the employee code.

5.  On the **General** tab, in the **Start date** and **End date** fields, select the starting date and ending date for the work.

6.  In the **Representative** field, select the name of the company representative that you set up in the **Officials** form.

7.  In the **Amount** field, enter the contract amount.

8.  In the **Account type** field, select the account type.

9.  In the **Account** field, select the value and the appropriate dimensions of the account.

10. On the **Work compound** tab, enter the reason for the contract in the **Work compound** field.

11. Click **Payroll lines** to view the calculated payroll lines for all transactions related to the contract.

12. Click **Print contract** to print the contract.

13. In the lower pane, click **New** to create the Acts of acceptance report for the contract.

14. In the **Account type** field, select the account type.

15. In the **Account** field, select the value and the appropriate dimensions of the account.

16. In the **Act date** field, select the date when the civil act is signed.

17. In the **Statement number** field, enter a number for the new statement.

18. In the **Amount** field, enter the amount to be paid to the employee.

19. Select the **Add to salary** check box to include benefits and additional compensation in the current calculation period.

20. On the **Work compound** tab, enter the reason that the act is signed in the **Compound of completed work** field.

21. Click **Payroll lines** after selecting an act to view the calculated payroll lines for the current act of the contract.

22. In the **Civil contracts** form, click **Calculation** to do the payroll calculation for a civil contract employee.

23. In the **Payments and deductions registration** form, click **Calculation** to view the payment amount that is paid to the civil contract worker for the specified calculation period.

24. Click **Print act** to print the Acts of acceptance report.

25. Click **Adjust storno** to reverse a transaction that is created for the current contract.

## 3\. Transfer an employee

You can create and post a transfer resolution to transfer the employees to a different division, position, or to change the employment terms like basic pay. You can also create a multiline transfer resolution.

To transfer an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Transfer**.

2.  In the **Transfer resolutions** form, click **New** to create a new transfer journal.

3.  In the **Name** field, select a journal code that is specified in the **Parameters** form for transfer resolution journals.
    

    > [!NOTE]
    > <P>The journal code is created in the <STRONG>Journal names</STRONG> form.</P>



4.  In the **Resolution date** field, enter the date to create the transfer resolutions.

5.  Click **Lines** to open the **Transfer resolution lines** form.

6.  Click **New** to create a new transfer resolution line.

7.  In the **Employee** field, select the employee that you want to transfer.

8.  Select the **By staff list** check box to indicate that the employee is transferred from one part of the staff list structure to another.

9.  To select the budgeted department and position for the employee who is transferred in the **Organization** field, select the **By staff list** check box.

10. Clear the **By staff list** check box to select the department and position separately in the **Organization** and **Position** fields, which are not included in the staff list structure.

11. In the **Start date** field, enter the starting date of the employment.

12. In the **End date** field, enter the ending date of the employment if the employee is transferred for a temporary period.

13. You can use the fields on the **General** tab that are described in the table below to enter the details of the transferred employee.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Employment</strong></p></td>
    <td><p>Select the rate value for full time employment or contractual employment for the payroll calculation. For more information about rates and rate values, see <a href="rus-set-up-parameters-for-the-payroll-process.md">(RUS) Set up parameters for the payroll process</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Salary</strong></p></td>
    <td><p>The salary amount is displayed with the value that is specified for the position in the <strong>Organizational chart</strong> form, if the employee is hired after the approval of the staff list to a position that is configured to use the scale of charges. You cannot modify the salary amount in this case. If this employee is assigned to a different budgeted position that is configured to use salary as a value, in the <strong>Salary</strong> field, the maximum salary amount is displayed with the value that is specified for the position in the <strong>Organizational chart</strong> form. You can also modify the salary amount, if necessary.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Code</strong></p></td>
    <td><p>Select the scale of charges code for the position. Scale of charges is used to create a directory of pay scales in an organization.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Grade</strong></p></td>
    <td><p>Select the category for the position.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Document number</strong></p></td>
    <td><p>Enter the document number that has the changes to the employment contract.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document date</strong></p></td>
    <td><p>Enter the document date on which the employment is changed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Transfer type</strong></p></td>
    <td><p>Select the type of transfer for the employee.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reason code</strong></p></td>
    <td><p>Select the reason code for the employee transfer.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Change of salary of position</strong></p></td>
    <td><p>Select this check box if the transfer resolution is created in connection with a change to the salary rate for a position.</p></td>
    </tr>
    </tbody>
    </table>


14. Click **Validate** to validate the resolution journal lines.

15. Click **Post** to post the resolution journal.

16. Optional: If an employee is transferred from one department to another, separate timesheets are updated for each department after the timesheet is updated using the **Timesheet generation** dialog box.

17. Click **OK** to confirm a transfer resolution. The following actions take place in Microsoft Dynamics AX:
    
      - A new record is generated in the **History** form.
    
      - In the **Organizational chart** form, click **Total** to verify the **Vacant** and **Occupied** positions.

18. Click **Restore** to reverse the changes that you have made in the **Transfer resolutions** form.

19. Click **Print** \> **Form T-5a** to print the transfer resolution for all employees from this resolution journal or **Print** \> **Form T-5** to print the transfer resolution for an employee from a single resolution line. For more information, see [(RUS) Staff administration reports](rus-staff-administration-reports.md).

20. Optional: If the transferred employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the previously created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Alternative method: Transfer an employee by using the Employees form

You can use the **Employees** form to create a transfer resolution for one employee at a time.

To transfer an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select the worker record, and then click **Move** to open the **Transfer of the employee onto other work** form.

3.  Enter the necessary details on the **Resolution** tab and the **Changes** tab.

4.  Click **OK** to transfer the employee.

5.  Optional: If the transferred employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the previously created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## 4\. Dismiss an employee

You can use the **Dismissal resolutions** form to create and post a dismissal resolution.

To dismiss an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Staff administration** \> **Resolution journals** \> **Dismissal**.

2.  In the **Dismissal resolutions** form, click **New** to create a new dismissal resolution journal.

3.  In the **Name** field, select the journal code that is specified in the **Parameters** form for dismissal resolution journals.

4.  In the **Resolution date** field, enter the dismissal resolutions date.

5.  Click **Lines** to open the **Dismissal resolution lines** form.

6.  Click **New** to create a new dismissal resolution line.

7.  In the **Employee** field, select an employee to dismiss.

8.  In the **Date of dismissal** field, enter the last working day of the employee.

9.  You can use the fields on the **General** tab that are described in the table below to enter the details of the employee dismissal.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Fields</p></th>
    <th><p>Purpose</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Reason code</strong></p></td>
    <td><p>Select the reason code for the dismissal. These codes are statutory defined in the labor code, and configured in the related list of codes.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Contract date</strong></p></td>
    <td><p>Enter the trade union decision document date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Agreement number</strong></p></td>
    <td><p>Enter the trade union decision document number.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document code</strong></p></td>
    <td><p>Select the dismissal reason document code. For more information, see &quot;Create document arguments&quot; in <a href="rus-configure-staff-administration-information-for-workers.md">(RUS) Configure staff administration information for workers</a>.</p></td>
    </tr>
    </tbody>
    </table>


10. Click **Validate** to validate the resolution line.

11. Click **Post** to post the journal.

12. Optional: You can update the timesheet if the employee is dismissed before the end date that is specified in the timesheet using the **Timesheet generation** dialog box.

13. Click **OK** to confirm the dismissal resolution. You can verify the following details:
    
      - A new record is generated in the **History** form.
    
      - In the **Organizational chart** form, click **Total** to verify the **Vacant** position.

14. Click **Restore** to reverse the changes that you have made in the **Dismissal resolutions** form.

15. Click **Print** \> **Form T-8a** to print the dismissal resolution for all employees from this resolution journal or **Print** \> **Form T-8** to print the dismissal resolution for an employee from a single resolution line. For more information, see [(RUS) Staff administration reports](rus-staff-administration-reports.md).
    

    > [!NOTE]
    > <P>At the time of dismissal, vacation compensation registration can be performed if an employee has non-zero balance of earned vacation days. For more information, see (RUS) Register vacations, business trips, and calculate compensation.</P>



16. Optional: If the dismissed employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the previously created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Alternative method: Dismiss an employee by using the Employees form

You can use the **Employees** form to dismiss one employee at a time.

To dismiss an employee, follow these steps:

1.  Click **Payroll (Russia)** \> **Common** \> **Employees**.

2.  Select the worker record, and then click **Dismiss** to open the **Dismiss the employee** form.

3.  Enter the necessary details on the **Resolution** tab and the **Reason** tab.

4.  Click **OK** to dismiss the employee.

5.  Optional: If the dismissed employee is paid based on the working schedule, click **Yes** in the **Timesheet generation** dialog box to update the previously created timesheet. For more information, see [(RUS) Generate pay statements](rus-generate-pay-statements.md).

## Next step

[(RUS) Support the workforce management process](rus-support-the-workforce-management-process.md)

## Related tasks

[(RUS) Set up employee compensation parameters](rus-set-up-employee-compensation-parameters.md)

[(RUS) Set up calculation procedures for the payroll process](rus-set-up-calculation-procedures-for-the-payroll-process.md)

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
<li><p><strong>Human Resources administrator</strong></p></li>
<li><p><strong>Recruiter</strong></p></li>
<li><p><strong>Payroll administrator</strong></p></li>
</ul>
<p>To hire, transfer, or dismiss a worker, you must be a member of a security role that includes the following duties:</p>
<ul>
<li><p><strong>Enable workforce management process</strong> (HcmWorkforceProcessEnable)</p></li>
<li><p><strong>Inquire into workforce management process</strong> (HcmWorkforceProcessInquire)</p></li>
<li><p><strong>Enable project accounting process</strong> (ProjProjectAccountingProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitInquire)</p></li>
<li><p><strong>Inquire into payroll position and worker setup</strong> (PayrollPositionWorkerSetupInquire)</p></li>
<li><p><strong>Inquire into workers</strong> (HcmWorkerInquire)</p></li>
<li><p><strong>Maintain audit policies</strong> (ComplianceMgmtAuditPoliciesMaintain)</p></li>
<li><p><strong>Maintain project master</strong> (ProjProjectMasterMaintain)</p></li>
<li><p><strong>Enable payroll process</strong> (HcmPayrollProcessEnable)</p></li>
<li><p><strong>Inquire into benefits process</strong> (HcmBenefitProcessInquire)</p></li>
<li><p><strong>Enable benefits process</strong> (HcmBenefitProcessEnable)</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To hire, transfer, or dismiss a worker, you must be a member of a security role that includes the privileges that are described in the following table.</p>
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
<td><p><strong>Create worker employment</strong></p></td>
<td><p>HCMEmploymentNewcreate</p></td>
<td><p>Hire and assign a new employee for a position.</p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain worker assignments for positions</strong></p></td>
<td><p>HcmPositionWorkerAssignmentMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>View positions</strong></p></td>
<td><p>HcmPositionView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View employment history</strong></p></td>
<td><p>HcmEmploymentHistoryView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Maintain employment terms</strong></p></td>
<td><p>HcmEmploymentTermMaintain</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Maintain worker assignments for positions</strong></p></td>
<td><p>HcmPositionWorkerAssignmentMaintain</p></td>
<td><p>Transfer an employee.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View employment terms</strong></p></td>
<td><p>HcmEmploymentTermView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>View positions</strong></p></td>
<td><p>HcmPositionView</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>View employment history</strong></p></td>
<td><p>HcmEmploymentHistoryView</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Terminate a worker</strong></p></td>
<td><p>HCMWorkerTerminationMaintain</p></td>
<td><p>Dismiss an employee.</p></td>
</tr>
<tr class="odd">
<td><p><strong>View employment history</strong></p></td>
<td><p>HcmEmploymentHistoryView</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


