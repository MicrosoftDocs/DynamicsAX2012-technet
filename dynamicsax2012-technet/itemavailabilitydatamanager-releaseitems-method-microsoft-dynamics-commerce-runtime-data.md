---
title: ItemAvailabilityDataManager.ReleaseItems Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: ReleaseItems Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.ReleaseItems(System.Collections.Generic.IEnumerable{System.Guid})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.itemavailabilitydatamanager.releaseitems(v=AX.60)
ms:contentKeyID: 49856578
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.ItemAvailabilityDataManager.ReleaseItems
dev_langs:
- CSharp
- C++
- VB
---

# ReleaseItems Method

Release items.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Public Sub ReleaseItems ( _
    reservationIds As IEnumerable(Of Guid) _
)
'Usage
Dim instance As ItemAvailabilityDataManager
Dim reservationIds As IEnumerable(Of Guid)

instance.ReleaseItems(reservationIds)
```

``` csharp
public void ReleaseItems(
    IEnumerable<Guid> reservationIds
)
```

``` c++
public:
void ReleaseItems(
    IEnumerable<Guid>^ reservationIds
)
```

#### Parameters

  - reservationIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[Guid](https://technet.microsoft.com/en-us/library/cey1zx63\(v=ax.60\))\>  

## See Also

#### Reference

[ItemAvailabilityDataManager Class](itemavailabilitydatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

