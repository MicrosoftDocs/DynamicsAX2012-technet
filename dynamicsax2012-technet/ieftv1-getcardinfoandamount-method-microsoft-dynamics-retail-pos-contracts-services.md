---
title: IEFTV1.GetCardInfoAndAmount Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetCardInfoAndAmount Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.GetCardInfoAndAmount(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ieftv1.getcardinfoandamount(v=AX.60)
ms:contentKeyID: 47344345
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.GetCardInfoAndAmount
dev_langs:
- CSharp
- C++
- VB
---

# GetCardInfoAndAmount Method

Implements workflows supported by the card type.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetCardInfoAndAmount ( _
    ByRef cardInfo As ICardInfo _
) As Boolean
'Usage
Dim instance As IEFTV1
Dim cardInfo As ICardInfo
Dim returnValue As Boolean

returnValue = instance.GetCardInfoAndAmount(cardInfo)
```

``` csharp
bool GetCardInfoAndAmount(
    ref ICardInfo cardInfo
)
```

``` c++
bool GetCardInfoAndAmount(
    ICardInfo^% cardInfo
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
true if the system should continue with the authorization process; otherwise, false.  

## See Also

#### Reference

[IEFTV1 Interface](ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

