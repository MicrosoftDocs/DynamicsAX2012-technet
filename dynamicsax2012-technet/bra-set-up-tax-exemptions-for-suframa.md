---
title: (BRA) Set up tax exemptions for Suframa
TOCTitle: (BRA) Set up tax exemptions for Suframa
ms:assetid: ccb1eb11-f694-4b9a-b08a-088c946de31d
ms:mtpsurl: https://technet.microsoft.com/library/JJ663932(v=AX.60)
ms:contentKeyID: 49384517
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up tax exemptions for Suframa 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Use the following procedure to exempt the PIS and COFINS taxes on sales made to customers from Suframa.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Click the **Fiscal information** tab.

2.  Select the **SUFRAMA** check box if the customer is from the Suframa region.

3.  In the **SUFRAMA number** field, enter the Suframa number of the customer.

4.  Select the **Discount PIS and COFINS** check box to discount the PIS and COFINS taxes for the Suframa customer.

5.  Click **General ledger** \> **Reports** \> **Base data** \> **Sales tax codes**. Then, create the ICMS, IPI, PIS, and COFINS sales tax codes.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A>and <A href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</A>.</P>



6.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. In the **Sales tax code** field on the **Setup** tab, select the sales tax code created in step 5.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa615960(v=ax.60)">Item sales tax groups (form)</A> and <A href="create-item-sales-tax-groups.md">Create item sales tax groups</A>.</P>



7.  Select the taxation code with fiscal value **Without Credit/Debit (other)** to specify the taxes that are without tax credit.

8.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

9.  Create a sales order or a sales quotation for the Suframa customer.

10. In the **Item sales tax group** and **Sales tax group** fields on the **Setup** tab, select the tax groups.
    
    On the **Lines** tab, in the **SUFRAMA discount** field, the total percentage of the discounted taxes is displayed.
    
    For example, if the ICMS tax is 5 percent, IPI is 5 percent, PIS is 2 percent, and COFINS is 5 percent, the total discount percentage for the Suframa customer is 12 percent. This provides the base to calculate other taxes.

## See also

[(BRA) Sales orders (modified form)](https://technet.microsoft.com/library/jj911252\(v=ax.60\))

[(BRA) Sales quotation (modified form)](https://technet.microsoft.com/library/jj923173\(v=ax.60\))

[(BRA) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj663982\(v=ax.60\))

[(BRA) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj682105\(v=ax.60\))

  


