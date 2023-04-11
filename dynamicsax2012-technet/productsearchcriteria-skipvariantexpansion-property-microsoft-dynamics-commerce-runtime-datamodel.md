---
title: ProductSearchCriteria.SkipVariantExpansion Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SkipVariantExpansion Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.SkipVariantExpansion
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.skipvariantexpansion(v=AX.60)
ms:contentKeyID: 62210149
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.SkipVariantExpansion
dev_langs:
- CSharp
- C++
- VB
---

# SkipVariantExpansion Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether product search should return all applicable variants as part of the product result. In some scenarios like product browsing, where the variants are unnecessary, this flag can be used to improve search performance.

This value is set to false by default if not specified.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SkipVariantExpansion As Boolean
    Get
    Set
'Usage
Dim instance As ProductSearchCriteria
Dim value As Boolean

value = instance.SkipVariantExpansion

instance.SkipVariantExpansion = value
```

``` csharp
[DataMemberAttribute]
public bool SkipVariantExpansion { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool SkipVariantExpansion {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

