---
title: GetItemAvailabilitiesByItemQuantitiesServiceRequest.MaxWarehousesPerItem Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: MaxWarehousesPerItem Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.MaxWarehousesPerItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemquantitiesservicerequest.maxwarehousesperitem(v=AX.60)
ms:contentKeyID: 62211261
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.MaxWarehousesPerItem
dev_langs:
- CSharp
- C++
- VB
---

# MaxWarehousesPerItem Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the maximum number of warehouses per item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property MaxWarehousesPerItem As Integer
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesByItemQuantitiesServiceRequest
Dim value As Integer

value = instance.MaxWarehousesPerItem
```

``` csharp
[DataMemberAttribute]
public int MaxWarehousesPerItem { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property int MaxWarehousesPerItem {
    int get ();
    private: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The maximum number of warehouses per item.  

## See Also

#### Reference

[GetItemAvailabilitiesByItemQuantitiesServiceRequest Class](getitemavailabilitiesbyitemquantitiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

