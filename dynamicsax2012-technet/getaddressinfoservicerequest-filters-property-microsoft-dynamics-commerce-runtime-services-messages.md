---
title: GetAddressInfoServiceRequest.Filters Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: Filters Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest.Filters
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getaddressinfoservicerequest.filters(v=AX.60)
ms:contentKeyID: 62202123
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetAddressInfoServiceRequest.Filters
dev_langs:
- CSharp
- C++
- VB
---

# Filters Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the components used to filter the outbound data.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Filters As ParameterSet
    Get
    Protected Set
'Usage
Dim instance As GetAddressInfoServiceRequest
Dim value As ParameterSet

value = instance.Filters

instance.Filters = value
```

``` csharp
[DataMemberAttribute]
public ParameterSet Filters { get; protected set; }
```

``` c++
[DataMemberAttribute]
public:
property ParameterSet^ Filters {
    ParameterSet^ get ();
    protected: void set (ParameterSet^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md)  
Returns [ParameterSet](parameterset-class-microsoft-dynamics-commerce-runtime.md).  

## Remarks

For instance, for GetCounties() API, filters countryRegionId (mandatory) and StateID.

## See Also

#### Reference

[GetAddressInfoServiceRequest Class](getaddressinfoservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

