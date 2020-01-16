---
title: ReceiptInfo.Title Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Title Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.Title
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receiptinfo.title(v=AX.60)
ms:contentKeyID: 62209731
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptInfo.Title
dev_langs:
- CSharp
- C++
- VB
---

# Title Property

Gets or sets the title of a receipt template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TITLE")> _
<DataMemberAttribute> _
Public Property Title As String
    Get
    Set
'Usage
Dim instance As ReceiptInfo
Dim value As String

value = instance.Title

instance.Title = value
```

``` csharp
[ColumnAttribute("TITLE")]
[DataMemberAttribute]
public string Title { get; set; }
```

``` c++
[ColumnAttribute(L"TITLE")]
[DataMemberAttribute]
public:
property String^ Title {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ReceiptInfo Class](receiptinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

