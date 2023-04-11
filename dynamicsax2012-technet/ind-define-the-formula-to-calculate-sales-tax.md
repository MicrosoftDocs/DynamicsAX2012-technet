---
title: (IND) Define the formula to calculate sales tax
TOCTitle: (IND) Define the formula to calculate sales tax
ms:assetid: 535ce6d4-95c8-4bd9-802e-5a78fbfcc507
ms:mtpsurl: https://technet.microsoft.com/library/JJ677819(v=AX.60)
ms:contentKeyID: 49385782
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Define the formula to calculate sales tax 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must define the formula to calculate sales tax for the item sales tax group. The formula for the sales tax codes can be defined by using sales tax codes and miscellaneous charge codes. The sales tax codes that are attached to the item sales tax group are displayed on the **Taxes** tab on the **Formula designer** form. You can also view the miscellaneous charges on the **Misc. charges** tab on the **Formula designer** form.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Select an item sales tax group.

3.  Click the **Formula designer** button.

4.  Press CTRL+N on the **Calculation** tab to define the calculation expression for a specific sales tax code. The automatically generated priority ID for sales tax calculation is displayed in the **ID** field.

5.  Select the sales tax code to define the formula for in the **Tax code** field.

6.  Select the basis to calculate sales tax.
    
      - **Line amount** – The sales tax is calculated on the transaction line amount by using the calculation expression that is defined for the sales tax code.
    
      - **Excl. line amount** – The sales tax is calculated by using the calculation expression that is defined for the sales tax code.
    
      - **Max. retail price** – The sales tax is calculated on the maximum retail price of the item line by using the calculation expression that is defined for the sales tax code.
    
      - **Assessable value** – The sales tax is calculated on the assessable value that is calculated for an item by using the calculation expression defined for the sales tax code.

7.  Select the **Price incl. tax** check box if the taxable basis includes the sales tax amount.
    

    > [!NOTE]
    > <P>The <STRONG>Price incl. tax</STRONG> check box is selected automatically for sales tax codes with maximum retail price as the taxable basis, but you can clear the check box if it is required.</P>



8.  Click the **+** button, **–** button, **\*** button, or **/** button to insert the calculation expression for the sales tax code in the **Calculation expression** field. You can define the calculation expression only by using the miscellaneous charge codes for the sales tax code with priority ID 1.
    

    > [!NOTE]
    > <P>The sales tax calculation is based on the formula that is defined in the <STRONG>Calculation expression</STRONG> field for the sales tax codes that are attached to the item sales tax group.</P>



9.  Use one of the following methods to add a sales tax code or a miscellaneous charge code to the **Calculation expression** field:
    
      - Click the **Taxes** tab \> **Misc. charges** tab \> **Misc. charges code**.
    
      - Double-click a code on the **Taxes** tab or the **Misc. charges** tab.
    
      - Drag and drop a code from the **Taxes** tab or **Misc. charges** tab.
    

    > [!NOTE]
    > <P>You must insert a calculation expression before each sales tax code in the <STRONG>Calculation expression</STRONG> field. For example, a formula must be entered in the syntax as + [LST – Freight + Fee].</P>



## See also

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj710918\(v=ax.60\))

  


