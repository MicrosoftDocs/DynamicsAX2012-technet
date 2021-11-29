---
title: GetShippingAdapterConfigurationDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetShippingAdapterConfigurationDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest.#ctor(System.Collections.Generic.IEnumerable{System.String},Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getshippingadapterconfigurationdatarequest.getshippingadapterconfigurationdatarequest(v=AX.60)
ms:contentKeyID: 65318729
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetShippingAdapterConfigurationDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetShippingAdapterConfigurationDataRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetShippingAdapterConfigurationDataRequest](getshippingadapterconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    deliveryModeIds As IEnumerable(Of String), _
    settings As QueryResultSettings _
)
'Usage
Dim deliveryModeIds As IEnumerable(Of String)
Dim settings As QueryResultSettings

Dim instance As New GetShippingAdapterConfigurationDataRequest(deliveryModeIds, _
    settings)
```

``` csharp
public GetShippingAdapterConfigurationDataRequest(
    IEnumerable<string> deliveryModeIds,
    QueryResultSettings settings
)
```

``` c++
public:
GetShippingAdapterConfigurationDataRequest(
    IEnumerable<String^>^ deliveryModeIds, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - deliveryModeIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetShippingAdapterConfigurationDataRequest Class](getshippingadapterconfigurationdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

