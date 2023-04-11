---
title: IPriceV2.GetItemPrice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetItemPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV2.GetItemPrice(System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ipricev2.getitemprice(v=AX.60)
ms:contentKeyID: 62203911
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV2.GetItemPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetItemPrice Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks if the item with variant is a part of a price agreement and if it is returns that price. If it's not then the function returns the basic item price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetItemPrice ( _
    itemId As String, _
    inventDimId As String, _
    unitOfMeasure As String _
) As Decimal
'Usage
Dim instance As IPriceV2
Dim itemId As String
Dim inventDimId As String
Dim unitOfMeasure As String
Dim returnValue As Decimal

returnValue = instance.GetItemPrice(itemId, _
    inventDimId, unitOfMeasure)
```

``` csharp
decimal GetItemPrice(
    string itemId,
    string inventDimId,
    string unitOfMeasure
)
```

``` c++
Decimal GetItemPrice(
    String^ itemId, 
    String^ inventDimId, 
    String^ unitOfMeasure
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - unitOfMeasure  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The price of variant item.  

## See Also

#### Reference

[IPriceV2 Interface](ipricev2-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

