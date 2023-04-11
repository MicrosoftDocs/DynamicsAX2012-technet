---
title: Set up parameters for the Journalized finalized product receipt batch job
TOCTitle: Set up parameters for the Journalized finalized product receipt batch job
ms:assetid: a919e966-c271-4760-b2dd-547fab26a218
ms:mtpsurl: https://technet.microsoft.com/library/JJ841079(v=AX.60)
ms:contentKeyID: 50406238
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up parameters for the Journalized finalized product receipt batch job 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can accrue purchases when a product receipt is entered for a purchase order. When you invoice the product receipt, the accrual is relieved. Because a purchase order can differ from the vendor invoices that it is matched with, a recurring, scheduled batch job is installed for each legal entity. You can use this batch job, **Journalized finalized product receipt**, to clear and journalize any remaining accrual amounts when a product receipt is fully invoiced.

In most cases, there will be no amounts to clear. However, if you accrue purchases, post physical sales tax, and then change the item sales tax group or sales tax group for the purchase order or its matched invoices, the sales tax accrual is not relieved when the product receipt is invoiced. This sales tax accrual is cleared by the **Journalized finalized product receipt** batch job.

You can configure when and where to run this batch job. This configuration includes the number of batch sub-tasks that the batch job can use to process the product receipts that have an accounting event type of **Finalize** and an accounting event status of **Started**.

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Select the **Journalized finalized product receipt** batch job description.

3.  Click **View tasks**.

4.  Click **Parameters**.

5.  Enter the number of runtime batch tasks. The **Journalized finalized product receipt** batch is divided into this number of batch sub-tasks, which are run by any available Application Object Server (AOS) batch server to improve processing efficiency.

6.  Click **OK**.

  


