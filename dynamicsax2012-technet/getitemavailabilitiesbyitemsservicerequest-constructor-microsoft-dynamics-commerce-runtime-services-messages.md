---
title: GetItemAvailabilitiesByItemsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetItemAvailabilitiesByItemsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemVariantInventoryDimension},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getitemavailabilitiesbyitemsservicerequest.getitemavailabilitiesbyitemsservicerequest(v=AX.60)
ms:contentKeyID: 65318732
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetItemAvailabilitiesByItemsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetItemAvailabilitiesByItemsServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    settings As QueryResultSettings, _
    items As IEnumerable(Of ItemVariantInventoryDimension), _
    customerAccountNumber As String _
)
'Usage
Dim settings As QueryResultSettings
Dim items As IEnumerable(Of ItemVariantInventoryDimension)
Dim customerAccountNumber As String

Dim instance As New GetItemAvailabilitiesByItemsServiceRequest(settings, _
    items, customerAccountNumber)
```

``` csharp
public GetItemAvailabilitiesByItemsServiceRequest(
    QueryResultSettings settings,
    IEnumerable<ItemVariantInventoryDimension> items,
    string customerAccountNumber
)
```

``` c++
public:
GetItemAvailabilitiesByItemsServiceRequest(
    QueryResultSettings^ settings, 
    IEnumerable<ItemVariantInventoryDimension^>^ items, 
    String^ customerAccountNumber
)
```

#### Parameters

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - items  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ItemVariantInventoryDimension](itemvariantinventorydimension-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - customerAccountNumber  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetItemAvailabilitiesByItemsServiceRequest Class](getitemavailabilitiesbyitemsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

