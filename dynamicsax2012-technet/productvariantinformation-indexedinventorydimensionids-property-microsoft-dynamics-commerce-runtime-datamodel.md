---
title: ProductVariantInformation.IndexedInventoryDimensionIds Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedInventoryDimensionIds Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedInventoryDimensionIds
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariantinformation.indexedinventorydimensionids(v=AX.60)
ms:contentKeyID: 65320957
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariantInformation.IndexedInventoryDimensionIds
dev_langs:
- CSharp
- C++
- VB
---

# IndexedInventoryDimensionIds Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedInventoryDimensionIds As Dictionary(Of String, Long)
    Get
    Friend Set
'Usage
Dim instance As ProductVariantInformation
Dim value As Dictionary(Of String, Long)

value = instance.IndexedInventoryDimensionIds
```

``` csharp
[IgnoreDataMemberAttribute]
public Dictionary<string, long> IndexedInventoryDimensionIds { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Dictionary<String^, long long>^ IndexedInventoryDimensionIds {
    Dictionary<String^, long long>^ get ();
    internal: void set (Dictionary<String^, long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>  

## See Also

#### Reference

[ProductVariantInformation Class](productvariantinformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

