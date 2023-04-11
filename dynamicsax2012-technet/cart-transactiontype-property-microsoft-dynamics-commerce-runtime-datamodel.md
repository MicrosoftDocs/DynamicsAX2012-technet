---
title: Cart.TransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.transactiontype(v=AX.60)
ms:contentKeyID: 65321053
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.TransactionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TYPE")> _
Public Property TransactionType As SalesTransactionType
    Get
    Set
'Usage
Dim instance As Cart
Dim value As SalesTransactionType

value = instance.TransactionType

instance.TransactionType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TYPE")]
public SalesTransactionType TransactionType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TYPE")]
public:
property SalesTransactionType TransactionType {
    SalesTransactionType get ();
    void set (SalesTransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionType](salestransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

