---
title: (EEUR) Create a cash order by using a slip journal
TOCTitle: (EEUR) Create a cash order by using a slip journal
ms:assetid: 39bbd418-fbb5-4526-93ca-92cc900e6f0d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677504(v=AX.60)
ms:contentKeyID: 49384807
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cash order
- create slip journal
- slip journal
- voucher slip journal
---

# (EEUR) Create a cash order by using a slip journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use a slip journal to create a cash order and register incoming and outgoing cash transactions to cash accounts.

1.  Click **Cash and bank management** \> **Journals** \> **Slip journal**.

2.  Click **New** to create a line, and then enter the required details. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)).

3.  Click **Lines** to open the **Journal voucher** form, click **New** to create a line, and then enter the required details. For more information, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

4.  In the **Offset account type** field, select **Bank**.

5.  Click the **Cash order** tab.

6.  In the **Representative type** field, select **Other**.

7.  In the **Representative** field, select the employee code of the customer or vendor. The employee name is displayed in the **Employee name** field.

8.  Click **Documents approval** \> **Approve** to approve the slip journal.

9.  Click **Post** \> **Post** to post the slip journal. The cash report is created.

10. Optional: To print the cash report, click **Print** \> **Cash report** in the **Journal voucher** form, and then click **Select** to set up the selection criteria.

11. Click **OK** to print the cash report.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

