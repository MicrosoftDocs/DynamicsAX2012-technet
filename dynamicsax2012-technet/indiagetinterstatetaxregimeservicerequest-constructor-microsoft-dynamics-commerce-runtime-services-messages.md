---
title: IndiaGetInterStateTaxRegimeServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IndiaGetInterStateTaxRegimeServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.RequestContext,System.String,Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.indiagetinterstatetaxregimeservicerequest.indiagetinterstatetaxregimeservicerequest(v=AX.60)
ms:contentKeyID: 65315913
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.IndiaGetInterStateTaxRegimeServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# IndiaGetInterStateTaxRegimeServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    context As RequestContext, _
    inventLocationId As String, _
    shippingAddress As Address _
)
'Usage
Dim context As RequestContext
Dim inventLocationId As String
Dim shippingAddress As Address

Dim instance As New IndiaGetInterStateTaxRegimeServiceRequest(context, _
    inventLocationId, shippingAddress)
```

``` csharp
public IndiaGetInterStateTaxRegimeServiceRequest(
    RequestContext context,
    string inventLocationId,
    Address shippingAddress
)
```

``` c++
public:
IndiaGetInterStateTaxRegimeServiceRequest(
    RequestContext^ context, 
    String^ inventLocationId, 
    Address^ shippingAddress
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - inventLocationId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - shippingAddress  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[IndiaGetInterStateTaxRegimeServiceRequest Class](indiagetinterstatetaxregimeservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

