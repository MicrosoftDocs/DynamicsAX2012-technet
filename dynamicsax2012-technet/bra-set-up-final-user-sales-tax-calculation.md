---
title: (BRA) Set up final user sales tax calculation
TOCTitle: (BRA) Set up final user sales tax calculation
ms:assetid: 45780bd5-cb52-4d4b-b433-58d6a8e29a8a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ710484(v=AX.60)
ms:contentKeyID: 49384375
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up final user sales tax calculation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The ICMS tax calculation basis must include IPI tax and freight charges, if any, on the sales made to a final user of the product or service.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. To open an existing customer record, double-click the customer in the list, and then on the **Action Pane** click **Edit**.

2.  On the **Fiscal information**, select the **Final user** check box for the customer.

3.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. To open an existing sales order, double-click the sales order in the list.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**. To open an existing sales quotation, double-click the sales quotation in the list.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.To open an existing free text invoice, double-click the free text invoice in the list.
    
    The **Final user** check box on the **Fiscal information** tab of the sales order, sales quotation, or free text invoice is selected if the customer is the final user of the item.

4.  Select the tax groups.

## Example

Suppose that the sale price is R$200, ICMS tax is 5 percent, IPI is 10 percent, and the ICMS tax base is 220 (200 + 200\*10 percent). The ICMS tax amount is 11 (220\*5 percent).

## See also

[(BRA) Customers (modified form)](https://technet.microsoft.com/en-us/library/jj933537\(v=ax.60\))

[(BRA) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj933514\(v=ax.60\))

[(BRA) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj933514\(v=ax.60\))

[(BRA) Sales quotation (modified form)](https://technet.microsoft.com/en-us/library/jj923173\(v=ax.60\))

  


