---
title: TaxL2CacheDataStoreAccessor.PutSalesTaxGroup Method (QueryResultSettings, ReadOnlyCollection(SalesTaxGroup)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: PutSalesTaxGroup Method (QueryResultSettings, ReadOnlyCollection(SalesTaxGroup))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxL2CacheDataStoreAccessor.PutSalesTaxGroup(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.ObjectModel.ReadOnlyCollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTaxGroup})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxl2cachedatastoreaccessor.putsalestaxgroup(v=AX.60)
ms:contentKeyID: 65320532
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# PutSalesTaxGroup Method (QueryResultSettings, ReadOnlyCollection(SalesTaxGroup))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub PutSalesTaxGroup ( _
    settings As QueryResultSettings, _
    result As ReadOnlyCollection(Of SalesTaxGroup) _
)
'Usage
Dim instance As TaxL2CacheDataStoreAccessor
Dim settings As QueryResultSettings
Dim result As ReadOnlyCollection(Of SalesTaxGroup)

instance.PutSalesTaxGroup(settings, result)
```

``` csharp
public void PutSalesTaxGroup(
    QueryResultSettings settings,
    ReadOnlyCollection<SalesTaxGroup> result
)
```

``` c++
public:
void PutSalesTaxGroup(
    QueryResultSettings^ settings, 
    ReadOnlyCollection<SalesTaxGroup^>^ result
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - result  
    Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TaxL2CacheDataStoreAccessor Class](taxl2cachedatastoreaccessor-class-microsoft-dynamics-commerce-runtime-data.md)

[PutSalesTaxGroup Overload](taxl2cachedatastoreaccessor-putsalestaxgroup-method-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

