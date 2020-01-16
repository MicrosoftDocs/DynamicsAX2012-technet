---
title: Printer.ReceiptLayoutId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptLayoutId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptLayoutId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.printer.receiptlayoutid(v=AX.60)
ms:contentKeyID: 62212245
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Printer.ReceiptLayoutId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptLayoutId Property

Gets or sets the formlayoutid of the receipt template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("FORMLAYOUTID")> _
<DataMemberAttribute> _
Public Property ReceiptLayoutId As String
    Get
    Set
'Usage
Dim instance As Printer
Dim value As String

value = instance.ReceiptLayoutId

instance.ReceiptLayoutId = value
```

``` csharp
[ColumnAttribute("FORMLAYOUTID")]
[DataMemberAttribute]
public string ReceiptLayoutId { get; set; }
```

``` c++
[ColumnAttribute(L"FORMLAYOUTID")]
[DataMemberAttribute]
public:
property String^ ReceiptLayoutId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Printer Class](printer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

