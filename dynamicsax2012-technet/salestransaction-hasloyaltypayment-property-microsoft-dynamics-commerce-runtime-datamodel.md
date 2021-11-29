---
title: SalesTransaction.HasLoyaltyPayment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: HasLoyaltyPayment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.HasLoyaltyPayment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction.hasloyaltypayment(v=AX.60)
ms:contentKeyID: 62211196
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction.HasLoyaltyPayment
dev_langs:
- CSharp
- C++
- VB
---

# HasLoyaltyPayment Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the transaction has any posted loyalty tender.

This property is populated only after the transaction is committed.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("HASLOYALTYPAYMENT")> _
Public Property HasLoyaltyPayment As Boolean
    Get
    Set
'Usage
Dim instance As SalesTransaction
Dim value As Boolean

value = instance.HasLoyaltyPayment

instance.HasLoyaltyPayment = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("HASLOYALTYPAYMENT")]
public bool HasLoyaltyPayment { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"HASLOYALTYPAYMENT")]
public:
property bool HasLoyaltyPayment {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesTransaction Class](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

