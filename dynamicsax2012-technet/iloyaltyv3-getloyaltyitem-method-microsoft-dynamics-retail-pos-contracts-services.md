---
title: ILoyaltyV3.GetLoyaltyItem Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetLoyaltyItem Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV3.GetLoyaltyItem(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv3.getloyaltyitem(v=AX.60)
ms:contentKeyID: 62205297
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV3.GetLoyaltyItem
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyItem Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets loyalty item based on the passed in card number

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetLoyaltyItem ( _
    cardNumber As String _
) As ILoyaltyItem
'Usage
Dim instance As ILoyaltyV3
Dim cardNumber As String
Dim returnValue As ILoyaltyItem

returnValue = instance.GetLoyaltyItem(cardNumber)
```

``` csharp
ILoyaltyItem GetLoyaltyItem(
    string cardNumber
)
```

``` c++
ILoyaltyItem^ GetLoyaltyItem(
    String^ cardNumber
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyItem](iloyaltyitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
An instance of the [ILoyaltyItem](iloyaltyitem-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md) for the specified loyalty card  

## See Also

#### Reference

[ILoyaltyV3 Interface](iloyaltyv3-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

