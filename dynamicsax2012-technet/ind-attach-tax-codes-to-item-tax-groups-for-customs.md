---
title: (IND) Attach tax codes to item tax groups for customs
TOCTitle: (IND) Attach tax codes to item tax groups for customs
ms:assetid: 9e5e6944-263c-41c3-8f19-afbaa55b75e4
ms:mtpsurl: https://technet.microsoft.com/library/JJ664710(v=AX.60)
ms:contentKeyID: 49386041
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Attach tax codes to item tax groups for customs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can attach tax codes to item tax groups for customs.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**. The **Item sales tax groups** form is displayed.

2.  Press CTRL+N to create a new line.

3.  Enter a group of sales tax codes that can be calculated for an item in the **Item sales tax group** field.

4.  Enter a description of the item sales tax group in the **Description** field.

5.  Click the **General** tab.

6.  Modify the **Item sales tax group** and **Description** fields, if required.

7.  Click the **Setup** tab and select the customs tax code in the **Tax code** field.
    

    > [!NOTE]
    > <P>The percentage defined for the tax code is displayed in the <STRONG>Percentage/amount</STRONG> field. When you enter more than one tariff code in the <STRONG>Values</STRONG> form for the tax code, zero will be displayed in the <STRONG>Percentage/amount</STRONG> field.</P>



8.  Enter the percentage of abatement in the **Abatement %** field. The tax amount is calculated after deducting the percentage of abatement from the base amount.

9.  Select the **Load on Inventory** check box to define the percentage of tax amount to add to the inventory cost.

10. Click **Formula Designer** to set up a formula for taxes.
    

    > [!NOTE]
    > <P>For more information, see <A href="ind-define-a-formula-to-calculate-customs-duty.md">(IND) Define a formula to calculate customs duty</A></P>



11. Press CTRL+S or close the form.

## See also

[(IND) Create tax codes for customs](ind-create-tax-codes-for-customs.md)

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj710918\(v=ax.60\))

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

  


