---
title: (BRA) Calculate interest and fines on vendor payments
TOCTitle: (BRA) Calculate interest and fines on vendor payments
ms:assetid: 0c31ac33-1a57-44ce-b9fc-34bd1ace0e05
ms:mtpsurl: https://technet.microsoft.com/library/JJ937982(v=AX.60)
ms:contentKeyID: 50950771
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00018
audience: Application User
ms.search.region: Brazil
---

# (BRA) Calculate interest and fines on vendor payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can apply interest and fines on vendor payments that are delayed. The interest and fine amounts that apply to a payment can be calculated when you make a payment to a vendor. Before you calculate interest or fine codes for vendor payments, you must set up a list of bank holidays and national holidays. A holiday date that is set up in the **Payment calendar** form is considered a non-working day. If an invoice is due on a non-working day, the due date moves to the next working day in the calendar, and the interest and fines are calculated accordingly. For more information, see the “Set up a payment calendar and payment calendar rules” section in [(BRA) Set up interest and fines for vendor payments](bra-set-up-interest-and-fines-for-vendor-payments.md). The interest and fine amounts can be calculated in two ways:

  - Automatically calculate the interest and fines – Set up the interest and fine codes to calculate interest automatically, based on the rates and terms that are defined for the codes. You can define a default interest code and fine code for a vendor, and attach the interest code and fine code to purchase orders. For more information, see [(BRA) Interest codes (form)](https://technet.microsoft.com/library/jj933502\(v=ax.60\)) and [(BRA) Fine codes (form)](https://technet.microsoft.com/library/jj933504\(v=ax.60\)). The automatic calculation of interest and fines takes into consideration the interest and fine codes, and the configuration of the payment calendar. For more information, see [About payment calendars](about-payment-calendars.md) and [Payment calendar configuration - vendors and customers (form)](https://technet.microsoft.com/library/jj677400\(v=ax.60\)).

  - Manually enter the interest and fines – Enter the interest and fine amounts on the payment lines, in either the **Settle open transactions** form or the **Vendor payment proposal** form. For more information, see [(BRA) Settle open transactions - vendor (modified form)](https://technet.microsoft.com/library/jj683239\(v=ax.60\)) and [(BRA) Vendor payment proposal - Edit (modified form)](https://technet.microsoft.com/library/jj937995\(v=ax.60\)).

<!-- end list -->

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Click **Lines**.

2.  In the **Account** field, select the vendor account.

3.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

4.  Select the **Mark** check box next to the invoice to mark for payment.

5.  Click the **Payment** tab to calculate the interest and fine amounts. Enter or view the information in the following fields:
    
      - **Interest code** – The interest code for the automatic calculation of interest for the payment line.
    
      - **Interest amount currency** – The interest amount in the payment currency.
    
      - **Interest amount** – The interest amount to charge on the payment line in the transaction currency.
        

        > [!NOTE]
        > <P>You can enter the interest amount manually, or you can use an interest code to calculate it automatically. Interest is calculated only when the date of the payment line in the <STRONG>Journal voucher</STRONG> form is after the due date of the invoice.</P>

    
      - **Fine code** – The fine code for the automatic calculation of the fine on the payment line.
    
      - **Fine amount currency** – The fine amount in the payment currency.
    
      - **Fine amount** – The fine amount to charge on the payment line in the transaction currency.
        

        > [!NOTE]
        > <P>You can enter the fine amount manually, or you can use a fine code to calculate it automatically.</P>



6.  On the **Overview** tab, in the **Interest amount** and **Fine amount** fields, view the interest amount and fine amount to charge on the payment line. Close the **Settle open transactions** form.

7.  Click **Payment proposal** \> **Edit payment proposal** to open the **Vendor payment proposal** form.

8.  Click the **Payment** tab to calculate the interest and fine amounts to charge on the payment line. In the **Interest amount** and **Fine amount** fields, you can modify the interest amount and fine amount.

## See also

[(BRA) Journal voucher - Vendor payment journal (modified form)](https://technet.microsoft.com/library/jj933534\(v=ax.60\))

[(BRA) Create and post a vendor payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-vendor-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[City holiday (form)](https://technet.microsoft.com/library/jj677375\(v=ax.60\))

  


