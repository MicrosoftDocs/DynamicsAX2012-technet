---
title: ItemAvailabilityDataManager.GetItemAvailabilitiesByItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemAvailabilitiesByItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItems(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension},System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.itemavailabilitydatamanager.getitemavailabilitiesbyitems(v=AX.60)
ms:contentKeyID: 65318250
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItems
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItems Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemAvailabilitiesByItems ( _
    items As IEnumerable(Of ItemVariantInventoryDimension), _
    customerAccountNumber As String, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ItemAvailability)
'Usage
Dim instance As ItemAvailabilityDataManager
Dim items As IEnumerable(Of ItemVariantInventoryDimension)
Dim customerAccountNumber As String
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ItemAvailability)

returnValue = instance.GetItemAvailabilitiesByItems(items, _
    customerAccountNumber, settings)
```

``` csharp
public ReadOnlyCollection<ItemAvailability> GetItemAvailabilitiesByItems(
    IEnumerable<ItemVariantInventoryDimension> items,
    string customerAccountNumber,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ItemAvailability^>^ GetItemAvailabilitiesByItems(
    IEnumerable<ItemVariantInventoryDimension^>^ items, 
    String^ customerAccountNumber, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/en-us/library/ms132474\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemAvailabilityDataManager Class](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

