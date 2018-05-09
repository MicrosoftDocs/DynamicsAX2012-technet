---
title: ProductDimensionValueDictionary Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductDimensionValueDictionary Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueDictionary
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionvaluedictionary(v=AX.60)
ms:contentKeyID: 62211297
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueDictionary
dev_langs:
- CSharp
- C++
- VB
---

# ProductDimensionValueDictionary Class

Represents an association of a dimension's value and the set of variants which have this value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<CollectionDataContractAttribute(Name := "ProductDimensionValueDictionary", ItemName := "Entry",  _
    KeyName := "DimensionValue", ValueName := "SetOfVariantIds")> _
Public NotInheritable Class ProductDimensionValueDictionary _
    Inherits Dictionary(Of String, ISet(Of Long))
'Usage
Dim instance As ProductDimensionValueDictionary
```

``` csharp
[CollectionDataContractAttribute(Name = "ProductDimensionValueDictionary", ItemName = "Entry", 
    KeyName = "DimensionValue", ValueName = "SetOfVariantIds")]
public sealed class ProductDimensionValueDictionary : Dictionary<string, ISet<long>>
```

``` c++
[CollectionDataContractAttribute(Name = L"ProductDimensionValueDictionary", ItemName = L"Entry", 
    KeyName = L"DimensionValue", ValueName = L"SetOfVariantIds")]
public ref class ProductDimensionValueDictionary sealed : public Dictionary<String^, ISet<long long>^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [ISet](https://technet.microsoft.com/en-us/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))\>\>  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionValueDictionary  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

