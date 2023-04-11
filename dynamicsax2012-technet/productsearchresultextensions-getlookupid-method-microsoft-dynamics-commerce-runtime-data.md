---
title: ProductSearchResultExtensions.GetLookupId Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetLookupId Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ProductSearchResultExtensions.GetLookupId(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.productsearchresultextensions.getlookupid(v=AX.60)
ms:contentKeyID: 65318988
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ProductSearchResultExtensions.GetLookupId
dev_langs:
- CSharp
- C++
- VB
---

# GetLookupId Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the standalone or master identifier based on productId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Data (in Microsoft.Dynamics.Commerce.Runtime.Data.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function GetLookupId ( _
    result As ProductSearchResult, _
    productId As Long _
) As Long
'Usage
Dim result As ProductSearchResult
Dim productId As Long
Dim returnValue As Long

returnValue = result.GetLookupId(productId)
```

``` csharp
public static long GetLookupId(
    this ProductSearchResult result,
    long productId
)
```

``` c++
[ExtensionAttribute]
public:
static long long GetLookupId(
    ProductSearchResult^ result, 
    long long productId
)
```

#### Parameters

  - result  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - productId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns the master product identifier for the productId, or productId otherwise.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ProductSearchResult](productsearchresult-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ProductSearchResultExtensions Class](productsearchresultextensions-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

