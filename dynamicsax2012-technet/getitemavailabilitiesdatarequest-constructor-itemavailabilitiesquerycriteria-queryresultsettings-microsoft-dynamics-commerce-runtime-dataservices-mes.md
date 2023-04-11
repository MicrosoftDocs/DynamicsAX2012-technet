---
title: GetItemAvailabilitiesDataRequest Constructor (ItemAvailabilitiesQueryCriteria, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetItemAvailabilitiesDataRequest Constructor (ItemAvailabilitiesQueryCriteria, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetItemAvailabilitiesDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getitemavailabilitiesdatarequest.getitemavailabilitiesdatarequest(v=AX.60)
ms:contentKeyID: 65321239
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetItemAvailabilitiesDataRequest Constructor (ItemAvailabilitiesQueryCriteria, QueryResultSettings)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetItemAvailabilitiesDataRequest](getitemavailabilitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    queryCriteria As ItemAvailabilitiesQueryCriteria, _
    settings As QueryResultSettings _
)
'Usage
Dim queryCriteria As ItemAvailabilitiesQueryCriteria
Dim settings As QueryResultSettings

Dim instance As New GetItemAvailabilitiesDataRequest(queryCriteria, _
    settings)
```

``` csharp
public GetItemAvailabilitiesDataRequest(
    ItemAvailabilitiesQueryCriteria queryCriteria,
    QueryResultSettings settings
)
```

``` c++
public:
GetItemAvailabilitiesDataRequest(
    ItemAvailabilitiesQueryCriteria^ queryCriteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - queryCriteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailabilitiesQueryCriteria](itemavailabilitiesquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetItemAvailabilitiesDataRequest Class](getitemavailabilitiesdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetItemAvailabilitiesDataRequest Overload](getitemavailabilitiesdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

