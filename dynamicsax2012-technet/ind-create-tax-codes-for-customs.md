---
title: (IND) Create tax codes for customs
TOCTitle: (IND) Create tax codes for customs
ms:assetid: 2b997829-3592-4334-ab1c-c64cf1eb0419
ms:mtpsurl: https://technet.microsoft.com/library/JJ664586(v=AX.60)
ms:contentKeyID: 49385769
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create tax codes for customs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can create tax codes for customs duties and define the percentage of customs duties.

You can also enter the preferential value for the customs tax code because the preferential rate is used for goods imported from specific countries, based on agreements with such countries. Customs duty is calculated based on the preferential rate defined in the **Preferential value** field instead of the value defined in the **Value** field if the vendor or customer is set as preferential.


> [!NOTE]
> <P>The setup options in the <STRONG>Purchase duty</STRONG> field and <STRONG>Payment sales tax code</STRONG> field on the <STRONG>General</STRONG> tab will not be applied for customs tax type.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N on the **Overview** tab.

3.  Enter a code to identify the customs tax code in the **Sales tax code** field and a name for the tax code in the **Name** field.

4.  Select the **Customs** in the **Tax type** field.

5.  Select the customs duty settlement period for the customs tax code in the **Settlement period** field.

6.  Select the customs tax ledger posting group for the customs tax code in the **Tax ledger posting group** field.

7.  Select a method of calculation in the **Origin** field to calculate the customs duty. The method of calculation is applied to the base amount. You can select the **Amount per unit** to define the custom duty amount per unit of item for the tax code. You can define the amount per unit only when you post transactions using a purchase order, sales order, export order and general journal.
    

    > [!NOTE]
    > <P>You can select only the percentage of net amount method of calculations and the amount per unit method of calculations for Indian taxes.</P>



8.  Click the **General** tab, and then select the customs duty component for the customs tax code in the **Tax component** field.

9.  Click the **Values** button to open the **Values of sales tax codes** form and attach customs tariff codes to the customs tax code.

10. Select the customs tariff code to define the customs duty percentage in the **Tariff code** field. The type of direction defined for the tariff code is displayed in the **Direction** field.

11. Enter the starting date and the ending date of validity for the customs duty percentage.

12. Enter the percentage to calculate customs duty for the tax code and tariff code combination in the **Value** field.

13. Enter the preferential value for the customs tax code in the **Preferential value** field.

14. Enter other required details.

15. Press CTRL+S or close the form.

## See also

[(IND) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj664864\(v=ax.60\))

  


