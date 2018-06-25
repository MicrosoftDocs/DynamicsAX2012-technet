---
title: (IND) Manually reverse or reclaim service tax
TOCTitle: (IND) Manually reverse or reclaim service tax
ms:assetid: 1233e7ed-5064-4aef-82ee-651cf6808d10
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664496(v=AX.60)
ms:contentKeyID: 49385576
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# (IND) Manually reverse or reclaim service tax [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can manually reverse or reclaim service tax for one or more vendor accounts. Service tax can be reclaimed and reversed for vendor invoices under the following conditions:

  - If a vendor account has open invoices that have been unpaid for more than three months, you can reverse the service tax credit for the invoices.

  - When invoices for a vendor account have been paid, you can reclaim the service tax credit for the invoices.

You can also set up a batch job to reverse or reclaim service tax for one or more vendors. For more information, see [(IND) Reverse service tax](ind-reverse-service-tax.md) and [(IND) Reclaim service tax](ind-reclaim-service-tax.md).

## Prerequisite

Before you can reverse or reclaim service tax, service tax must be enabled. Click **General ledger** \> **Setup** \> **General ledger parameters**. In the **Sales tax** area, in the **Apply India taxes** field group, select the **Service tax** check box.

## Reverse service tax for open invoices

1.  Click **General ledger** \> **Periodic** \> **India** \> **Post service tax reversal or reclaim**.

2.  In the **Select** field group, specify the following criteria to identify vendor invoices:
    
      - **Vendor account** – To find transactions for a specific vendor, select a vendor account. If this field is blank, all vendor transactions are reversed.
    
      - **Start date** – Specify the start date of the period for which to display transactions.
    
      - **Posting date** – Specify the posting date of the service tax transactions.
    
      - **Invoice** – Select **Open invoices**.

3.  Click **Show data** to display open invoices for the vendor. The point of taxation status for the invoice lines that are displayed is **Original**.
    
    You can then validate the information and select the invoice lines to include. For more details about the information that is displayed for the invoice lines, see [(IND) Vendor invoices with service tax (form)](https://technet.microsoft.com/en-us/library/jj678030\(v=ax.60\)).

4.  The **Select** check box is selected for all invoice lines. Clear this check box to exclude any of the invoice lines.

5.  Click **Reverse service tax**.

## Reclaim service tax for realized invoices

1.  Click **General ledger** \> **Periodic** \> **India** \> **Post service tax reversal or reclaim**.

2.  In the **Select** field group, specify the following criteria to identify vendor invoices:
    
      - **Vendor account** – To find transactions for a specific vendor, select a vendor account. If this field is blank, all vendor transactions are reclaimed.
    
      - **Start date** – Specify the start date of the period for which to display transactions.
    
      - **Posting date** – Specify the posting date of the service tax transactions.
    
      - **Invoice** – Select **Realized invoices**.

3.  Click **Show data** to display realized invoices for the vendor, which are invoices that have been paid. The point of taxation status for the invoice lines that are displayed is **Reversed**, **Partially reversed**, or **Partially reclaimed**.
    
    You can then validate the information and select the invoice lines to include. For more details about the information that is displayed for the invoice lines, see [(IND) Vendor invoices with service tax (form)](https://technet.microsoft.com/en-us/library/jj678030\(v=ax.60\)).

4.  The **Select** check box is selected for all invoice lines. Clear this check box to exclude any of the invoice lines.

5.  Click **Reclaim service tax**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

