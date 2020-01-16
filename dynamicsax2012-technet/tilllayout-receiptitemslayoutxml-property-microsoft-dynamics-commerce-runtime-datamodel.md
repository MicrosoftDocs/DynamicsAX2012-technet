---
title: TillLayout.ReceiptItemsLayoutXml Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptItemsLayoutXml Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptItemsLayoutXml
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.receiptitemslayoutxml(v=AX.60)
ms:contentKeyID: 62203448
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ReceiptItemsLayoutXml
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptItemsLayoutXml Property

Gets or sets the value of receipt items xml.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("RECEIPTITEMSLAYOUTXML")> _
Public Property ReceiptItemsLayoutXml As String
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As String

value = instance.ReceiptItemsLayoutXml

instance.ReceiptItemsLayoutXml = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("RECEIPTITEMSLAYOUTXML")]
public string ReceiptItemsLayoutXml { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"RECEIPTITEMSLAYOUTXML")]
public:
property String^ ReceiptItemsLayoutXml {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The receipt items xml.  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

