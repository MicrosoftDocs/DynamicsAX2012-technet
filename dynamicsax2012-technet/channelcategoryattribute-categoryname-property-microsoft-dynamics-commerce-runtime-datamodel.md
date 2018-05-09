---
title: ChannelCategoryAttribute.CategoryName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CategoryName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelcategoryattribute.categoryname(v=AX.60)
ms:contentKeyID: 65318437
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelCategoryAttribute.CategoryName
dev_langs:
- CSharp
- C++
- VB
---

# CategoryName Property

Gets the category name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATEGORYNAME")> _
Public Property CategoryName As String
    Get
    Friend Set
'Usage
Dim instance As ChannelCategoryAttribute
Dim value As String

value = instance.CategoryName
```

``` csharp
[ColumnAttribute("CATEGORYNAME")]
public string CategoryName { get; internal set; }
```

``` c++
[ColumnAttribute(L"CATEGORYNAME")]
public:
property String^ CategoryName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelCategoryAttribute Class](channelcategoryattribute-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

