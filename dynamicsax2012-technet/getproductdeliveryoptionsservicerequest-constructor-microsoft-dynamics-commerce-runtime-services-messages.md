---
title: GetProductDeliveryOptionsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetProductDeliveryOptionsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDeliveryOptionsServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getproductdeliveryoptionsservicerequest.getproductdeliveryoptionsservicerequest(v=AX.60)
ms:contentKeyID: 65322927
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetProductDeliveryOptionsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetProductDeliveryOptionsServiceRequest Constructor

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    shippingAddress As Address, _
    itemId As String, _
    inventDimId As String _
)
'Usage
Dim shippingAddress As Address
Dim itemId As String
Dim inventDimId As String

Dim instance As New GetProductDeliveryOptionsServiceRequest(shippingAddress, _
    itemId, inventDimId)
```

``` csharp
public GetProductDeliveryOptionsServiceRequest(
    Address shippingAddress,
    string itemId,
    string inventDimId
)
```

``` c++
public:
GetProductDeliveryOptionsServiceRequest(
    Address^ shippingAddress, 
    String^ itemId, 
    String^ inventDimId
)
```

#### Parameters

  - shippingAddress  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventDimId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetProductDeliveryOptionsServiceRequest Class](getproductdeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

