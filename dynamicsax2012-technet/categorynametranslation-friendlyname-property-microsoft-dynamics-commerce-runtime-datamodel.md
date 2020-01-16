---
title: CategoryNameTranslation.FriendlyName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FriendlyName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CategoryNameTranslation.FriendlyName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.categorynametranslation.friendlyname(v=AX.60)
ms:contentKeyID: 49826184
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CategoryNameTranslation.FriendlyName
dev_langs:
- CSharp
- C++
- VB
---

# FriendlyName Property

Gets the translated text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FRIENDLYNAME")> _
Public Property FriendlyName As String
    Get
    Friend Set
'Usage
Dim instance As CategoryNameTranslation
Dim value As String

value = instance.FriendlyName
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FRIENDLYNAME")]
public string FriendlyName { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FRIENDLYNAME")]
public:
property String^ FriendlyName {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CategoryNameTranslation Class](categorynametranslation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

