---
title: (BRA) Dispose of a CIAP fixed asset
TOCTitle: (BRA) Dispose of a CIAP fixed asset
ms:assetid: 5188bb97-5736-4fab-af5e-7a41dc5c8d0c
ms:mtpsurl: https://technet.microsoft.com/library/Dn305867(v=AX.60)
ms:contentKeyID: 54912967
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Dispose of a CIAP fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When a fixed asset that is tracked through CIAP fiscal books is disposed of by selling or scrapping, the tracking and the fixed asset tax credit accumulation must stop, and the remaining tax credit balance must be printed on a corresponding invoice.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



This information explains how to set up transactions for disposing of assets by selling or scrapping them.

## Dispose a fixed asset

In the **Fixed asset posting profiles** form, on the **Ledger accounts** FastTab, select **Disposal - sale** and **Disposal - scrap** to set up the accounts for posting to the ledger.

For both transaction types, the ledger account is credited for the disposal value of the fixed asset. The debit is posted to an offset account, which might be, for example, a bank account. If a fixed asset is sold to a customer, the customer account is used instead of the offset account.

Click **Disposal** and click **Sale** or **Scrap**, and then set up detailed accounts to reverse the net book value of the fixed asset. You can also enter information in the **Post value** and **Sales value type** fields in the **Disposal parameters** form.

The disposal transaction for an asset in a low-value pool reduces the net book value of the low-value pool by only the disposed amount. However, when the sale of an asset is more than the net book value of the low-value pool, the net book value is reduced to zero.

## Create an invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, on the **Invoice** tab, click **Free text invoice**. For more information, see [(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md).

3.  In the **Free text invoice** form, on the **Action Pane**, on the **Invoice** tab, click **Line view**.

4.  In the **Invoice lines** area, select a free text invoice line, and then click the **Line details** FastTab.

5.  Click the **General** tab, and then in the **Fixed asset number** field, select the ID number of the fixed asset that the free text invoice line is created for.

6.  In the **Invoice lines** area, click **Charges** to open the **Charges transactions** form.

7.  In the **Charges code** field, select the code of the charge that is applied to the selected free text invoice line.

8.  In the **Charges value** field, enter the value that is attached to the category of the charge.

9.  In the **Description** field, update the description of the charges code.

10. In the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and the item sales tax group.

11. On the **Action Pane**, on the **Invoice** tab, click **Fiscal document texts** to open the **Fiscal document text** form, where you can attach fiscal document texts to the invoice. For more information, see[(BRA) Attach fiscal document texts to a free text invoice](bra-attach-fiscal-document-texts-to-a-free-text-invoice.md).
    
    On the **Fiscal document text** form, enter information about the remaining CIAP ICMS tax credit and the number of installments.

## Post an invoice

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the free text invoice for a fixed asset to post.

3.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

4.  Click the **Bill of lading** tab, and then in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity that are used in an invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is not selected on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



5.  Click **OK** to post the free text invoice.

6.  During the booking period process, the fiscal document that contains the CIAP information will record the disposal of the CIAP fixed asset and set the **Status** to **Closed**.

  


