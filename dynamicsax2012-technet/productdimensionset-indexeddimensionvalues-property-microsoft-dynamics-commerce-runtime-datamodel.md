---
title: ProductDimensionSet.IndexedDimensionValues Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IndexedDimensionValues Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.IndexedDimensionValues
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productdimensionset.indexeddimensionvalues(v=AX.60)
ms:contentKeyID: 62206704
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductDimensionSet.IndexedDimensionValues
dev_langs:
- CSharp
- C++
- VB
---

# IndexedDimensionValues Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the indexed set of values of this dimension for the current product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property IndexedDimensionValues As Dictionary(Of String, ISet(Of Long))
    Get
    Friend Set
'Usage
Dim instance As ProductDimensionSet
Dim value As Dictionary(Of String, ISet(Of Long))

value = instance.IndexedDimensionValues
```

``` csharp
[IgnoreDataMemberAttribute]
public Dictionary<string, ISet<long>> IndexedDimensionValues { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Dictionary<String^, ISet<long long>^>^ IndexedDimensionValues {
    Dictionary<String^, ISet<long long>^>^ get ();
    internal: void set (Dictionary<String^, ISet<long long>^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [ISet](https://technet.microsoft.com/library/dd412081\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[ProductDimensionSet Class](productdimensionset-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

