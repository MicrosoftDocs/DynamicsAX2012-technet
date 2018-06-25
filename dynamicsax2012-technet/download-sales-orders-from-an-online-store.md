---
title: Download sales orders from an online store
TOCTitle: Download sales orders from an online store
ms:assetid: 7e220abc-ea57-4769-bf4b-fe8ee75221f7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn631655(v=AX.60)
ms:contentKeyID: 62200106
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- download
- sales orders
- retail
- Classes.RetailSyncOrdersSchedulerJob
- Forms.RetailCDXSchedule
- Online store
- online transactions
---

# Download sales orders from an online store [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to download orders that were entered in an online store to generate sales orders in Microsoft Dynamics AX. When customers place orders for products in your online stores, you must complete the following steps to pull the transactions into Microsoft Dynamics AX to process the orders:

1.  Run the distribution schedule P-job to pull transactions from the online store into Microsoft Dynamics AX.

2.  Run the **Synchronize online orders** process to generate sales orders so that the sales orders can be processed and invoiced, and the products can be picked, packed, and shipped to the customer.

You can run these processes manually or you can set them up as a batch process to run automatically on a regular basis. For more information about how to set up batch processes, see [Batch processing overview](batch-processing-overview.md).


> [!NOTE]
> <P>In AX 2012 R3 with Retail: When orders for physical gift cards are processed from the online store, you must select options in the additional <STRONG>Gift card</STRONG> fields in the <STRONG>Sales order</STRONG> form before you can complete the sales order. Electronic gift cards are processed automatically when the sales order is invoiced. (The <STRONG>Gift card</STRONG> fields are on the <STRONG>Packing</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Sales order</STRONG> form.)</P>



To download sales orders from an online store, follow these steps:

1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.

2.  In the **Distribution schedule** form, do the following:
    
    1.  In the left pane, select the job **P-0001 Channel transactions**.
    
    2.  To run the job manually, click **Run now**.
    
    3.  If you are running this job as a batch, click **Create batch job**. Then, in the dialog box, select the **Batch processing** check box, select a **Batch group**, and then click **OK** to run the job.

3.  Click **Retail** \> **Periodic** \> **Synchronize online orders**.

4.  In the **Synchronize online orders job** form, do one of the following:
    
      - Accept the fields as they appear by default and then click **OK** to run the job.
    
      - If you are running this job as a batch, select the **Batch processing** check box, select a batch group, and then click **OK** to run the job.

5.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. On the **All sales orders** list page, select the sales orders that were downloaded from the online store and process them.
    
    For more information about how to process sales orders, see [Sales orders overview](sales-orders-overview.md).

## See also

[About online stores](about-online-stores.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

