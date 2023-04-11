---
title: GetReasonCodesServiceResponse Constructor (IEnumerable(ReasonCode)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetReasonCodesServiceResponse Constructor (IEnumerable(ReasonCode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReasonCodesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreasoncodesserviceresponse.getreasoncodesserviceresponse(v=AX.60)
ms:contentKeyID: 62213036
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCodesServiceResponse Constructor (IEnumerable(ReasonCode))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetReasonCodesServiceResponse](getreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reasonCodes As IEnumerable(Of ReasonCode) _
)
'Usage
Dim reasonCodes As IEnumerable(Of ReasonCode)

Dim instance As New GetReasonCodesServiceResponse(reasonCodes)
```

``` csharp
public GetReasonCodesServiceResponse(
    IEnumerable<ReasonCode> reasonCodes
)
```

``` c++
public:
GetReasonCodesServiceResponse(
    IEnumerable<ReasonCode^>^ reasonCodes
)
```

#### Parameters

  - reasonCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReasonCodesServiceResponse Class](getreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetReasonCodesServiceResponse Overload](getreasoncodesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

