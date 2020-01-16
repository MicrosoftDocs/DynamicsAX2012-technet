---
title: ProductChangeTrackingAnchorSet.EcoResProductVariantConfiguration Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EcoResProductVariantConfiguration Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductVariantConfiguration
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinganchorset.ecoresproductvariantconfiguration(v=AX.60)
ms:contentKeyID: 62210060
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingAnchorSet.EcoResProductVariantConfiguration
dev_langs:
- CSharp
- C++
- VB
---

# EcoResProductVariantConfiguration Property

Gets or sets the sync anchor of the specified data source.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ECORESPRODUCTVARIANTCONFIGURATION")> _
<DataMemberAttribute> _
Public Property EcoResProductVariantConfiguration As Long
    Get
    Set
'Usage
Dim instance As ProductChangeTrackingAnchorSet
Dim value As Long

value = instance.EcoResProductVariantConfiguration

instance.EcoResProductVariantConfiguration = value
```

``` csharp
[ColumnAttribute("ECORESPRODUCTVARIANTCONFIGURATION")]
[DataMemberAttribute]
public long EcoResProductVariantConfiguration { get; set; }
```

``` c++
[ColumnAttribute(L"ECORESPRODUCTVARIANTCONFIGURATION")]
[DataMemberAttribute]
public:
property long long EcoResProductVariantConfiguration {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[ProductChangeTrackingAnchorSet Class](productchangetrackinganchorset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

