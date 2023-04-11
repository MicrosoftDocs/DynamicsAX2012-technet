---
title: ICardV1.TryParseExpiration Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: TryParseExpiration Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.TryParseExpiration(System.String,System.DateTime@)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icardv1.tryparseexpiration(v=AX.60)
ms:contentKeyID: 47344212
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.TryParseExpiration
dev_langs:
- CSharp
- C++
- VB
---

# TryParseExpiration Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Tries to parse an expiration date string to a DateTime

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function TryParseExpiration ( _
    expirationDateString As String, _
    <OutAttribute> ByRef expirationDate As DateTime _
) As Boolean
'Usage
Dim instance As ICardV1
Dim expirationDateString As String
Dim expirationDate As DateTime
Dim returnValue As Boolean

returnValue = instance.TryParseExpiration(expirationDateString, _
    expirationDate)
```

``` csharp
bool TryParseExpiration(
    string expirationDateString,
    out DateTime expirationDate
)
```

``` c++
bool TryParseExpiration(
    String^ expirationDateString, 
    [OutAttribute] DateTime% expirationDate
)
```

#### Parameters

  - expirationDateString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - expirationDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true if conversion successful; otherwise, false.  

## See Also

#### Reference

[ICardV1 Interface](icardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

