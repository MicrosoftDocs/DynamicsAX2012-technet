---
title: GetNonSaleTenderServiceResponse Constructor (IEnumerable(NonSalesTransaction)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetNonSaleTenderServiceResponse Constructor (IEnumerable(NonSalesTransaction))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.NonSalesTransaction})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnonsaletenderserviceresponse.getnonsaletenderserviceresponse(v=AX.60)
ms:contentKeyID: 62206924
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetNonSaleTenderServiceResponse Constructor (IEnumerable(NonSalesTransaction))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetNonSaleTenderServiceResponse](getnonsaletenderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactions As IEnumerable(Of NonSalesTransaction) _
)
'Usage
Dim transactions As IEnumerable(Of NonSalesTransaction)

Dim instance As New GetNonSaleTenderServiceResponse(transactions)
```

``` csharp
public GetNonSaleTenderServiceResponse(
    IEnumerable<NonSalesTransaction> transactions
)
```

``` c++
public:
GetNonSaleTenderServiceResponse(
    IEnumerable<NonSalesTransaction^>^ transactions
)
```

#### Parameters

  - transactions  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[NonSalesTransaction](nonsalestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetNonSaleTenderServiceResponse Class](getnonsaletenderserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetNonSaleTenderServiceResponse Overload](getnonsaletenderserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

