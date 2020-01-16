---
title: ProductAttributeSchemaEntry.FriendlyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FriendlyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.FriendlyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.friendlyname(v=AX.60)
ms:contentKeyID: 65315536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.FriendlyName
dev_langs:
- CSharp
- C++
- VB
---

# FriendlyName Property

Gets or sets the friendly name of the attribute suitable for display to the end user.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FRIENDLYNAME")> _
Public Property FriendlyName As String
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As String

value = instance.FriendlyName

instance.FriendlyName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FRIENDLYNAME")]
public string FriendlyName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FRIENDLYNAME")]
public:
property String^ FriendlyName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductAttributeSchemaEntry Class](productattributeschemaentry-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

