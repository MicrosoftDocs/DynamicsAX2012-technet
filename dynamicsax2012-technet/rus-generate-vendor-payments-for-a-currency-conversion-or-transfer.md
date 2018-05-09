---
title: (RUS) Generate vendor payments for a currency conversion or transfer
TOCTitle: (RUS) Generate vendor payments for a currency conversion or transfer
ms:assetid: 17cf8dd5-d64a-44bb-b1a2-f9c4f7a910be
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923257(v=AX.60)
ms:contentKeyID: 52075351
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Generate vendor payments for a currency conversion or transfer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create a currency sale transaction, and you can calculate the exchange adjustment and the profit or loss from the currency conversion during settlement.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines** to open the **Journal voucher** form.

2.  Select the journal line that is created, and then click **Functions** \> **Generate payments** to open the **Generate payments** form.

3.  Select **Export format**, and then, in the **Export format** field, select **Currency transfer order** as the export format to generate payments for the currency sale.

4.  In the **Bank account** field, select the bank account for the payment.

5.  Select the **Show format dialog** check box to review the payment format before you generate the payment.

6.  Click **OK** to open the **Bank currency transfer** form, and then enter the required details.

7.  In the **Transit account** field, select the transit bank account. In the **Vendor account** field, select the account number of the foreign vendor.

8.  In the **Purchase agreement ID** field, select the identification code of the purchase agreement for the vendor.

9.  Click **OK**. The **Payment status** field is updated to **Sent**. The **Transit account**, **Representative**, **Purchase agreement ID**, and **Commission from account** fields are updated on the **Payment** tab in the **Journal voucher** form.

10. Click **Print** \> **Currency sale order** to print the currency sales order. The report contains the following information:
    
      - The currency for the currency conversion
    
      - The identification number of the taxpayer
    
      - The amount of the currency transaction
    
      - The currency code for the currency that is sold
    
      - The transit bank account
    
      - The Bank Identification Code (BIC) for the transit bank

11. In the **Journal voucher** form, click **Validate** \> **Validate** to validate the payment journal.

12. Click **Post** \> **Post** to post the payment journal.

## See also

[(RUS) Journal voucher (form)](https://technet.microsoft.com/en-us/library/jj923409\(v=ax.60\))

[(RUS) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj733511\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

