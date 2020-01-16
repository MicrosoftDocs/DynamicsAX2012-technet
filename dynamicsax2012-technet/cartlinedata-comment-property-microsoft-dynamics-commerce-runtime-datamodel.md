---
title: CartLineData.Comment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Comment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Comment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.comment(v=AX.60)
ms:contentKeyID: 62215060
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.Comment
dev_langs:
- CSharp
- C++
- VB
---

# Comment Property

Gets or sets the line comment.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMMENT")> _
<DataMemberAttribute> _
Public Property Comment As String
    Get
    Set
'Usage
Dim instance As CartLineData
Dim value As String

value = instance.Comment

instance.Comment = value
```

``` csharp
[ColumnAttribute("COMMENT")]
[DataMemberAttribute]
public string Comment { get; set; }
```

``` c++
[ColumnAttribute(L"COMMENT")]
[DataMemberAttribute]
public:
property String^ Comment {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The line comment.  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

