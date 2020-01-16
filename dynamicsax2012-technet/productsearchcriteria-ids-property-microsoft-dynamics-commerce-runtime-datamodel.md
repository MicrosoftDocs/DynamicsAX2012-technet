---
title: ProductSearchCriteria.Ids Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Ids Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Ids
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.ids(v=AX.60)
ms:contentKeyID: 62210097
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.Ids
dev_langs:
- CSharp
- C++
- VB
---

# Ids Property

Gets or sets the ids of the products which are to be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Ids As IList(Of Long)
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As IList(Of Long)

value = instance.Ids

instance.Ids = value
```

``` csharp
[DataMemberAttribute]
public IList<long> Ids { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IList<long long>^ Ids {
    IList<long long>^ get ();
    void set (IList<long long>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IList](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [IList\<T\>](https://technet.microsoft.com/library/5y536ey6\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

