---
title: ICardV1.IsExpiryDateValid Method (String) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsExpiryDateValid Method (String)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.IsExpiryDateValid(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icardv1.isexpirydatevalid(v=AX.60)
ms:contentKeyID: 47343826
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IsExpiryDateValid Method (String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks for date validity.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsExpiryDateValid ( _
    expirationDateString As String _
) As Boolean
'Usage
Dim instance As ICardV1
Dim expirationDateString As String
Dim returnValue As Boolean

returnValue = instance.IsExpiryDateValid(expirationDateString)
```

``` csharp
bool IsExpiryDateValid(
    string expirationDateString
)
```

``` c++
bool IsExpiryDateValid(
    String^ expirationDateString
)
```

#### Parameters

  - expirationDateString  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true when the expiry date has not yet passed; otherwise, false.  

## See Also

#### Reference

[ICardV1 Interface](icardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[IsExpiryDateValid Overload](icardv1-isexpirydatevalid-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

