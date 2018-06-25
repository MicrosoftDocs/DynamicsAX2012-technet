---
title: Export and send VAT recovery returns
TOCTitle: Export and send VAT recovery returns
ms:assetid: 79783c69-fc97-4db0-8732-4bc86cd7c7cf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209260(v=AX.60)
ms:contentKeyID: 36058239
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Export and send VAT recovery returns [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The recovery of Value Added Tax (VAT) is a two-part process. The first part of the recovery process is to identify and verify all expenses that are eligible for recovery and to calculate the total recoverable amount. The second part of the process is to file the VAT returns with all required documentation.

A third-party company is often needed to complete the two parts. Microsoft Dynamics AX can help you complete the first part of this process so that you only have to use the third-party company for filing the VAT returns.

As part of the process, you export VAT information to a Microsoft Excel worksheet. Before you begin the export, verify the following:

  - All expense reports have the required receipts attached.

  - All receipts are issued in the name of your company and not the employee who incurred the expense.

  - The correct sales tax codes have been used.

After all of the VAT information has been exported and the status of the expense transaction is set to ready for recovery, you can begin to file the returns with the local government.

1.  Click **Travel and expense** \> **Common** \> **Expense tax recovery**.

2.  Select **Open** in the **Status** filter and then select the country/region that the taxes are being recovered from.

3.  On the **File** menu, click **Export to Excel**.

The VAT information for the selected transactions is exported to a worksheet in Microsoft Excel. You can attach the worksheet to an e-mail message and send it to the company that is filing the VAT return on your behalf.

## See also

[Create a work item queue](create-a-work-item-queue.md)

[Create a work item queue group](create-a-work-item-queue-group.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

