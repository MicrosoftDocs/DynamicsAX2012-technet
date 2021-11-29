---
title: IEFTV1.GetTransactionToken Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetTransactionToken Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.GetTransactionToken(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo,Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.ieftv1.gettransactiontoken(v=AX.60)
ms:contentKeyID: 47343867
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IEFTV1.GetTransactionToken
dev_langs:
- CSharp
- C++
- VB
---

# GetTransactionToken Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets transaction token for authorized transaction (Secure card storage).

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub GetTransactionToken ( _
    eftInfo As IEFTInfo, _
    posTransaction As IPosTransaction _
)
'Usage
Dim instance As IEFTV1
Dim eftInfo As IEFTInfo
Dim posTransaction As IPosTransaction

instance.GetTransactionToken(eftInfo, _
    posTransaction)
```

``` csharp
void GetTransactionToken(
    IEFTInfo eftInfo,
    IPosTransaction posTransaction
)
```

``` c++
void GetTransactionToken(
    IEFTInfo^ eftInfo, 
    IPosTransaction^ posTransaction
)
```

#### Parameters

  - eftInfo  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IEFTInfo](ieftinfo-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

<!-- end list -->

  - posTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

## See Also

#### Reference

[IEFTV1 Interface](ieftv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

