---
title: GetPricesServiceResponse Constructor (IEnumerable(SalesLine), String) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetPricesServiceResponse Constructor (IEnumerable(SalesLine), String)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetPricesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine},System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getpricesserviceresponse.getpricesserviceresponse(v=AX.60)
ms:contentKeyID: 62214105
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetPricesServiceResponse Constructor (IEnumerable(SalesLine), String)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetPricesServiceResponse](getpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesLines As IEnumerable(Of SalesLine), _
    currencyCode As String _
)
'Usage
Dim salesLines As IEnumerable(Of SalesLine)
Dim currencyCode As String

Dim instance As New GetPricesServiceResponse(salesLines, _
    currencyCode)
```

``` csharp
public GetPricesServiceResponse(
    IEnumerable<SalesLine> salesLines,
    string currencyCode
)
```

``` c++
public:
GetPricesServiceResponse(
    IEnumerable<SalesLine^>^ salesLines, 
    String^ currencyCode
)
```

#### Parameters

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - currencyCode  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[GetPricesServiceResponse Class](getpricesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[GetPricesServiceResponse Overload](getpricesserviceresponse-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

