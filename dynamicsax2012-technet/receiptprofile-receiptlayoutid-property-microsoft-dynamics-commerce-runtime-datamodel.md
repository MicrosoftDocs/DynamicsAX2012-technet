---
title: ReceiptProfile.ReceiptLayoutId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptLayoutId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ReceiptLayoutId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.receiptprofile.receiptlayoutid(v=AX.60)
ms:contentKeyID: 62208934
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptProfile.ReceiptLayoutId
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptLayoutId Property

Gets or sets the formalayoutId of a receipt.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FORMLAYOUTID")> _
Public Property ReceiptLayoutId As String
    Get
    Set
'Usage
Dim instance As ReceiptProfile
Dim value As String

value = instance.ReceiptLayoutId

instance.ReceiptLayoutId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FORMLAYOUTID")]
public string ReceiptLayoutId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FORMLAYOUTID")]
public:
property String^ ReceiptLayoutId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptProfile Class](receiptprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

