---
title: AttributeProduct.MetadataVersion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MetadataVersion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.MetadataVersion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.attributeproduct.metadataversion(v=AX.60)
ms:contentKeyID: 49825214
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AttributeProduct.MetadataVersion
dev_langs:
- CSharp
- C++
- VB
---

# MetadataVersion Property

Gets the version number of the meta data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("METADATAVERSION")> _
Public Property MetadataVersion As Integer
    Get
    Friend Set
'Usage
Dim instance As AttributeProduct
Dim value As Integer

value = instance.MetadataVersion
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("METADATAVERSION")]
public int MetadataVersion { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"METADATAVERSION")]
public:
property int MetadataVersion {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[AttributeProduct Class](attributeproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

