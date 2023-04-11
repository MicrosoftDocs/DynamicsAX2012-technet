---
title: (POL) Calculate tax interest and free-hand interest
TOCTitle: (POL) Calculate tax interest and free-hand interest
ms:assetid: c5e049e4-7af9-43d0-8cfb-af554b2be156
ms:mtpsurl: https://technet.microsoft.com/library/JJ711271(v=AX.60)
ms:contentKeyID: 49387089
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Calculate tax interest and free-hand interest 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Poland, the tax interest rates are determined by the Ministry of Finance. The vendor calculates the interest if the payment settlement is made after the due date. If the payment period is shorter than 30 days, the vendor can calculate the tax interest from the due date through the payment date. Free-hand interest rates apply when payments are settled between the 31st day after the posting and the due date.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Periodic** \> **Collections** \> **Interest calculation**.

2.  Select the **Invoice** check box to calculate interest on invoices.

3.  Select the **Credit note** check box to deduct customer credit notes before the interest calculation.

4.  Select the **Payment** check box to deduct customer payments before interest calculation.

5.  Select the **Interest** check box to calculate compound interest on previous interest notes.

6.  In the **From date** field, select the starting date. The interest calculation will include transactions that are due on or after this date.

7.  In the **To date** field, select the ending date for the interest calculation.

8.  In the **Round-off** field, enter the units to round off the interest amount.

9.  In the **Use posting profile from** field, select the posting profile from the following options:
    
      - **Account** – Use the posting profile from the relevant customer account for each interest note.
    
      - **Select** – Indicate a posting profile in the **Posting profile** field.

10. In the **Posting profile** field, select the customer posting profile for the calculation.

11. Select the **Tax interest** check box to calculate the free-hand interest and tax interest.

12. Click **Select** to open the **Interest job** form.

13. Select the criteria to calculate interest and click **OK**.

14. In the **Interest calculation** form, click **OK** to calculate the tax interest and free-hand interest and create the interest notes for the customer accounts.

## See also

[(POL) Set up the accounts receivable parameters to calculate interest](pol-set-up-the-accounts-receivable-parameters-to-calculate-interest.md)

[(POL) Set up a number sequence code for the interest note and voucher](pol-set-up-a-number-sequence-code-for-the-interest-note-and-voucher.md)

[(POL) Set up interest codes](pol-set-up-interest-codes.md)

[(POL) Set up customer posting profiles](pol-set-up-customer-posting-profiles.md)

[(POL) Post and print an interest note](pol-post-and-print-an-interest-note.md)

[(POL) View the calculated interest](pol-view-the-calculated-interest.md)

[(POL) Interest calculation (modified form)](https://technet.microsoft.com/library/jj678208\(v=ax.60\))

  


