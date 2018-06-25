---
title: Set up price combinations
TOCTitle: Set up price combinations
ms:assetid: 007c732b-6bab-445e-8357-10ea45986d97
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569681(v=AX.60)
ms:contentKeyID: 36055916
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up price combinations [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To determine the sales price of configured items, you can create price combinations for product models. Price combinations are the alternative to the standard BOM price calculation. Click **Product information management** \> **Setup** \> **Product builder** \> **Product builder parameters**.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



Price combinations are based on the item sales price from the **Item** form or from trade agreements, with the addition of one or more price adjustments, depending on what has been selected in the user dialog box for the product model.

1.  Click **Product information management** \> **Common** \> **Product builder** \> **Product models**.

2.  Double-click a product model.

3.  Click **Setup** \> **Price combinations**.

4.  In the **Percentage/Amount** field, select an option to calculate price adjustments:
    
      - As a percentage of the basic price (**Percent**)
    
      - As an absolute amount (**Amount**)
    
      - By using a calculation formula (**Calculated**)
    
    When several price adjustments apply to a specific item configuration, amount-based and calculated adjustments are applied first, and then percentage-based adjustments are applied.

5.  If you select **Percent** or **Amount**, enter a percentage or an amount (positive or negative) that should be added to the standard sales price in the **Price adjustment** field. If you select **Calculated**, click **Price/Discount setup** and specify a formula.

6.  Enter a description of the price adjustment in the **Description** field.

7.  Click **Price/Discount setup** to define a rule that determines when the price adjustment becomes active for percentage-based and amount-based adjustments. Price adjustment expressions are created just like validation rules. For more information, see [About validation rules](about-validation-rules.md).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

