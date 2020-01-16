---
title: SalesTransaction.TransactionTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TransactionTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.transactiontypevalue(v=AX.60)
ms:contentKeyID: 62206164
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.TransactionTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# TransactionTypeValue Property

Gets or sets the value of the TransactionType. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionTypeValue As Integer
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Integer

value = instance.TransactionTypeValue

instance.TransactionTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int TransactionTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int TransactionTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

