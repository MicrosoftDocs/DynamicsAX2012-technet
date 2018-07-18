---
title: (BRA) Calculate interest and fines on customer payments
TOCTitle: (BRA) Calculate interest and fines on customer payments
ms:assetid: 1067bd2b-cab3-49a6-bdbb-67a0d23ff592
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ937983(v=AX.60)
ms:contentKeyID: 50950772
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00018
audience: Application User
ms.search.region: Brazil
---

# (BRA) Calculate interest and fines on customer payments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can apply interest and fines on customer payments that are delayed. The interest and fine amounts that apply to a payment can be calculated when you receive a payment from a customer. Before you calculate interest or fine codes for customer payments, you must set up a list of bank holidays and national holidays. A holiday date that is set up in the **Payment calendar** form is considered a non-working day. If an invoice is due on a non-working day, the due date moves to the next working day in the calendar, and the interest and fines are calculated accordingly. For more information, see the “Set up a payment calendar and payment calendar rules” section in [(BRA) Set up interest and fines for customer payments](bra-set-up-interest-and-fines-for-customer-payments.md). The interest and fine amounts can be calculated in two ways:

  - Manually enter the interest and fines – Enter the interest and fine amounts on the payment lines, in either the **Settle open transactions** form or the **Customer payment proposal** form. For more information, see [(BRA) Settle open transactions - customer (modified form)](https://technet.microsoft.com/en-us/library/jj937992\(v=ax.60\)) and [(BRA) Customer payment proposal - Edit (modified form)](https://technet.microsoft.com/en-us/library/jj933517\(v=ax.60\)).

  - Automatically calculate the interest and fines – Set up the interest and fine codes to calculate interest automatically, based on the rates and terms that are defined for the codes. You can define a default interest code and fine code for a customer, and attach the interest code and fine code to sales orders. For more information, see [(BRA) Interest codes (form)](https://technet.microsoft.com/en-us/library/jj933502\(v=ax.60\)) and [(BRA) Fine codes (form)](https://technet.microsoft.com/en-us/library/jj933504\(v=ax.60\)). To calculate interest and fine amounts, you must select the interest and fine codes on the payment lines in either the **Settle open transactions** form or the **Customer payment proposal** form. The automatic calculation of interest and fines takes into consideration the interest and fine codes, and the configuration of the payment calendar. For more information see [About payment calendars](about-payment-calendars.md) and [Payment calendar configuration - vendors and customers (form)](https://technet.microsoft.com/en-us/library/jj677400\(v=ax.60\)).

<!-- end list -->

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Select the customer account for which the customer invoice was paid late. Click **Lines**.

2.  In the **Journal voucher** form, click **Edit customer payments**.

3.  In the upper pane, enter customer payment information, if appropriate.

4.  In the lower pane, select the **Mark** check box next to the invoice to mark for payment.

5.  Enter amounts in the **Fine amount** and **Interest amount** fields.

6.  Close the form.

7.  In the **Journal voucher** form, click **Functions** \> **Settlement** to open the **Settle open transactions** form.

8.  Select the **Mark** check box next to the invoice to mark for payment.

9.  On the **Payment** tab, update the information in the following fields to calculate the interest and fine amounts:
    
      - **Fine amount** – The fine amount to charge on the payment line in the transaction currency.
        

        > [!NOTE]
        > <P>You can enter the fine amount manually, or you can use a fine code to calculate it automatically.</P>

    
      - **Fine amount in %1** – The fine amount in the payment currency.
    
      - **Fine code** – The fine code for the automatic calculation of the fine on the payment line.
    
      - **Interest amount** – The interest amount to charge on the payment line in the transaction currency.
        

        > [!NOTE]
        > <P>You can enter the interest amount manually, or you can use an interest code to calculate it automatically. Interest is calculated only when the date of the payment line is after the due date of the invoice in the <STRONG>Journal voucher</STRONG> form.</P>

    
      - **Interest amount in %1** – The interest amount in the payment currency.
    
      - **Interest code** – The interest code for the automatic calculation of interest on the payment line.

10. Close the form.

11. In the **Journal voucher** form, click **Payment proposal** \> **Edit payment proposal** to open the **Customer payment proposal** form.

12. Click the **Payment** tab to calculate the interest and fine amounts to charge on the payment line. In the **Interest amount** and **Fine amount** fields, you can modify the interest amount and fine amount.

## See also

[(BRA) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/en-us/library/jj933499\(v=ax.60\))

[(BRA) Create and post a customer payment journal with a default description for withholding tax, interest, and fine payments](bra-create-and-post-a-customer-payment-journal-with-a-default-description-for-withholding-tax-interest-and-fine-payments.md)

[City holiday (form)](https://technet.microsoft.com/en-us/library/jj677375\(v=ax.60\))

  


