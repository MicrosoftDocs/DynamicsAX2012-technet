---
title: TaxDataManager.GetSalesTaxGroups Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetSalesTaxGroups Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetSalesTaxGroups(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.taxdatamanager.getsalestaxgroups(v=AX.60)
ms:contentKeyID: 65322910
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.TaxDataManager.GetSalesTaxGroups
dev_langs:
- CSharp
- C++
- VB
---

# GetSalesTaxGroups Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetSalesTaxGroups ( _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of SalesTaxGroup)
'Usage
Dim instance As TaxDataManager
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of SalesTaxGroup)

returnValue = instance.GetSalesTaxGroups(settings)
```

``` csharp
public ReadOnlyCollection<SalesTaxGroup> GetSalesTaxGroups(
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<SalesTaxGroup^>^ GetSalesTaxGroups(
    QueryResultSettings^ settings
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[SalesTaxGroup](salestaxgroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[TaxDataManager Class](taxdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

