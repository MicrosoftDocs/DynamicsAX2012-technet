---
title: AttributeProduct.Metadata Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Metadata Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.Metadata
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.attributeproduct.metadata(v=AX.60)
ms:contentKeyID: 49843007
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.Metadata
dev_langs:
- CSharp
- C++
- VB
---

# Metadata Property

Gets the meta data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("METADATA")> _
Public Property Metadata As String
    Get
    Friend Set
'Usage
Dim instance As AttributeProduct
Dim value As String

value = instance.Metadata
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("METADATA")]
public string Metadata { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"METADATA")]
public:
property String^ Metadata {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[AttributeProduct Class](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

