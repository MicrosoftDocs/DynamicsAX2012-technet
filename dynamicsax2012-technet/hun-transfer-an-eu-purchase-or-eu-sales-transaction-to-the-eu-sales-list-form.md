---
title: (HUN) Transfer an EU purchase or EU sales transaction to the EU sales list form
TOCTitle: (HUN) Transfer an EU purchase or EU sales transaction to the EU sales list form
ms:assetid: 81fe7963-42d1-45b2-8b53-27739cc0436a
ms:mtpsurl: https://technet.microsoft.com/library/JJ664322(v=AX.60)
ms:contentKeyID: 49385411
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Transfer an EU purchase or EU sales transaction to the EU sales list form 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can modify an EU purchase transaction and specify the reason for the change in the EU sales list form. The transactions are grouped based on the VAT registration ID and trade type. According to Hungarian tax regulations, companies are free to designate their own bank exchange rate. The exchange rate must be calculated as the average of the selling and buying rate of the foreign currency. Companies are also free to designate the date of exchange rate used to calculate the MST amount for orders in foreign currencies. The following two methods can be applied:

  - **Shipping date** – The shipping date is the date of the packing slip.

  - **Fulfillment of contract** – The contract fulfillment date is selected as the Intrastat fulfillment date in sales and purchase forms.

<!-- end list -->

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **EU sales list**.

2.  Click **Transfer** to transfer the posted EU purchase or sales transaction into the **EU sales list** form.

3.  Select the transactions to be corrected.

4.  In the **Direction** field, indicate whether the transaction is a sale or purchase:
    
      - **Vendor** – The transaction is a purchase.
    
      - **Customer** – The transaction is a sale.

5.  Select the **Corrected** check box to indicate that the transaction is corrected.

6.  Click the **Other** tab.

7.  Select the **Error in registration number** check box to indicate that an error in the registration number was corrected.

8.  Select the **Error in amount** check box to indicate that an error in the amount was corrected.

9.  Select the **Error in period** check box to indicate that an error in the reporting period was corrected.

10. Press CTRL+S or close the form.

## See also

[(HUN) EU sales list (modified form)](https://technet.microsoft.com/library/jj664282\(v=ax.60\))

  


