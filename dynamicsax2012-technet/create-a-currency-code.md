---
title: Create a currency code
TOCTitle: Create a currency code
ms:assetid: a7092da3-b60a-40f4-ba8e-45e09c9bd377
ms:mtpsurl: https://technet.microsoft.com/library/Hh351822(v=AX.60)
ms:contentKeyID: 36676400
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- currency code
- currency
- currency setup
- set up a currency
audience: Application User
ms.search.region: Global
---

# Create a currency code 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Many currency codes are already set up, based on the International Organization for Standardization (ISO) currency codes. However, you can update existing currency codes with information that is specific to your legal entity.

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  Click **New**.

3.  Enter a unique code. If the code does not match an existing ISO currency code, a message will be displayed.

4.  Enter a name and symbol for the currency code.

5.  Select the **Reference currency for triangulation** check box if this currency is a denomination, or fixed, currency that other currencies are triangulated through.

6.  Select the **Conversion** check box to include the currency in the calculations of the online numeric conversion tool.

7.  Enter text to be printed in front of the amount (**Prefix**) or after the amount (**Suffix**) for the currency.

8.  Click the **Rounding rules** FastTab.

9.  Enter the unit for general rounding amounts.

10. Enter the unit for rounding amounts on sales orders, purchase orders, or prices, and select the rounding convention that applies to the number to the right of the round-off unit that is entered in the **Rounding rule** field.

11. Click the **Currency gender** FastTab.

12. If the currency is used on checks and reports, and has a feminine gender, select **Feminine** in the **Gender** field.
    
    The default value for this field is **Masculine**, which, in effect, means no gender.

13. Click the **External codes** button to define and maintain external codes for different fields that are used to send and receive documents electronically through Application Integration Framework (AIF).

  


