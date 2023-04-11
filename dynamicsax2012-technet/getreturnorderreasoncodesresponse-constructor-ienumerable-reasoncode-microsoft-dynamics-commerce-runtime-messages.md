---
title: GetReturnOrderReasonCodesResponse Constructor (IEnumerable(ReasonCode)) (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetReturnOrderReasonCodesResponse Constructor (IEnumerable(ReasonCode))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.GetReturnOrderReasonCodesResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getreturnorderreasoncodesresponse.getreturnorderreasoncodesresponse(v=AX.60)
ms:contentKeyID: 65321481
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# GetReturnOrderReasonCodesResponse Constructor (IEnumerable(ReasonCode))


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    returnReasonCodes As IEnumerable(Of ReasonCode) _
)
'Usage
Dim returnReasonCodes As IEnumerable(Of ReasonCode)

Dim instance As New GetReturnOrderReasonCodesResponse(returnReasonCodes)
```

``` csharp
public GetReturnOrderReasonCodesResponse(
    IEnumerable<ReasonCode> returnReasonCodes
)
```

``` c++
public:
GetReturnOrderReasonCodesResponse(
    IEnumerable<ReasonCode^>^ returnReasonCodes
)
```

#### Parameters

  - returnReasonCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[GetReturnOrderReasonCodesResponse Class](getreturnorderreasoncodesresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[GetReturnOrderReasonCodesResponse Overload](getreturnorderreasoncodesresponse-constructor-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

