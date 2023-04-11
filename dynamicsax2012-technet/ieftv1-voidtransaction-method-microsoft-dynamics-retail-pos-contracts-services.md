---
title: IEFTV1.VoidTransaction Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: VoidTransaction Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.VoidTransaction(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo@,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftv1.voidtransaction(v=AX.60)
ms:contentKeyID: 47343908
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.VoidTransaction
dev_langs:
- CSharp
- C++
- VB
---

# VoidTransaction Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Voids the card payment by establishing a connection with the configured payment processor.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function VoidTransaction ( _
    ByRef eftInfo As IEFTInfo, _
    posTransaction As IPosTransaction _
) As Boolean
'Usage
Dim instance As IEFTV1
Dim eftInfo As IEFTInfo
Dim posTransaction As IPosTransaction
Dim returnValue As Boolean

returnValue = instance.VoidTransaction(eftInfo, _
    posTransaction)
```

``` csharp
bool VoidTransaction(
    ref IEFTInfo eftInfo,
    IPosTransaction posTransaction
)
```

``` c++
bool VoidTransaction(
    IEFTInfo^% eftInfo, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - eftInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if the processing succeeded otherwise, false.  

## See Also

#### Reference

[IEFTV1 Interface](ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

