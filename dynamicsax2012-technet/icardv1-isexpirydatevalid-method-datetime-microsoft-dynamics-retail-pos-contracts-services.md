---
title: ICardV1.IsExpiryDateValid Method (DateTime) (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: IsExpiryDateValid Method (DateTime)
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ICardV1.IsExpiryDateValid(System.DateTime)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.icardv1.isexpirydatevalid(v=AX.60)
ms:contentKeyID: 47344470
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# IsExpiryDateValid Method (DateTime)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Checks for date validity.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function IsExpiryDateValid ( _
    expirationDate As DateTime _
) As Boolean
'Usage
Dim instance As ICardV1
Dim expirationDate As DateTime
Dim returnValue As Boolean

returnValue = instance.IsExpiryDateValid(expirationDate)
```

``` csharp
bool IsExpiryDateValid(
    DateTime expirationDate
)
```

``` c++
bool IsExpiryDateValid(
    DateTime expirationDate
)
```

#### Parameters

  - expirationDate  
    Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
true when the expiration date has not yet passed; otherwise, false.  

## See Also

#### Reference

[ICardV1 Interface](icardv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[IsExpiryDateValid Overload](icardv1-isexpirydatevalid-method-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

