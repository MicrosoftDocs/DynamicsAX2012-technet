---
title: ShiftTenderLine.TransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.transactiontype(v=AX.60)
ms:contentKeyID: 62211860
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.TransactionType
dev_langs:
- CSharp
- C++
- VB
---

# TransactionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the transaction type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("TRANSACTIONTYPE")> _
Public Property TransactionType As TransactionType
    Get
    Set
'Usage
Dim instance As ShiftTenderLine
Dim value As TransactionType

value = instance.TransactionType

instance.TransactionType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("TRANSACTIONTYPE")]
public TransactionType TransactionType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"TRANSACTIONTYPE")]
public:
property TransactionType TransactionType {
    TransactionType get ();
    void set (TransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [TransactionType](transactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

