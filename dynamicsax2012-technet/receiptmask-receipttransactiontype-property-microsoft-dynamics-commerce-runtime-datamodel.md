---
title: ReceiptMask.ReceiptTransactionType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptTransactionType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.ReceiptTransactionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptmask.receipttransactiontype(v=AX.60)
ms:contentKeyID: 62210285
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptMask.ReceiptTransactionType
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptTransactionType Property

Gets the transaction type of the receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECEIPTTRANSTYPE")> _
<DataMemberAttribute> _
Public Property ReceiptTransactionType As ReceiptTransactionType
    Get
    Friend Set
'Usage
Dim instance As ReceiptMask
Dim value As ReceiptTransactionType

value = instance.ReceiptTransactionType
```

``` csharp
[ColumnAttribute("RECEIPTTRANSTYPE")]
[DataMemberAttribute]
public ReceiptTransactionType ReceiptTransactionType { get; internal set; }
```

``` c++
[ColumnAttribute(L"RECEIPTTRANSTYPE")]
[DataMemberAttribute]
public:
property ReceiptTransactionType ReceiptTransactionType {
    ReceiptTransactionType get ();
    internal: void set (ReceiptTransactionType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReceiptTransactionType](receipttransactiontype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ReceiptMask Class](receiptmask-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

