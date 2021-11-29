---
title: (RUS) Set up amount difference parameters for exchange rates
TOCTitle: (RUS) Set up amount difference parameters for exchange rates
ms:assetid: 3cd7c3b1-5557-420d-ba94-3a9292194c6e
ms:mtpsurl: https://technet.microsoft.com/library/JJ853174(v=AX.60)
ms:contentKeyID: 50396455
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up amount difference parameters for exchange rates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

An original facture can be corrected if the currency values change during the shipment of goods. After the facture is corrected, the company verifies that the sum of the correction is equal to the sum of the amount difference. An amount difference facture is generated when a purchase or sales transaction is settled under the following conditions:

  - The invoice currency and the company currency differ.

  - The payment currency is equal to the company currency.

  - The exchange rate of the invoice currency on the invoice date differs from the exchange rate on the payment date.

  - The amount difference affects the company’s liability for value-added tax (VAT).

An amount difference facture that is generated is processed independently of other factures, and is included in the sales and purchase books. You can then print the amount difference facture and the original facture that was adjusted based on the amount difference.

Use this procedure to set up parameters for amount difference for exchange rates. When you post an exchange adjustment transaction, it is posted to the ledger account that is defined in the **Currency revaluation accounts** form. All adjustments are posted to ledger accounts. You must set the posting rules, and you must set the taxable parameter for a positive or negative amount difference.

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency parameters**.

2.  Select the **Activate parameters** check box to activate the Russian revaluation parameters for the specified currency.

3.  On the **General** FastTab, select the **Amount difference in tax accounting** check box to take amount difference into account in the calculation of tax accounting registers.

4.  On the **Sales/customers** FastTab, in the **Expense code** field, select the expense code to use as a tax dimension for the exchange adjustment transaction if the exchange adjustment is a loss.
    

    > [!NOTE]
    > <P>The <STRONG>Sales/customers</STRONG> FastTab is available only if you select <STRONG>Incremental</STRONG> or <STRONG>Period grand total</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



5.  The settlement transactions may cause exchange adjustment losses and profits. In the **Main account** field, select the main account for the **Realized loss** or **Realized gain** account and the **Unrealized loss** or **Unrealized gain** account that these exchange adjustment losses and profits are posted to.
    

    > [!NOTE]
    > <P>This field is required if you select <STRONG>Deviation from the cost price</STRONG> in the <STRONG>Ledger posting</STRONG> field. The <STRONG>Unrealized loss</STRONG> or <STRONG>Unrealized gain</STRONG> account is used when revaluation of foreign currency is performed.</P>



6.  In the **Customer tax dimension** field group, in the **Revenue code** field, select the revenue code for the exchange adjustment transaction if the exchange adjustment is a profit.

7.  In the **Sales taxes** field, select **Tax** to specify whether the realized profit or loss of purchase tax is subject to VAT.
    

    > [!NOTE]
    > <P>The amount difference factures are created only if the <STRONG>Sales taxes</STRONG> field for a positive or negative amount difference is set to <STRONG>Tax</STRONG>.</P>



8.  On the **Purchases/Vendors** FastTab, in the **Expense code** field, select the expense code to use as a tax dimension for the amount difference transaction if the amount difference is a loss.
    

    > [!NOTE]
    > <P>The <STRONG>Purchases/Vendors</STRONG> tab is available only if you select <STRONG>Incremental</STRONG> or <STRONG>Period grand total</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



9.  In the **Revenue code** field, select the revenue code to use for the transaction if the amount difference that the settlement produces is a profit.

10. In the **Sales taxes** field, select **Tax** to specify whether the realized profit or loss of purchase tax is subject to VAT.
    

    > [!NOTE]
    > <P>The amount difference factures are created only if the <STRONG>Sales taxes</STRONG> field for a positive or negative amount difference is set to <STRONG>Tax</STRONG>.</P>



11. In the **Main account** fields, select the ledger account that the exchange adjustment transactions for losses and profits are posted to.
    

    > [!NOTE]
    > <P>This field is required if you select <STRONG>Deviation from the cost price</STRONG> in the <STRONG>Ledger posting</STRONG> field.</P>



## See also

[(RUS) Set up accounts payable parameters for amount differences](rus-set-up-accounts-payable-parameters-for-amount-differences.md)

[(RUS) Currency revaluation accounts (modified form)](https://technet.microsoft.com/library/jj852149\(v=ax.60\))

  


