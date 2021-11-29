---
title: ProductSearchCriteria Constructor (Int64, Int64) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductSearchCriteria Constructor (Int64, Int64)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchCriteria.#ctor(System.Int64,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productsearchcriteria.productsearchcriteria(v=AX.60)
ms:contentKeyID: 62214228
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductSearchCriteria Constructor (Int64, Int64)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductSearchCriteria](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    catalogId As Long _
)
'Usage
Dim channelId As Long
Dim catalogId As Long

Dim instance As New ProductSearchCriteria(channelId, _
    catalogId)
```

``` csharp
public ProductSearchCriteria(
    long channelId,
    long catalogId
)
```

``` c++
public:
ProductSearchCriteria(
    long long channelId, 
    long long catalogId
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - catalogId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

## See Also

#### Reference

[ProductSearchCriteria Class](productsearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductSearchCriteria Overload](productsearchcriteria-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

