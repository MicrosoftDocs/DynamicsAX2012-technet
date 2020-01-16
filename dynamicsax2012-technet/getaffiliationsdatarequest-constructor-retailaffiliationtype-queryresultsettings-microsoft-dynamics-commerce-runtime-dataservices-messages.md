---
title: GetAffiliationsDataRequest Constructor (RetailAffiliationType, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: GetAffiliationsDataRequest Constructor (RetailAffiliationType, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.GetAffiliationsDataRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailAffiliationType,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.getaffiliationsdatarequest.getaffiliationsdatarequest(v=AX.60)
ms:contentKeyID: 65315484
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetAffiliationsDataRequest Constructor (RetailAffiliationType, QueryResultSettings)

Initializes a new instance of the [GetAffiliationsDataRequest](getaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    affiliationType As RetailAffiliationType, _
    settings As QueryResultSettings _
)
'Usage
Dim affiliationType As RetailAffiliationType
Dim settings As QueryResultSettings

Dim instance As New GetAffiliationsDataRequest(affiliationType, _
    settings)
```

``` csharp
public GetAffiliationsDataRequest(
    RetailAffiliationType affiliationType,
    QueryResultSettings settings
)
```

``` c++
public:
GetAffiliationsDataRequest(
    RetailAffiliationType affiliationType, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - affiliationType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailAffiliationType](retailaffiliationtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetAffiliationsDataRequest Class](getaffiliationsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[GetAffiliationsDataRequest Overload](getaffiliationsdatarequest-constructor-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

