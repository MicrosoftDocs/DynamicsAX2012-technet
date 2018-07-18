---
title: (HUN) Create a free text invoice that includes the VAT exchange rate
TOCTitle: (HUN) Create a free text invoice that includes the VAT exchange rate
ms:assetid: d0415283-110a-41d3-a3a7-d4123dd74d60
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664377(v=AX.60)
ms:contentKeyID: 49385465
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Create a free text invoice that includes the VAT exchange rate 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Free-text invoices must contain tax information in your organization’s accounting currency.

Organizations are not required to calculate value-added tax (VAT) amounts based on the National Bank currency exchange rates. Instead, you can create exchange rates for calculating VAT in other currencies. The exchange rates that you create for calculating VAT can be different from the exchange rates that you use for general accounting.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, in the **New** group, click **Free text invoice**.

3.  In the **Free text invoice** form, on the **Free text invoice header** FastTab, select the customer account. The default information for the customer account is displayed.

4.  Select a billing classification.

5.  In the **Invoice lines** grid, enter a description, select the main account, and enter the quantity and unit price for the invoice line.

6.  On the **Line details** FastTab, enter any additional information.

7.  On the **Action Pane**, in the **Details** group, click **Sales tax**.

8.  In the **Sales tax transactions** form, enter a date in the **Date of VAT register** field, and update the sales tax exchange rate.
    

    > [!NOTE]
    > <P>The <STRONG>Sales tax exchange rate</STRONG> field is automatically filled in with the exchange rate for the default bank group.</P>

    
    You can view the VAT exchange rate information on the **General** tab.


> [!NOTE]
> <P>Any difference in amounts that are caused by the difference between the general accounting exchange rates and VAT calculation exchange rates is automatically posted to the ledger account that has been selected to receive differences in sales tax calculation.</P>



## See also

[(HUN) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664221\(v=ax.60\))

  


