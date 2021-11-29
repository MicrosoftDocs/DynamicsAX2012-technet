---
title: ProductProperty.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Language
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productproperty.language(v=AX.60)
ms:contentKeyID: 62207903
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductProperty.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the language of this property's value, if text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGE")> _
<DataMemberAttribute> _
Public Property Language As String
    Get
    Friend Set
'Usage
Dim instance As ProductProperty
Dim value As String

value = instance.Language
```

``` csharp
[ColumnAttribute("LANGUAGE")]
[DataMemberAttribute]
public string Language { get; internal set; }
```

``` c++
[ColumnAttribute(L"LANGUAGE")]
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductProperty Class](productproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

