---
title: LoyaltyCardTransaction.EntryDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EntryDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.EntryDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtransaction.entrydatetime(v=AX.60)
ms:contentKeyID: 62209429
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.EntryDateTime
dev_langs:
- CSharp
- C++
- VB
---

# EntryDateTime Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the entry date time of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property EntryDateTime As DateTime
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As DateTime

value = instance.EntryDateTime
```

``` csharp
[DataMemberAttribute]
public DateTime EntryDateTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property DateTime EntryDateTime {
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

