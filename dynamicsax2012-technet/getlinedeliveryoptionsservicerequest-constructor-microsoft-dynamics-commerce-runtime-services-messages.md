---
title: GetLineDeliveryOptionsServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetLineDeliveryOptionsServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,System.Collections.Generic.ICollection{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},Microsoft.Dynamics.Commerce.Runtime.DataModel.Address)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getlinedeliveryoptionsservicerequest.getlinedeliveryoptionsservicerequest(v=AX.60)
ms:contentKeyID: 65320103
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetLineDeliveryOptionsServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# GetLineDeliveryOptionsServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransaction As SalesTransaction, _
    salesLines As ICollection(Of SalesLine), _
    shippingAddress As Address _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim salesLines As ICollection(Of SalesLine)
Dim shippingAddress As Address

Dim instance As New GetLineDeliveryOptionsServiceRequest(salesTransaction, _
    salesLines, shippingAddress)
```

``` csharp
public GetLineDeliveryOptionsServiceRequest(
    SalesTransaction salesTransaction,
    ICollection<SalesLine> salesLines,
    Address shippingAddress
)
```

``` c++
public:
GetLineDeliveryOptionsServiceRequest(
    SalesTransaction^ salesTransaction, 
    ICollection<SalesLine^>^ salesLines, 
    Address^ shippingAddress
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesLines  
    Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - shippingAddress  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetLineDeliveryOptionsServiceRequest Class](getlinedeliveryoptionsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

