---
title: IEFTV1.IdentifyCard Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IdentifyCard Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.IdentifyCard(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.ieftv1.identifycard(v=AX.60)
ms:contentKeyID: 47344248
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.IdentifyCard
dev_langs:
- CSharp
- C++
- VB
---

# IdentifyCard Method

Identifies the card if a match with pre-configured card types in not found by the application.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub IdentifyCard ( _
    ByRef cardInfo As ICardInfo, _
    ByRef eftInfo As IEFTInfo _
)
'Usage
Dim instance As IEFTV1
Dim cardInfo As ICardInfo
Dim eftInfo As IEFTInfo

instance.IdentifyCard(cardInfo, eftInfo)
```

``` csharp
void IdentifyCard(
    ref ICardInfo cardInfo,
    ref IEFTInfo eftInfo
)
```

``` c++
void IdentifyCard(
    ICardInfo^% cardInfo, 
    IEFTInfo^% eftInfo
)
```

#### Parameters

  - cardInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICardInfo](icardinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - eftInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEFTV1 Interface](ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

