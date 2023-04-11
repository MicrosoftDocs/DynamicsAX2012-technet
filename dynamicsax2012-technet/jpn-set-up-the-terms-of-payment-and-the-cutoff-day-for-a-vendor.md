---
title: (JPN) Set up the terms of payment and the cutoff day for a vendor
TOCTitle: (JPN) Set up the terms of payment and the cutoff day for a vendor
ms:assetid: 5b57da09-9b75-44b1-8e4d-875295b2130f
ms:mtpsurl: https://technet.microsoft.com/library/JJ711058(v=AX.60)
ms:contentKeyID: 49386469
author: tonyafehr
ms.date: 01/21/2017
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up the terms of payment and the cutoff day for a vendor 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Terms of payment** form to set up the cutoff day and payment day for a vendor. For more information, see [(JPN) Terms of payment (modified form)](https://technet.microsoft.com/library/jj711223\(v=ax.60\)).

You can set up a cutoff day in the **Terms of payment** form to calculate the due date for a vendor based on the payment days that you have defined by using the **Payment days** form. For more information, see [Payment days (form)](https://technet.microsoft.com/library/aa553269\(v=ax.60\)).

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Terms of payment**.

2.  Set up terms of payment.

3.  In the **Payment method** field, select **Cutoff day** as the payment method.

4.  In the **Payment day** field, select the payment day to use to calculate the due date.

5.  In the **Cutoff day** field, enter a numeric value from 1 to 31 to set the cutoff date. If the last day of the month falls on a date that has a number that is less than the numeric value that you have specified, the invoices are consolidated on the last business day of the month. For more information about cutoff day and due date calculation, see **Calculating the due date for a consolidated invoice** in [(JPN) About consolidating invoices](jpn-about-consolidating-invoices.md).
    

    > [!NOTE]
    > <P>This field is available only if you select the <STRONG>Use cut-off day</STRONG> check box in the <STRONG>Accounts payable parameters</STRONG> form.</P>



## See also

[(JPN) Set up a consolidated invoice for a vendor](jpn-set-up-a-consolidated-invoice-for-a-vendor.md)

  


