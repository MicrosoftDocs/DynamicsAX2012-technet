---
title: Calculate and post withholding tax
TOCTitle: Calculate and post withholding tax
ms:assetid: c14fe151-bd4b-4e45-b0fa-db5daf534e0d
ms:mtpsurl: https://technet.microsoft.com/library/Aa550675(v=AX.60)
ms:contentKeyID: 36059271
author: tonyafehr
ms.date: 06/20/2014
mtps_version: v=AX.60
f1_keywords:
- calculate withholding tax
- post withholding tax
audience: Application User
ms.search.region: Global
---

# Calculate and post withholding tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can calculate and post withholding tax in the **Payment journal** form in Accounts payable or in the **General journal** form in General ledger. The default withholding tax group of the vendor is displayed in the **Withholding tax group** field.

In the **Payment journal** form, all transactions are considered payments, and the withholding tax setup is always handled as described in the steps earlier in this section.

In the **General journal** form, withholding tax is calculated automatically when the following conditions are true:

  - A vendor account that is set up to calculate withholding tax is selected for the journal line.

  - There is no entry in the **Invoice** field for the selected journal line.

<!-- end list -->

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal or click **New** to create a journal, and then click **Lines**.

3.  Enter a payment date and select the vendor account that is set up to calculate withholding tax.
    
    By default, the **Withholding tax group** field displays the withholding tax group for the vendor. You can select a different group or delete the field value if no withholding tax should be calculated for the line.

4.  Click **Functions** and then click **Settlement**. Select the **Mark** check box for the open invoices to pay.

5.  Verify the Infolog information about the calculated withholding tax and close the Infolog.
    

    > [!NOTE]
    > <P>(GBR) In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3, withholding tax is calculated during the settlement of vendor invoices that are posted using purchase orders, an invoice journal, or an invoice register.</P>



6.  Optional: Click the **Withholding tax** tab for each selected line to change or delete the calculated withholding tax. You can also create lines and enter the information.

7.  Close the **Settle open transactions** form. The payment amount on the journal line is reduced by the withholding tax amount.

8.  Validate and post the payment journal.

## See also

[Set up withholding tax in System administration and General ledger](set-up-withholding-tax-in-system-administration-and-general-ledger.md)

[(Global, AUS, ITA) Set up withholding tax for a vendor](global-aus-ita-set-up-withholding-tax-for-a-vendor.md)

  


