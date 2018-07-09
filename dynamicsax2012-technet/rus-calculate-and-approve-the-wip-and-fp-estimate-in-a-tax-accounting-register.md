---
title: (RUS) Calculate and approve the WIP and FP estimate in a tax accounting register
TOCTitle: (RUS) Calculate and approve the WIP and FP estimate in a tax accounting register
ms:assetid: 9eb736d6-ea71-49c9-9ada-d2325bd41a11
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923570(v=AX.60)
ms:contentKeyID: 52075415
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Calculate and approve the WIP and FP estimate in a tax accounting register [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you can calculate the value in the estimation of work in process (WIP) and finished products (FP) in the tax accounting register, you must calculate values in the depreciation of fixed assets (FA), the depreciation of intangible assets (IA), deferrals, and income and expenses that do not affect tax base registers. For more information, see [(RUS) Calculate the fixed asset depreciation register](rus-calculate-the-fixed-asset-depreciation-register.md), [(RUS) Calculate the intangible asset depreciation register](rus-calculate-the-intangible-asset-depreciation-register.md), [(RUS) Calculate the deferrals register](rus-calculate-the-deferrals-register.md).

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Select the WIP and FP estimation on the tax accounting journal line.

3.  Click **Lines** to open the **Register journal lines** form. When register journal lines are first created, they have a status of **Not calculated**.

4.  Select the **WIP and FP estimation in tax accounting** journal line.

5.  Click **Calculate all** to calculate all the registers. You can also click **Calculate current** to calculate the selected register.

6.  Click **OK** to confirm the calculation. The status of the register is updated to **Calculated**.
    

    > [!NOTE]
    > <P>To view the details on the register lines after calculation, click <STRONG>Register lines</STRONG>.</P>



7.  Select the **Approved** check box to approve the register.
    

    > [!NOTE]
    > <P>Any additions, modifications, or deletions to register lines must be made before you approve the register.</P>



8.  In the **Worker** field, select the code of the employee who approved the register, if applicable.

9.  Click **Register lines** to view the calculated details. At this point, you can manually add, modify, or delete the register lines that are calculated. For more information, see [(RUS) View register lines](rus-view-register-lines.md) and [(RUS) Adjust data in registers manually](rus-adjust-data-in-registers-manually.md).

10. Click **Print** to print the register details.

## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

[(RUS) Register journal lines (form)](https://technet.microsoft.com/en-us/library/jj839663\(v=ax.60\))

[(RUS) Calculation algorithm for WIP and FP estimation](rus-calculation-algorithm-for-wip-and-fp-estimation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

