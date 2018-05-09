---
title: Generate budget plans from source information
TOCTitle: Generate budget plans from source information
ms:assetid: 10762d52-250d-4403-8d78-083dad9199e3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677325(v=AX.60)
ms:contentKeyID: 49384099
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Generate budget plans from source information 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This procedure explains how to create or update budget plan scenarios by using information from an external source. The external source can be the general ledger, other budget plans, fixed assets, or human resources. The steps are the same, regardless of the source. First, select the source information to use, and then specify the budget planning information to create or update.

1.  Click **Budgeting** \> **Periodic** \> **Budget plan generation** \> **Generate budget plan from general ledger**.
    
    –or–
    
    Click **Budgeting** \> **Periodic** \> **Budget plan generation** \> **Generate budget plan from budget plan**.
    
    –or–
    
    Click **Budgeting** \> **Periodic** \> **Budget plan generation** \> **Generate budget plan from fixed assets**.
    
    –or–
    
    Click **Budgeting** \> **Periodic** \> **Budget plan generation** \> **Generate budget plan from forecast positions**.

2.  In the **Source** section of the form, select the source data from which to generate data for the budget plan. To include advanced criteria as source information, click **Select** to open the inquiry form.

3.  In the **Target** section, enter or select the budget planning process, budget plan, and budget planning scenario to create or update. Then enter or select the other required information, such as the responsibility center to use and the person who prepared the budget plan.

4.  In the **Generation rules** section, enter the rules to use for the budget plan lines: the conversion factor to apply, the minimum amount that is permitted for a budget plan line, and the rounding format to use for the amounts on budget plan lines.

5.  To create or update the budget plan data as a batch process, complete the fields in the **Batch** section. For information about the batch options in this form, and about how to submit a batch processing job, see [Batch tasks (form)](https://technet.microsoft.com/en-us/library/hh209494\(v=ax.60\)) and [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

## See also

[Generate budget plan from general ledger (form)](https://technet.microsoft.com/en-us/library/jj677392\(v=ax.60\))

[Generate budget plan from budget plan (form)](https://technet.microsoft.com/en-us/library/jj677377\(v=ax.60\))

[Generate budget plan from fixed assets (form)](https://technet.microsoft.com/en-us/library/jj710361\(v=ax.60\))

[Generate budget plan from forecast positions (form)](https://technet.microsoft.com/en-us/library/jj677428\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

