---
title: (IND) Reclaim service tax
TOCTitle: (IND) Reclaim service tax
ms:assetid: 4e430b4f-631b-40f8-8d42-c25b6ccdb285
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664686(v=AX.60)
ms:contentKeyID: 49385759
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Reclaim service tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use a batch process to reclaim the service tax credits for vendor transactions. You can reclaim services tax credits only for invoices that have been settled.

When you reclaim service tax by using a batch process, the service tax credit is reclaimed. The **Point of taxation status** field in the **Vendor transactions** and the **Open transactions** forms is updated as follows:

  - If the invoice is fully settled, the service tax is fully reclaimed, and the point of taxation status is **Reclaimed**.

  - If the invoice is only partially paid, the service tax is partially reclaimed, and the point of taxation status is **Partially reclaimed**.

You can also reclaim service tax manually for one or more vendors. For more information, see [(IND) Manually reverse or reclaim service tax](ind-manually-reverse-or-reclaim-service-tax.md).

## Prerequisites for reclaiming service tax

  - Services taxes must be enabled. Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Sales tax** area, in the **Apply India taxes** field group, select the **Service tax** check box.

  - Only vendor transactions that have a point of taxation status of **Reversed**, **Partially reversed**, or **Partially reclaimed** are included in the batch process. In the **Vendor transactions** form, on the **General** tab, you can view the point of taxation status in the **Point of taxation status** field. The status is updated automatically by the batch process.

## View transactions where service tax is calculated

You can view transactions where service tax is calculated in the **Point of taxation status** field in the **Vendor transactions** and the **Open transactions** forms.

  - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, in the **Transactions** group, click **Transactions**. On the **General** tab, view the point of taxation status in the **Point of taxation status** field.

  - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, in the **Transactions** group, click **Transactions**, and then click **Open**. On the **General** tab, view the point of taxation status in the **Point of taxation status** field.

## Reclaim service tax by using a batch process

1.  Click **General ledger** \> **Periodic** \> **India** \> **Batch reclaim for service tax**.

2.  On the **Batch** tab, select the **Batch processing** check box.

3.  Click **Recurrence** to define the recurrence of the batch process, and then click **OK**.

## See also

[(IND) Vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664503\(v=ax.60\))

[(IND) Open vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664856\(v=ax.60\))

[(IND) Reverse service tax](ind-reverse-service-tax.md)

  


