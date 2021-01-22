---
title: (CAN) Create sales tax entries for tax on rebates and self-assessments
TOCTitle: (CAN) Create sales tax entries for tax on rebates and self-assessments
ms:assetid: 00a38266-8f4c-4dc8-af78-02dc57790266
ms:mtpsurl: https://technet.microsoft.com/library/Hh242091(v=AX.60)
ms:contentKeyID: 36055917
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Canada
- rebate
- self-assessment
audience: Application User
ms.search.region: Canada
---

# (CAN) Create sales tax entries for tax on rebates and self-assessments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Companies must submit Goods and Services Tax or Harmonized Sales Tax (GST/HST) returns to the Canada Revenue Agency (CRA) based on self-assessment of imported goods. If you import taxable supplies, you must assess the value of the goods, calculate the GST/HST amount due, and submit the total self-assessed amount with your tax return. You can claim any rebates to which you may be entitled from the government by filing manually.

Entries for self-assessed taxes and rebates are recorded in the vendor invoice journal and the general journal using the **Journal voucher** form. Use this procedure to record sales tax transactions for rebates or self-assessments.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.
    
    –or–
    
    Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a new journal.

3.  Click **Lines** to open the **Journal voucher** form.

4.  In the **Account type** field, select **Vendor**.

5.  In the **Account** field, select the account number of the vendor.

6.  In the **Credit** field, enter the amount of the transaction.

7.  In the **Offset account type** field, select **Bank**.

8.  In the **Offset account** field, select the bank account.

9.  Click the **General** tab, and in the **GST/HST** field, select the GST/HST transaction type from the following options:
    
      - **None** – No sales tax transaction is created.
    
      - **Rebates (Line 111)** – A sales tax transaction is created for the transaction type rebate.
    
      - **Tax on acquisition** – A sales tax transaction is created for the transaction type acquisition.
    
      - **Self-assessment (Line 405)** – A sales tax transaction is created based on the self-assessment.

10. Click **Post** \> **Post** to post the journal.

11. Close the forms to save your changes. Click **General ledger** \> **Inquiries** \> **Tax** \> **Posted sales tax**. to view the GST/HST details posted in the purchase order lines, vendor invoice journal, and general journal.

## See also

[(CAN) Set up GST/HST and post a purchase order with tax on acquisition details](can-set-up-gst-hst-and-post-a-purchase-order-with-tax-on-acquisition-details.md)

[Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\))

[Journal voucher - Invoice register (form)](https://technet.microsoft.com/library/aa575517\(v=ax.60\))

  


