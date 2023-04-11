---
title: GetDiscountCodesServiceResponse Constructor (IEnumerable(DiscountCode)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetDiscountCodesServiceResponse Constructor (IEnumerable(DiscountCode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetDiscountCodesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getdiscountcodesserviceresponse.getdiscountcodesserviceresponse(v=AX.60)
ms:contentKeyID: 62213001
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetDiscountCodesServiceResponse Constructor (IEnumerable(DiscountCode))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetDiscountCodesServiceResponse](getdiscountcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    discountCodes As IEnumerable(Of DiscountCode) _
)
'Usage
Dim discountCodes As IEnumerable(Of DiscountCode)

Dim instance As New GetDiscountCodesServiceResponse(discountCodes)
```

``` csharp
public GetDiscountCodesServiceResponse(
    IEnumerable<DiscountCode> discountCodes
)
```

``` c++
public:
GetDiscountCodesServiceResponse(
    IEnumerable<DiscountCode^>^ discountCodes
)
```

#### Parameters

  - discountCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[DiscountCode](discountcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetDiscountCodesServiceResponse Class](getdiscountcodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetDiscountCodesServiceResponse Overload](getdiscountcodesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

