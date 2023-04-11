---
title: TaxL2CacheDataStoreAccessor.GetSalesTaxGroup Method (QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetSalesTaxGroup Method (QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.GetSalesTaxGroup(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.getsalestaxgroup(v=AX.60)
ms:contentKeyID: 65318395
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetSalesTaxGroup Method (QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesTaxGroup ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of SalesTaxGroup)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of SalesTaxGroup)

returnValue = instance.GetSalesTaxGroup(settings)
```

``` csharp
public ReadOnlyCollection<SalesTaxGroup> GetSalesTaxGroup(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<SalesTaxGroup^>^ GetSalesTaxGroup(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[GetSalesTaxGroup Overload](taxl2cachedatastoreaccessor-getsalestaxgroup-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

