---
title: View and fix upgrade readiness issues
TOCTitle: View and fix upgrade readiness issues
ms:assetid: 67d602e1-7f0b-41f7-831a-5c6686bdd1b1
ms:mtpsurl: https://technet.microsoft.com/library/Hh202065(v=AX.60)
ms:contentKeyID: 35949306
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# View and fix upgrade readiness issues 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **View and fix upgrade readiness issues** task opens the **Upgrade validation results** form. Use the **Upgrade validation results** form as a starting point to resolve issues that are discovered when you used the **Upgrade readiness** form to run the upgrade readiness scripts.


> [!NOTE]
> <P>Resolving upgrade readiness issues helps prevent failure of the upgrade later in the upgrade process.</P>



## Resolve readiness issues

The **Upgrade validation results** form and the **Upgrade validation details** form provide the information and tools that are needed to resolve readiness issues.

1.  In the **Upgrade validation results** form, in the **Validation results** grid, review the scripts that ran. Each script has a status of **Incomplete**, **Pass**, **Error**, or **Advisory**.

2.  Select a job that has a status of **Error** or **Advisory** in the **Validation results** grid to view diagnostic information in the **Log** grid.

3.  For more information about a record that appears in the **Log** grid, click the **Details** button, if it is available.

4.  To fix an issue for a record, click the **Fix** button and then enter any information that is required in the form that opens.
    
    If the **Fix** button is not available, you must either resolve the issue manually or write an upgrade script that resolves the issue. For information about scripts, see the white paper, [How to Write Data Upgrade Scripts for Microsoft Dynamics AX 2012](https://go.microsoft.com/fwlink/?linkid=212587%26clcid=0x409).

  


