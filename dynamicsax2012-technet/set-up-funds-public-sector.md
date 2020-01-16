---
title: Set up funds (Public sector)
TOCTitle: Set up funds (Public sector)
ms:assetid: ed80aaf4-26b8-4bfe-b566-93d9f6f0818a
ms:mtpsurl: https://technet.microsoft.com/library/Hh208602(v=AX.60)
ms:contentKeyID: 36056390
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Public sector
- set up funds
- fund
audience: Application User
ms.search.region: Denmark, France
---

# Set up funds (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up funds that can be linked to financial account dimensions.

Each fund must have a name and a unique number, and must be assigned a fund type, fund class, and other required attributes. Fund types must be created before you can set up funds. For more information about setting up fund types, see [Set up fund types (Public sector)](set-up-fund-types-public-sector.md). For more information about setting up a system of funds, see [About funds (Public sector)](about-funds-public-sector.md).

The Governmental Accounting Standards Board (GASB) recommends a set of Generally Accepted Accounting Principles (GAAP) for state and local governmental accounting. You can use these standards when you set up your own system of funds and fund types.

### Set up funds

1.  Click **General ledger** \> **Setup** \> **Fund** \> **Funds**.

2.  Click **New** to create a line for a new fund.

3.  In the **Fund number** field, enter a unique number for the fund.

4.  In the **Fund name** field, enter a name for the fund.

5.  In the **Fund type** field, select a type for the fund.

6.  In the **Fund class** field, select a high-level classification for the fund.
    

    > [!NOTE]
    > <P>The GAAP identifies eight fund types that are categorized under three fund classes:</P>
    > <UL>
    > <LI>
    > <P>Governmental funds include the general fund, special revenue funds, capital project funds, and debt service funds.</P>
    > <LI>
    > <P>Proprietary, or business-type, funds include enterprise funds and internal service funds.</P>
    > <LI>
    > <P>Fiduciary funds include trust funds and agency funds.</P></LI></UL>



7.  If this fund is not used in financial reporting, select the **Non-reporting fund** check box.

8.  If this fund is reported as a major fund, select the **Major fund** check box.

9.  Optional: Select the **Override selected year-end option** to select a year-end close option for this fund.
    

    > [!IMPORTANT]
    > <P>Do this only if you want this fund to have different year-end processing rules than those used for other funds. If you do this, it will override any year-end processing options that have been selected for all funds in the <STRONG>Purchase order year-end process</STRONG> form.</P>



10. If you selected **Override selected year-end option**, select a year-end option for this fund from the list. For more information on year-end processing options, see [Process purchase orders at year end](process-purchase-orders-at-year-end.md).

## See also

[Funds (form) (Public sector)](https://technet.microsoft.com/library/hh208514\(v=ax.60\))

  


