---
title: CartLineData.LineIdsLinkedProductMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineIdsLinkedProductMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineIdsLinkedProductMap
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.cartlinedata.lineidslinkedproductmap(v=AX.60)
ms:contentKeyID: 62214294
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartLineData.LineIdsLinkedProductMap
dev_langs:
- CSharp
- C++
- VB
---

# LineIdsLinkedProductMap Property

Gets the line ids and the corresponding linked products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property LineIdsLinkedProductMap As Dictionary(Of String, LinkedProduct)
    Get
    Friend Set
'Usage
Dim instance As CartLineData
Dim value As Dictionary(Of String, LinkedProduct)

value = instance.LineIdsLinkedProductMap
```

``` csharp
[IgnoreDataMemberAttribute]
public Dictionary<string, LinkedProduct> LineIdsLinkedProductMap { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property Dictionary<String^, LinkedProduct^>^ LineIdsLinkedProductMap {
    Dictionary<String^, LinkedProduct^>^ get ();
    internal: void set (Dictionary<String^, LinkedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)), [LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/en-us/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[CartLineData Class](cartlinedata-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

