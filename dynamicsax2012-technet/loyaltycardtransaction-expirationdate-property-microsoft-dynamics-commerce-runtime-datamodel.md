---
title: LoyaltyCardTransaction.ExpirationDate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationDate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.ExpirationDate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtransaction.expirationdate(v=AX.60)
ms:contentKeyID: 62206438
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.ExpirationDate
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationDate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the expiration date of the earned points.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpirationDate As DateTime
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As DateTime

value = instance.ExpirationDate
```

``` csharp
[DataMemberAttribute]
public DateTime ExpirationDate { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime ExpirationDate {
    DateTime get ();
    internal: void set (DateTime value);
}
```

#### Property Value

Type: [System.DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\))  
Returns [DateTime](https://technet.microsoft.com/library/03ybds8y\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

