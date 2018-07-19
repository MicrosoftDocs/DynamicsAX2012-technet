---
title: Check upgrade readiness
TOCTitle: Check upgrade readiness
ms:assetid: 6494b089-f4a7-4e5d-bd14-f46e5dc9a1b5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731817(v=AX.60)
ms:contentKeyID: 35132665
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- upgrade
- preprocessing
- readiness
---

# Check upgrade readiness 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can check upgrade readiness before you begin upgrading data on the Microsoft Dynamics AX source system. The readiness check produces a report that identifies issues that could potentially affect data upgrade. Checks include identifying data that might cause failure of the data upgrade scripts and identifying scenarios that will need extra planning before the upgrade. No changes to data are made during the checks.

The upgrade readiness check is optional, but recommended. Running the readiness check will save time and reduce the number of times you need to run the live or delta preprocessing scripts.

## Run the upgrade readiness check

1.  In the **Preprocessing upgrade checklist**, click **Check upgrade readiness**. The **Upgrade readiness** form opens to display a grid of readiness scripts waiting to be run. The grid provides a description of each script, the method being invoked, the Microsoft Dynamics AX module that the script applies to, and other information.

2.  Click **Run** to begin running the scripts.


> [!TIP]
> <P>By using the batch processing framework, you can set the number of batch server threads available to the upgrade readiness scripts. Adding additional threads up to your processing capacity will speed the completion of the scripts. For more information, see <A href="batch-processing-overview.md">Batch processing overview</A>.</P>



## View readiness results and resolve issues

After the readiness scripts have run, a list of discovered issues is available. To view and resolve these issues, open the **Upgrade validation results** form in either of two ways:

  - Click the **Readiness results** button in the **Upgrade readiness** form.

  - Click the checklist task **View and fix upgrade readiness issues**.

For information about using this form, see [View and fix upgrade readiness issues](view-and-fix-upgrade-readiness-issues.md).

## Rerun the upgrade readiness scripts

After you fix any issues that were identified by the readiness scripts, you can rerun any or all of the failed scripts. Each run of the upgrade readiness scripts results in a new report. You can refer to past readiness reports by selecting one from the **Run date** menu in the **Upgrade validation results** form.

To rerun a single script or multiple scripts when upgrading from Microsoft Dynamics AX 4.0, complete the following procedures that apply:

1.  In the **Upgrade readiness** form, select one or more scripts and click **Rerun job**.

2.  To rerun all readiness scripts, click **Reset status** and then click **Run**.

To rerun a single script or multiple scripts when upgrading from Microsoft Dynamics AX 2009, complete any of the following procedures that apply:

  - In the **Upgrade readiness** form, select one or more scripts and click **Rerun script**.

  - To rerun all failed scripts, click **Rerun all failed scripts**.

  - To rerun all readiness scripts, click **Reset status** and then click **Run**.


> [!IMPORTANT]
> <P>After you resolve issues in the scripts or in the data, you can rerun the readiness check as many times as necessary until the scripts pass validation. Do not attempt an upgrade of your production data until you have identified and resolved all of the upgrade issues flagged by the upgrade readiness check.</P>



## See also

[Upgrade preprocessing scripts (form)](https://technet.microsoft.com/en-us/library/hh202100\(v=ax.60\))

  


