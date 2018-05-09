---
title: Printer.ReceiptType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.printer.receipttype(v=AX.60)
ms:contentKeyID: 62207416
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptType
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptType Property

Gets or sets the receipttype of the receipt template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTTYPE")> _
Public Property ReceiptType As ReceiptType
    Get
    Set
'Usage
Dim instance As Printer
Dim value As ReceiptType

value = instance.ReceiptType

instance.ReceiptType = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTTYPE")]
public ReceiptType ReceiptType { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTTYPE")]
public:
property ReceiptType ReceiptType {
    ReceiptType get ();
    void set (ReceiptType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReceiptType](receipttype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

