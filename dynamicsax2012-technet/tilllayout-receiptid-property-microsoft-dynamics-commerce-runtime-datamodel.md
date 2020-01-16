---
title: TillLayout.ReceiptId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.receiptid(v=AX.60)
ms:contentKeyID: 62204730
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptId Property

Gets or sets the value of receipt identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("RECEIPTID")> _
<DataMemberAttribute> _
Public Property ReceiptId As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.ReceiptId

instance.ReceiptId = value
```

``` csharp
[ColumnAttribute("RECEIPTID")]
[DataMemberAttribute]
public string ReceiptId { get; set; }
```

``` c++
[ColumnAttribute(L"RECEIPTID")]
[DataMemberAttribute]
public:
property String^ ReceiptId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The receipt identifier.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

