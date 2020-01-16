---
title: ICardV1.IsCardLengthValid Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsCardLengthValid Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.IsCardLengthValid(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icardv1.iscardlengthvalid(v=AX.60)
ms:contentKeyID: 47344407
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.IsCardLengthValid
dev_langs:
- CSharp
- C++
- VB
---

# IsCardLengthValid Method

Checks to determine whether entered card number is of a valid length.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsCardLengthValid ( _
    cardNumber As String _
) As Boolean
'Usage
Dim instance As ICardV1
Dim cardNumber As String
Dim returnValue As Boolean

returnValue = instance.IsCardLengthValid(cardNumber)
```

``` csharp
bool IsCardLengthValid(
    string cardNumber
)
```

``` c++
bool IsCardLengthValid(
    String^ cardNumber
)
```

#### Parameters

  - cardNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true when the length of the card number is in the given limits; otherwise, false.  

## See Also

#### Reference

[ICardV1 Interface](icardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

