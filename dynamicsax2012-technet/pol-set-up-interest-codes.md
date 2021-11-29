---
title: (POL) Set up interest codes
TOCTitle: (POL) Set up interest codes
ms:assetid: 30d7959e-3a20-4ae0-91ce-32b686eccf35
ms:mtpsurl: https://technet.microsoft.com/library/JJ678171(v=AX.60)
ms:contentKeyID: 49386894
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up interest codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up and maintain interest codes. Interest codes contain settings that determine when interest is charged and how it is calculated on overdue accounts.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Interest**.

2.  In the **Interest code** field, enter a unique code to use to calculate interest.

3.  In the **Description** field, enter a description of the interest code.

4.  On the **Earnings** tab, in the **Ledger posting debit** field, select the ledger account number for interest earnings.

5.  On the **Payments** tab, in the **Ledger posting credit** field, select the ledger account number for interest payments.

6.  In the **Grace period** field, enter the number of days after which interest is calculated.
    

    > [!NOTE]
    > <P>The interest is calculated from the payment date.</P>



7.  On the **Earnings** tab and on the **Payments** tab, in the **Monthly interest %**field, enter the tax interest rates.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa577265(v=ax.60)">Interest (form)</A>.</P>



8.  Press CTRL+S or close the form.

## See also

[(POL) Set up the accounts receivable parameters to calculate interest](pol-set-up-the-accounts-receivable-parameters-to-calculate-interest.md)

[(POL) Set up a number sequence code for the interest note and voucher](pol-set-up-a-number-sequence-code-for-the-interest-note-and-voucher.md)

[(POL) Set up customer posting profiles](pol-set-up-customer-posting-profiles.md)

[(POL) Calculate tax interest and free-hand interest](pol-calculate-tax-interest-and-free-hand-interest.md)

[(POL) Post and print an interest note](pol-post-and-print-an-interest-note.md)

[(POL) View the calculated interest](pol-view-the-calculated-interest.md)

  


