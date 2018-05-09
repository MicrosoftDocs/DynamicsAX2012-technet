---
title: ChannelCategoryAttribute.CategoryPath Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryPath Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryPath
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.categorypath(v=AX.60)
ms:contentKeyID: 65322201
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryPath
dev_langs:
- CSharp
- C++
- VB
---

# CategoryPath Property

Gets or sets the category path.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CATEGORYPATH")> _
Public Property CategoryPath As String
    Get
    Set
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As String

value = instance.CategoryPath

instance.CategoryPath = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CATEGORYPATH")]
public string CategoryPath { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CATEGORYPATH")]
public:
property String^ CategoryPath {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

