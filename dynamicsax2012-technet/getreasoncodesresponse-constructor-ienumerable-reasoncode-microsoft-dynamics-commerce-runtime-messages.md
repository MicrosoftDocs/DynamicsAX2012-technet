---
title: GetReasonCodesResponse Constructor (IEnumerable(ReasonCode)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReasonCodesResponse Constructor (IEnumerable(ReasonCode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReasonCodesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreasoncodesresponse.getreasoncodesresponse(v=AX.60)
ms:contentKeyID: 62214133
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReasonCodesResponse Constructor (IEnumerable(ReasonCode))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [GetReasonCodesResponse](getreasoncodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    reasonCodes As IEnumerable(Of ReasonCode) _
)
'Usage
Dim reasonCodes As IEnumerable(Of ReasonCode)

Dim instance As New GetReasonCodesResponse(reasonCodes)
```

``` csharp
public GetReasonCodesResponse(
    IEnumerable<ReasonCode> reasonCodes
)
```

``` c++
public:
GetReasonCodesResponse(
    IEnumerable<ReasonCode^>^ reasonCodes
)
```

#### Parameters

  - reasonCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReasonCodesResponse Class](getreasoncodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReasonCodesResponse Overload](getreasoncodesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

