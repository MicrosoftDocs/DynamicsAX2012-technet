---
title: ILoyaltyV4.GetLoyaltyBalanceInfo Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetLoyaltyBalanceInfo Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.GetLoyaltyBalanceInfo(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iloyaltyv4.getloyaltybalanceinfo(v=AX.60)
ms:contentKeyID: 62205005
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ILoyaltyV4.GetLoyaltyBalanceInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetLoyaltyBalanceInfo Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets loyalty card balance info.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetLoyaltyBalanceInfo ( _
    cardNumber As String _
) As ILoyaltyCardData
'Usage
Dim instance As ILoyaltyV4
Dim cardNumber As String
Dim returnValue As ILoyaltyCardData

returnValue = instance.GetLoyaltyBalanceInfo(cardNumber)
```

``` csharp
ILoyaltyCardData GetLoyaltyBalanceInfo(
    string cardNumber
)
```

``` c++
ILoyaltyCardData^ GetLoyaltyBalanceInfo(
    String^ cardNumber
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILoyaltyCardData](iloyaltycarddata-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
Info about loyalty card and its balance.  

## See Also

#### Reference

[ILoyaltyV4 Interface](iloyaltyv4-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

