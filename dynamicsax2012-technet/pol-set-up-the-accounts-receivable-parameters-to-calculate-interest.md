---
title: (POL) Set up the accounts receivable parameters to calculate interest
TOCTitle: (POL) Set up the accounts receivable parameters to calculate interest
ms:assetid: 9a412380-af50-4b06-9a74-5cf1fdb2109e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678309(v=AX.60)
ms:contentKeyID: 49387031
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up the accounts receivable parameters to calculate interest 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Poland, two types of interest rates are used:

  - Tax interest rates, also referred to as statutory interest rates, which are specified by the Ministry of Finance.

  - Free-hand interest rates, which are negotiated between the vendor and the customer.


> [!NOTE]
> <P>Free-hand interest may or may not be calculated, based on the agreement between the customer and the vendor. However, tax interest calculation is mandatory.</P>



Generally, the vendor sets the settlement period of no longer than 30 days. However, the following situations can arise:

  - If the vendor and customer agree on a settlement period longer than 30 days or if the settlement period is not set, then free-hand interest can be calculated from the 31st day until the due date. Alternatively, tax interest can be calculated until the date of payment.

  - If the settlement period is less than 30 days, the vendor can calculate tax interest from the due date until the date of payment.

You can define the parameters for interest calculation in **Accounts receivable parameters** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Collections**. In the **Interest calculation** field, select the transactions for which interest is to be calculated.

3.  Press CTRL+S or close the form.

## See also

[(POL) Set up customer posting profiles](pol-set-up-customer-posting-profiles.md)

[(POL) Set up interest codes](pol-set-up-interest-codes.md)

[(POL) Set up a number sequence code for the interest note and voucher](pol-set-up-a-number-sequence-code-for-the-interest-note-and-voucher.md)

[(POL) Calculate tax interest and free-hand interest](pol-calculate-tax-interest-and-free-hand-interest.md)

[(POL) Post and print an interest note](pol-post-and-print-an-interest-note.md)

[(POL) View the calculated interest](pol-view-the-calculated-interest.md)

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678183\(v=ax.60\))

  


