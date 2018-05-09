---
title: IPriceV1.GetBasicPrice Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetBasicPrice Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.GetBasicPrice(System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ipricev1.getbasicprice(v=AX.60)
ms:contentKeyID: 47344061
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IPriceV1.GetBasicPrice
dev_langs:
- CSharp
- C++
- VB
---

# GetBasicPrice Method

**Note: This API is now obsolete.**

Retrieves the basic retail price.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
<ObsoleteAttribute("This method is not used anymore, please use GetItemPrice method.")> _
Function GetBasicPrice ( _
    itemId As String _
) As Decimal
'Usage
Dim instance As IPriceV1
Dim itemId As String
Dim returnValue As Decimal

returnValue = instance.GetBasicPrice(itemId)
```

``` csharp
[ObsoleteAttribute("This method is not used anymore, please use GetItemPrice method.")]
decimal GetBasicPrice(
    string itemId
)
```

``` c++
[ObsoleteAttribute(L"This method is not used anymore, please use GetItemPrice method.")]
Decimal GetBasicPrice(
    String^ itemId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The price of the item.  

## See Also

#### Reference

[IPriceV1 Interface](ipricev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

