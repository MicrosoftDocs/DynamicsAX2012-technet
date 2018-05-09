---
title: (IND) Reverse service tax
TOCTitle: (IND) Reverse service tax
ms:assetid: abdf7af5-3d71-44e3-b5c9-9548f629ae44
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664785(v=AX.60)
ms:contentKeyID: 49386107
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Reverse service tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use a batch process to reverse service tax credits for vendor transactions. You can reverse service tax credits only for open invoices.

When you reverse service tax by using a batch process, the service tax credit is reversed. The **Point of taxation status** field in the **Vendor transactions** and **Open transactions** forms is updated as follows:

  - If the invoice has not been settled within 90 days, the service tax is fully reversed, and the point of taxation status is **Reversed**.

  - If a partial payment is received within 90 days, the vendor invoice is only partially reversed, and the point of taxation status is **Partially reversed**.

You can also reverse service tax manually for one or more individual vendors. For more information, see [(IND) Manually reverse or reclaim service tax](ind-manually-reverse-or-reclaim-service-tax.md).

## Prerequisites for reversing service tax

  - Service taxes must be enabled. Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Sales tax** area, in the **Apply India taxes** field group, select the **Service tax** check box.

  - Only vendor transactions that have the **Original** point of taxation status are included in the batch process. In the **Vendor transactions** form, on the **General** tab, you can view the point of taxation status in the **Point of taxation status** field. The status is updated automatically by the batch process.

  - Tax reversals must not be blocked for the transactions for which you want to reverse service tax. In the **Vendor transactions** form, on the **General** tab, clear the **Block tax reversal** check box to remove any blocking of tax reversals.

## View transactions where service tax is calculated

You can view transactions where service tax is calculated in the **Point of taxation status** field in the **Vendor transactions** and the **Open transactions** forms.

  - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, in the **Transactions** group, click **Transactions**. On the **General** tab, view the point of taxation status in the **Point of taxation status** field.

  - Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. On the **Action Pane**, on the **Vendor** tab, in the **Transactions** group, click **Transactions**, and then click **Open**. On the **General** tab, view the point of taxation status in the **Point of taxation status** field.

## Reverse service tax by using a batch process

1.  Click **General ledger** \> **Periodic** \> **India** \> **Batch reversal for service tax**.

2.  In the **Unit** field, select the unit of time for which to reverse the service tax. Then, in the **Number of units** field, select the number of units.

3.  On the **Batch** tab, select the **Batch processing** check box.

4.  Click **Recurrence** to define the recurrence of the batch process, and then click **OK**.

## See also

[(IND) Vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664503\(v=ax.60\))

[(IND) Open vendor transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664856\(v=ax.60\))

[(IND) Reclaim service tax](ind-reclaim-service-tax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

