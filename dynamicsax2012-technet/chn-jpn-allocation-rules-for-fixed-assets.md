---
title: (CHN, JPN) Allocation rules for fixed assets
TOCTitle: (CHN, JPN) Allocation rules for fixed assets
ms:assetid: d67b5e3c-36d5-4acc-bb62-6e51f7d8ad85
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn306806(v=AX.60)
ms:contentKeyID: 54925750
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Rule
- Fixed asset
- Allocation rule
- Depreciation cost
- Depreciation expense
audience: Application User
ms.search.region: China (PRC)
---

# (CHN, JPN) Allocation rules for fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up an allocation rule to allocate depreciation costs for a fixed asset to a dimension of your legal entity. Fixed assets can be put into service for multiple dimensions, such as departments or cost centers. When you depreciate a fixed asset, the depreciation cost is posted to an offset account. By setting up an allocation rule, you can share the depreciation cost of the fixed asset between multiple dimensions of your legal entity.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## When allocating depreciation costs, is it possible for the dimensions that are based on the allocation rule of the fixed asset model to override the default dimensions in the journal header?

Yes. The dimensions that you specify in the allocation rule override the default dimensions that are normally displayed in the journal header.

## What happens if I delete a dimension that is part of an allocation rule?

If you delete a financial dimension that is assigned to an allocation rule, Microsoft Dynamics AX displays a message that indicates that the depreciation proposal cannot be run. You must select another financial dimension for the allocation rule and run the depreciation proposal again.

## How does rounding the currency up or down affect the allocation rule?

After an allocation rule is applied to a fixed asset, the deprecation cost that is allocated to a legal entity dimension can be a whole amount or a fractional amount. If you have set up rounding rules for your currency, the resulting allocated depreciation costs can be greater than or less than the depreciation cost, in accordance with the allocation rule. Here are some examples of how currency rounding can affect the allocation rule:

## Rounded up currency

Assume that the depreciation cost amount of a fixed asset is 170 currency units. You have set up an allocation rule to allocate one percent of the depreciation cost to each of the 100 dimensions of your legal entity. You have also set up a rounding rule that indicates that fractional currency units that are greater than the halfway point between two whole currency units are rounded up to the nearest whole currency unit. In this case, the depreciation cost per dimension is calculated as follows.

  - Original depreciation cost per dimension = 1.70 currency units

  - Rounded up depreciation cost per dimension = 2.00 currency units

  - Total rounded up depreciation cost of the fixed asset = 2.00 \* 100 = 200 currency units

## Rounded down currency

Assume that the depreciation cost amount of a fixed asset is 120 currency units. You have set up an allocation rule to allocate one percent of the depreciation cost to each of the 100 dimensions of your legal entity. You have also set up a rounding rule that indicates that fractional currency units that are less than the halfway point between two whole currency units are rounded down to the nearest whole currency unit. In this case, the depreciation cost per dimension is calculated as follows.

  - Original depreciation cost per dimension = 1.20 currency units

  - Rounded down depreciation cost per dimension = 1.00 currency units

  - Total rounded down depreciation cost of the fixed asset = 1.00 \* 100 = 100 currency units

If the total rounded down depreciation cost to be allocated across each dimension is less than the rounding amount, Microsoft Dynamics AX does not apply the allocation rule to the depreciation. The depreciation amount is posted to the main account, or is offset by using the posting profile rules that you set up in the **Fixed asset posting profiles** form. To avoid these and similar scenarios, you can manually adjust the rounding rule for fixed asset depreciation in the **Currencies** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(CHN, JPN) Create allocation rules and allocate depreciation costs](chn-jpn-create-allocation-rules-and-allocate-depreciation-costs.md)

[About default offset accounts for expense transactions](about-default-offset-accounts-for-expense-transactions.md)

[About round-off depreciation](about-round-off-depreciation.md)

[Currencies (form)](https://technet.microsoft.com/en-us/library/aa582902\(v=ax.60\))

  


