---
title: IApplicationServiceV1.GetNextReceiptId Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: GetNextReceiptId Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetNextReceiptId(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.iapplicationservicev1.getnextreceiptid(v=AX.60)
ms:contentKeyID: 47344460
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.IApplicationServiceV1.GetNextReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# GetNextReceiptId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets and increments the next available receipt ID for the IPosTransaction transaction given.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetNextReceiptId ( _
    transaction As IPosTransaction _
) As String
'Usage
Dim instance As IApplicationServiceV1
Dim transaction As IPosTransaction
Dim returnValue As String

returnValue = instance.GetNextReceiptId(transaction)
```

``` csharp
string GetNextReceiptId(
    IPosTransaction transaction
)
```

``` c++
String^ GetNextReceiptId(
    IPosTransaction^ transaction
)
```

#### Parameters

  - transaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IPosTransaction](ipostransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The next receipt ID.  

## See Also

#### Reference

[IApplicationServiceV1 Interface](iapplicationservicev1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

