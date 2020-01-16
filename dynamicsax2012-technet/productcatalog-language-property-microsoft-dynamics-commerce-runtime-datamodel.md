---
title: ProductCatalog.Language Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Language Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.Language
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productcatalog.language(v=AX.60)
ms:contentKeyID: 62214385
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductCatalog.Language
dev_langs:
- CSharp
- C++
- VB
---

# Language Property

Gets or sets the catalog translation language.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LANGUAGE")> _
<DataMemberAttribute> _
Public Property Language As String
    Get
    Set
'Usage
Dim instance As ProductCatalog
Dim value As String

value = instance.Language

instance.Language = value
```

``` csharp
[ColumnAttribute("LANGUAGE")]
[DataMemberAttribute]
public string Language { get; set; }
```

``` c++
[ColumnAttribute(L"LANGUAGE")]
[DataMemberAttribute]
public:
property String^ Language {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductCatalog Class](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

