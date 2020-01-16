---
title: ProductManager.GetProductCatalogs Method (Int64, Boolean, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Client)
TOCTitle: GetProductCatalogs Method (Int64, Boolean, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Client.ProductManager.GetProductCatalogs(System.Int64,System.Boolean,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.client.productmanager.getproductcatalogs(v=AX.60)
ms:contentKeyID: 65323001
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetProductCatalogs Method (Int64, Boolean, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Client](microsoft-dynamics-commerce-runtime-client-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Client (in Microsoft.Dynamics.Commerce.Runtime.Client.dll)

## Syntax

``` vb
'Declaration
Public Function GetProductCatalogs ( _
    channelId As Long, _
    activeOnly As Boolean, _
    settings As QueryResultSettings _
) As PagedResult(Of ProductCatalog)
'Usage
Dim instance As ProductManager
Dim channelId As Long
Dim activeOnly As Boolean
Dim settings As QueryResultSettings
Dim returnValue As PagedResult(Of ProductCatalog)

returnValue = instance.GetProductCatalogs(channelId, _
    activeOnly, settings)
```

``` csharp
public PagedResult<ProductCatalog> GetProductCatalogs(
    long channelId,
    bool activeOnly,
    QueryResultSettings settings
)
```

``` c++
public:
PagedResult<ProductCatalog^>^ GetProductCatalogs(
    long long channelId, 
    bool activeOnly, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - activeOnly  
    Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [Microsoft.Dynamics.Commerce.Runtime.PagedResult](pagedresult-tentity-class-microsoft-dynamics-commerce-runtime.md)\<[ProductCatalog](productcatalog-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ProductManager Class](productmanager-class-microsoft-dynamics-commerce-runtime-client.md)

[GetProductCatalogs Overload](productmanager-getproductcatalogs-method-microsoft-dynamics-commerce-runtime-client.md)

[Microsoft.Dynamics.Commerce.Runtime.Client Namespace](microsoft-dynamics-commerce-runtime-client-namespace.md)

