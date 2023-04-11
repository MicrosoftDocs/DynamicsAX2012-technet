---
title: SalesTransaction.PriceCalculableSalesLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PriceCalculableSalesLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PriceCalculableSalesLines
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.pricecalculablesaleslines(v=AX.60)
ms:contentKeyID: 62211990
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.PriceCalculableSalesLines
dev_langs:
- CSharp
- C++
- VB
---

# PriceCalculableSalesLines Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the sales lines that needs to be included in discount and pricing calculation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public ReadOnly Property PriceCalculableSalesLines As ReadOnlyCollection(Of SalesLine)
    Get
'Usage
Dim instance As SalesTransaction
Dim value As ReadOnlyCollection(Of SalesLine)

value = instance.PriceCalculableSalesLines
```

``` csharp
[IgnoreDataMemberAttribute]
public ReadOnlyCollection<SalesLine> PriceCalculableSalesLines { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property ReadOnlyCollection<SalesLine^>^ PriceCalculableSalesLines {
    ReadOnlyCollection<SalesLine^>^ get ();
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## Remarks

This acts as a projection of the sales lines, allowing prices and discounts to operate over the subset of the sales lines for whose IsPriceLocked property is false.

Note that this might cause unexpected scenarios likes mix and match discounts not being applied due to the fact that one product is price locked, and the order is not.

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

