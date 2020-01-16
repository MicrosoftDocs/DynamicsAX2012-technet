---
title: (LTU) Set up VAT paid by the customer
TOCTitle: (LTU) Set up VAT paid by the customer
ms:assetid: 2db1ac22-3df1-4885-b9c2-4c9d020b0882
ms:mtpsurl: https://technet.microsoft.com/library/JJ665047(v=AX.60)
ms:contentKeyID: 49386630
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Set up VAT paid by the customer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Under certain conditions, sales or purchase VAT is calculated and paid by the customer or vendor, if the customer or vendor is registered in Lithuania as a VAT payer. These conditions include:

  - The company is buying or selling wood and woodenwares, such as logs, planks, or beams.

  - The company is buying or selling ferrous/non-ferrous items or products, including waste or debris.

  - The company is bankrupt.

When the sales and purchase orders are marked as **Not in invoice** in the **Sales tax codes setup** form, the VAT paid by the customer is excluded from the tax calculated in the invoice register reports. The sales invoice register (FR0672) and the purchase invoice register (FR0671) reports are modified to display the amount of VAT paid by the customer (reverse charge VAT case) and the VAT that pertains to purchase and sales orders issued by United VAT companies.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new line.

3.  In the **Sales tax code** field, enter a VAT code.

4.  Click the **General** FastTab.

5.  Select the **Exclude from invoice** check box to exclude the sales tax code with a negative percentage from the VAT specification in the invoice reports and the invoice registers.
    

    > [!NOTE]
    > <P>Select the <STRONG>Exclude from invoice</STRONG> check box only for the sales tax code with a negative VAT percentage.</P>



6.  Click the **Tax directives** button to enter the language and description for the new sales tax codes.

7.  Press CTRL+S or close the form.

8.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.
    

    > [!NOTE]
    > <P>For more information, see "Sales tax groups (form)" in the Applications and Business Processes Help.</P>



9.  Press CTRL+N to create a new line.

10. In the **Sales tax group** field, enter a sales tax group.

11. Click the **Setup** tab.

12. In the **Sales tax code** field, select the sales tax code with a negative VAT percentage to attach the sales tax codes to the sales tax groups.
    

    > [!NOTE]
    > <P>You must also attach the sales tax code that you created with a normal VAT percentage.</P>



13. Press CTRL+S or close the form.

14. Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.
    

    > [!NOTE]
    > <P>For more information, see "Item sales tax groups (form)" in the Applications and Business Processes Help.</P>



15. Press CTRL+N to create a new line.

16. In the **Item sales tax group** field, enter an item sales tax group.

17. Click the **Setup** tab.

18. In the **Sales tax code** field, select the sales tax code with a negative VAT percentage to attach the sales tax codes to the item sales tax group.
    

    > [!NOTE]
    > <P>You must also attach the sales tax code that you created with a normal VAT percentage.</P>



19. Press CTRL+S or close the form.

  


