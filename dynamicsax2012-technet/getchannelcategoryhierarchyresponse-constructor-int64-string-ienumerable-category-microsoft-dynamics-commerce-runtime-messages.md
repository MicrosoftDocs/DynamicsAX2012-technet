---
title: GetChannelCategoryHierarchyResponse Constructor (Int64, String, IEnumerable(Category)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetChannelCategoryHierarchyResponse Constructor (Int64, String, IEnumerable(Category))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelCategoryHierarchyResponse.#ctor(System.Int64,System.String,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.Category})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchannelcategoryhierarchyresponse.getchannelcategoryhierarchyresponse(v=AX.60)
ms:contentKeyID: 49855221
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetChannelCategoryHierarchyResponse Constructor (Int64, String, IEnumerable(Category))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetChannelCategoryHierarchyResponse](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    hierarchyName As String, _
    categories As IEnumerable(Of Category) _
)
'Usage
Dim channelId As Long
Dim hierarchyName As String
Dim categories As IEnumerable(Of Category)

Dim instance As New GetChannelCategoryHierarchyResponse(channelId, _
    hierarchyName, categories)
```

``` csharp
public GetChannelCategoryHierarchyResponse(
    long channelId,
    string hierarchyName,
    IEnumerable<Category> categories
)
```

``` c++
public:
GetChannelCategoryHierarchyResponse(
    long long channelId, 
    String^ hierarchyName, 
    IEnumerable<Category^>^ categories
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - hierarchyName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - categories  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[Category](category-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetChannelCategoryHierarchyResponse Class](getchannelcategoryhierarchyresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetChannelCategoryHierarchyResponse Overload](getchannelcategoryhierarchyresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

