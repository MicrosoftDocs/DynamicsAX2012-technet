---
title: GetDeliveryPreferencesServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDeliveryPreferencesServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getdeliverypreferencesservicerequest.getdeliverypreferencesservicerequest(v=AX.60)
ms:contentKeyID: 65320178
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDeliveryPreferencesServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetDeliveryPreferencesServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    context As RequestContext, _
    cartId As String _
)
'Usage
Dim context As RequestContext
Dim cartId As String

Dim instance As New GetDeliveryPreferencesServiceRequest(context, _
    cartId)
```

``` csharp
public GetDeliveryPreferencesServiceRequest(
    RequestContext context,
    string cartId
)
```

``` c++
public:
GetDeliveryPreferencesServiceRequest(
    RequestContext^ context, 
    String^ cartId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - cartId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetDeliveryPreferencesServiceRequest Class](getdeliverypreferencesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

