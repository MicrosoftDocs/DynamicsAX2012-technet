---
title: ProductAttributeSchemaEntry.FriendlyNameLanguage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FriendlyNameLanguage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.FriendlyNameLanguage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productattributeschemaentry.friendlynamelanguage(v=AX.60)
ms:contentKeyID: 65320725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductAttributeSchemaEntry.FriendlyNameLanguage
dev_langs:
- CSharp
- C++
- VB
---

# FriendlyNameLanguage Property

Gets or sets the friendly name associated with this attribute.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGE")> _
<DataMemberAttribute> _
Public Property FriendlyNameLanguage As String
    Get
    Set
'Usage
Dim instance As ProductAttributeSchemaEntry
Dim value As String

value = instance.FriendlyNameLanguage

instance.FriendlyNameLanguage = value
```

``` csharp
[ColumnAttribute("LANGUAGE")]
[DataMemberAttribute]
public string FriendlyNameLanguage { get; set; }
```

``` c++
[ColumnAttribute(L"LANGUAGE")]
[DataMemberAttribute]
public:
property String^ FriendlyNameLanguage {
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

