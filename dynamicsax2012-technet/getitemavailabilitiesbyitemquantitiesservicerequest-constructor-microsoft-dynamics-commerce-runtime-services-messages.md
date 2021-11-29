---
title: GetItemAvailabilitiesByItemQuantitiesServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesByItemQuantitiesServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemQuantity},System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemquantitiesservicerequest.getitemavailabilitiesbyitemquantitiesservicerequest(v=AX.60)
ms:contentKeyID: 65320938
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemQuantitiesServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemQuantitiesServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    itemQuantities As IEnumerable(Of ItemQuantity), _
    customerAccountNumber As String, _
    maxWarehousesPerItem As Integer _
)
'Usage
Dim settings As QueryResultSettings
Dim itemQuantities As IEnumerable(Of ItemQuantity)
Dim customerAccountNumber As String
Dim maxWarehousesPerItem As Integer

Dim instance As New GetItemAvailabilitiesByItemQuantitiesServiceRequest(settings, _
    itemQuantities, customerAccountNumber, _
    maxWarehousesPerItem)
```

``` csharp
public GetItemAvailabilitiesByItemQuantitiesServiceRequest(
    QueryResultSettings settings,
    IEnumerable<ItemQuantity> itemQuantities,
    string customerAccountNumber,
    int maxWarehousesPerItem
)
```

``` c++
public:
GetItemAvailabilitiesByItemQuantitiesServiceRequest(
    QueryResultSettings^ settings, 
    IEnumerable<ItemQuantity^>^ itemQuantities, 
    String^ customerAccountNumber, 
    int maxWarehousesPerItem
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemQuantities  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemQuantity](itemquantity-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - maxWarehousesPerItem  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailabilitiesByItemQuantitiesServiceRequest Class](getitemavailabilitiesbyitemquantitiesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

