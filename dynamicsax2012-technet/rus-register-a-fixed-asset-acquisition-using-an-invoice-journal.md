---
title: (RUS) Register a fixed asset acquisition using an invoice journal
TOCTitle: (RUS) Register a fixed asset acquisition using an invoice journal
ms:assetid: 34bbdc29-e838-45cf-bcda-2b590cf36e4a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665269(v=AX.60)
ms:contentKeyID: 49387358
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Register a fixed asset acquisition using an invoice journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can record the purchase of a fixed asset with the vendor invoice journal if the fixed asset is not a warehouse item, and if it does not incur receipt and issue transactions that must be tracked.


> [!NOTE]
> <P>Before you purchase a fixed asset, the asset must be registered in the <STRONG>Fixed assets</STRONG> form.</P>



1.  Click **Fixed assets (Russia)** \> **Common** \> **Fixed assets**. On the **Action pane**, click **Fixed asset** to create a fixed asset, or select a fixed asset record.

2.  Press CTRL+N to create a fixed asset with a **Scheduled** status.
    

    > [!NOTE]
    > <P>.</P>



3.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

4.  Press CTRL+N to create a new journal.

5.  In the **Name** field, select the journal name.

6.  Click **Lines** to open the **Journal voucher** form.

7.  Press CTRL+N to create a new line.
    

    > [!NOTE]
    > <P>The posting date and voucher number are displayed in the <STRONG>Date</STRONG> and <STRONG>Voucher</STRONG> fields.</P>



8.  In the **Account type** field, select the account type.
    

    > [!NOTE]
    > <P><STRONG>Vendor</STRONG> is displayed by default.</P>



9.  In the **Account** field, select a vendor code.

10. In the **Invoice** field, enter the invoice number for the fixed asset purchase.

11. In the **Description** field, enter any notes about the invoice.

12. In the **Credit** field, enter the invoice amount.

13. In the **Offset account type** field, select the account type for the current account.
    

    > [!NOTE]
    > <P><STRONG>Ledger</STRONG> is displayed by default.</P>



14. In the **Offset account** field, select the ledger account for the fixed asset before acquisition.

15. Click the **General** tab.

16. In the **Currency** field, select the current invoice currency.

17. In the **FA number** field, select the fixed asset number.

18. Click **Post** \> **Post** to generate the vendor and ledger transactions.
    

    > [!NOTE]
    > <P>The invoice details are displayed in the <STRONG>Fixed assets</STRONG> form. In the <STRONG>Status</STRONG> field, the status is displayed as <STRONG>Bought</STRONG>. If the fixed asset number is specified in the invoice journal line, then the invoice journal must be posted or deleted in order to create an asset or inventory transaction.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

