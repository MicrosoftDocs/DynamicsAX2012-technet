---
title: CustomersSearchServiceRequest Constructor (CustomerSearchCriteria, QueryResultSettings) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomersSearchServiceRequest Constructor (CustomerSearchCriteria, QueryResultSettings)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CustomersSearchServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria,Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.customerssearchservicerequest.customerssearchservicerequest(v=AX.60)
ms:contentKeyID: 65320185
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CustomersSearchServiceRequest Constructor (CustomerSearchCriteria, QueryResultSettings)

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    criteria As CustomerSearchCriteria, _
    settings As QueryResultSettings _
)
'Usage
Dim criteria As CustomerSearchCriteria
Dim settings As QueryResultSettings

Dim instance As New CustomersSearchServiceRequest(criteria, _
    settings)
```

``` csharp
public CustomersSearchServiceRequest(
    CustomerSearchCriteria criteria,
    QueryResultSettings settings
)
```

``` c++
public:
CustomersSearchServiceRequest(
    CustomerSearchCriteria^ criteria, 
    QueryResultSettings^ settings
)
```

#### Parameters

  - criteria  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerSearchCriteria](customersearchcriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - settings  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.QueryResultSettings](queryresultsettings-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CustomersSearchServiceRequest Class](customerssearchservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CustomersSearchServiceRequest Overload](customerssearchservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

