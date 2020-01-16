---
title: GetItemAvailabilitiesByItemWarehousesServiceRequest.ItemWarehouses Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ItemWarehouses Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest.ItemWarehouses
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemwarehousesservicerequest.itemwarehouses(v=AX.60)
ms:contentKeyID: 62208782
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemWarehousesServiceRequest.ItemWarehouses
dev_langs:
- CSharp
- C++
- VB
---

# ItemWarehouses Property

Gets the items and corresponding inventory dimensions.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ItemWarehouses As IEnumerable(Of ItemWarehouse)
    Get
    Private Set
'Usage
Dim instance As GetItemAvailabilitiesByItemWarehousesServiceRequest
Dim value As IEnumerable(Of ItemWarehouse)

value = instance.ItemWarehouses
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ItemWarehouse> ItemWarehouses { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ItemWarehouse^>^ ItemWarehouses {
    IEnumerable<ItemWarehouse^>^ get ();
    private: void set (IEnumerable<ItemWarehouse^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemWarehouse](itemwarehouse-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[GetItemAvailabilitiesByItemWarehousesServiceRequest Class](getitemavailabilitiesbyitemwarehousesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

