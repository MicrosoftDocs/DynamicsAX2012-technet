---
title: ProductLookupClause Constructor (String, String) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductLookupClause Constructor (String, String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductLookupClause.#ctor(System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productlookupclause.productlookupclause(v=AX.60)
ms:contentKeyID: 62214685
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductLookupClause Constructor (String, String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [ProductLookupClause](productlookupclause-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    itemId As String, _
    inventDimId As String _
)
'Usage
Dim itemId As String
Dim inventDimId As String

Dim instance As New ProductLookupClause(itemId, _
    inventDimId)
```

``` csharp
public ProductLookupClause(
    string itemId,
    string inventDimId
)
```

``` c++
public:
ProductLookupClause(
    String^ itemId, 
    String^ inventDimId
)
```

#### Parameters

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[ProductLookupClause Class](productlookupclause-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductLookupClause Overload](productlookupclause-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

