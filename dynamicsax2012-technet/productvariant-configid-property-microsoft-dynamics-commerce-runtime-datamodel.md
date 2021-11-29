---
title: ProductVariant.ConfigId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ConfigId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ConfigId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.configid(v=AX.60)
ms:contentKeyID: 62213231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.ConfigId
dev_langs:
- CSharp
- C++
- VB
---

# ConfigId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the identifer for the configuration dimension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CONFIGID")> _
Public Property ConfigId As String
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As String

value = instance.ConfigId

instance.ConfigId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CONFIGID")]
public string ConfigId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CONFIGID")]
public:
property String^ ConfigId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

