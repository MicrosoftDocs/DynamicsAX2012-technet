---
title: LoyaltyCardTransaction.TransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycardtransaction.transactionid(v=AX.60)
ms:contentKeyID: 62212250
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTransaction.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifier of the transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionId As String
    Get
    Friend Set
'Usage
Dim instance As LoyaltyCardTransaction
Dim value As String

value = instance.TransactionId
```

``` csharp
[DataMemberAttribute]
public string TransactionId { get; internal set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TransactionId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCardTransaction Class](loyaltycardtransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

