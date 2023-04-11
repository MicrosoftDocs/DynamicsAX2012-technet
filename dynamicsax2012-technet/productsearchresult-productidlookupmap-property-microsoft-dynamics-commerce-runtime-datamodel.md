---
title: ProductSearchResult.ProductIdLookupMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductIdLookupMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult.ProductIdLookupMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchresult.productidlookupmap(v=AX.60)
ms:contentKeyID: 62213058
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult.ProductIdLookupMap
dev_langs:
- CSharp
- C++
- VB
---

# ProductIdLookupMap Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a lookup map of product id to parent product id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property ProductIdLookupMap As Dictionary(Of Long, Long)
    Get
    Set
'Usage
Dim instance As ProductSearchResult
Dim value As Dictionary(Of Long, Long)

value = instance.ProductIdLookupMap

instance.ProductIdLookupMap = value
```

``` csharp
[IgnoreDataMemberAttribute]
public Dictionary<long, long> ProductIdLookupMap { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Dictionary<long long, long long>^ ProductIdLookupMap {
    Dictionary<long long, long long>^ get ();
    void set (Dictionary<long long, long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)), [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchResult Class](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

