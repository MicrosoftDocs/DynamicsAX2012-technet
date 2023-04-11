---
title: SalesLine.LineIdsLinkedProductMap Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LineIdsLinkedProductMap Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineIdsLinkedProductMap
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.lineidslinkedproductmap(v=AX.60)
ms:contentKeyID: 62214386
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.LineIdsLinkedProductMap
dev_langs:
- CSharp
- C++
- VB
---

# LineIdsLinkedProductMap Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the line ids and the corresponding linked products.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LineIdsLinkedProductMap As Dictionary(Of String, LinkedProduct)
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Dictionary(Of String, LinkedProduct)

value = instance.LineIdsLinkedProductMap

instance.LineIdsLinkedProductMap = value
```

``` csharp
[DataMemberAttribute]
public Dictionary<string, LinkedProduct> LineIdsLinkedProductMap { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Dictionary<String^, LinkedProduct^>^ LineIdsLinkedProductMap {
    Dictionary<String^, LinkedProduct^>^ get ();
    void set (Dictionary<String^, LinkedProduct^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.Dictionary](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)), [LinkedProduct](linkedproduct-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [Dictionary\<TKey, TValue\>](https://technet.microsoft.com/library/xfhwa508\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

