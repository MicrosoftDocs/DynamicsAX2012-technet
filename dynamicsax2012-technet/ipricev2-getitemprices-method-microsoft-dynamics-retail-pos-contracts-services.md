---
title: IPriceV2.GetItemPrices Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetItemPrices Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV2.GetItemPrices(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISaleLineItem},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipricev2.getitemprices(v=AX.60)
ms:contentKeyID: 62204123
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV2.GetItemPrices
dev_langs:
- CSharp
- C++
- VB
---

# GetItemPrices Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if the items are part of a price agreement and returns either that price or the basic item price for each specified item.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetItemPrices ( _
    items As IEnumerable(Of ISaleLineItem), _
    inventDimId As String _
) As IEnumerable(Of ISaleLineItem)
'Usage
Dim instance As IPriceV2
Dim items As IEnumerable(Of ISaleLineItem)
Dim inventDimId As String
Dim returnValue As IEnumerable(Of ISaleLineItem)

returnValue = instance.GetItemPrices(items, _
    inventDimId)
```

``` csharp
IEnumerable<ISaleLineItem> GetItemPrices(
    IEnumerable<ISaleLineItem> items,
    string inventDimId
)
```

``` c++
IEnumerable<ISaleLineItem^>^ GetItemPrices(
    IEnumerable<ISaleLineItem^>^ items, 
    String^ inventDimId
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ISaleLineItem](isalelineitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)\>  
The collection of items with prices populated  

## See Also

#### Reference

[IPriceV2 Interface](ipricev2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

