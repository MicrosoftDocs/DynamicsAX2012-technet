---
title: ItemAvailabilityDataManager.GetItemAvailabilitiesByItemQuantities Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: GetItemAvailabilitiesByItemQuantities Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItemQuantities(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity},System.String,System.Int32,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemavailabilitydatamanager.getitemavailabilitiesbyitemquantities(v=AX.60)
ms:contentKeyID: 65321963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.GetItemAvailabilitiesByItemQuantities
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemQuantities Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Function GetItemAvailabilitiesByItemQuantities ( _
    itemQuantities As IEnumerable(Of ItemQuantity), _
    customerAccountNumber As String, _
    maxWarehousesPerItem As Integer, _
    settings As QueryResultSettings _
) As ReadOnlyCollection(Of ItemAvailability)
'Usage
Dim instance As ItemAvailabilityDataManager
Dim itemQuantities As IEnumerable(Of ItemQuantity)
Dim customerAccountNumber As String
Dim maxWarehousesPerItem As Integer
Dim settings As QueryResultSettings
Dim returnValue As ReadOnlyCollection(Of ItemAvailability)

returnValue = instance.GetItemAvailabilitiesByItemQuantities(itemQuantities, _
    customerAccountNumber, maxWarehousesPerItem, _
    settings)
```

``` csharp
public ReadOnlyCollection<ItemAvailability> GetItemAvailabilitiesByItemQuantities(
    IEnumerable<ItemQuantity> itemQuantities,
    string customerAccountNumber,
    int maxWarehousesPerItem,
    QueryResultSettings settings
)
```

``` c++
public:
ReadOnlyCollection<ItemAvailability^>^ GetItemAvailabilitiesByItemQuantities(
    IEnumerable<ItemQuantity^>^ itemQuantities, 
    String^ customerAccountNumber, 
    int maxWarehousesPerItem, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - itemQuantities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxWarehousesPerItem  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[ItemAvailability](itemavailability-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemAvailabilityDataManager Class](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

