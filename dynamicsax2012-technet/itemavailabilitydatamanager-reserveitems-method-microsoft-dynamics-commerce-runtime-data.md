---
title: ItemAvailabilityDataManager.ReserveItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReserveItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.ReserveItems(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemReservation})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.itemavailabilitydatamanager.reserveitems(v=AX.60)
ms:contentKeyID: 49830720
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.ReserveItems
dev_langs:
- CSharp
- C++
- VB
---

# ReserveItems Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Reserve items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub ReserveItems ( _
    itemReservations As IEnumerable(Of ItemReservation) _
)
'Usage
Dim instance As ItemAvailabilityDataManager
Dim itemReservations As IEnumerable(Of ItemReservation)

instance.ReserveItems(itemReservations)
```

``` csharp
public void ReserveItems(
    IEnumerable<ItemReservation> itemReservations
)
```

``` c++
public:
void ReserveItems(
    IEnumerable<ItemReservation^>^ itemReservations
)
```

#### Parameters

  - itemReservations  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemReservation](itemreservation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[ItemAvailabilityDataManager Class](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

