---
title: ISalesOrderV1.CreatePackingSlip Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: CreatePackingSlip Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CreatePackingSlip(System.Boolean@,System.String@,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.createpackingslip(v=AX.60)
ms:contentKeyID: 47343864
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.CreatePackingSlip
dev_langs:
- CSharp
- C++
- VB
---

# CreatePackingSlip Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Creates a packing slip.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub CreatePackingSlip ( _
    <OutAttribute> ByRef retValue As Boolean, _
    <OutAttribute> ByRef comment As String, _
    salesId As String _
)
'Usage
Dim instance As ISalesOrderV1
Dim retValue As Boolean
Dim comment As String
Dim salesId As String

instance.CreatePackingSlip(retValue, _
    comment, salesId)
```

``` csharp
void CreatePackingSlip(
    out bool retValue,
    out string comment,
    string salesId
)
```

``` c++
void CreatePackingSlip(
    [OutAttribute] bool% retValue, 
    [OutAttribute] String^% comment, 
    String^ salesId
)
```

#### Parameters

  - retValue  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - comment  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - salesId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

