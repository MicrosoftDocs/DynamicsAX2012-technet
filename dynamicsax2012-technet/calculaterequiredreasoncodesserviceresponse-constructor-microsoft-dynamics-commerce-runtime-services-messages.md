---
title: CalculateRequiredReasonCodesServiceResponse Constructor  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateRequiredReasonCodesServiceResponse Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.#ctor(System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCode},System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeRequirement})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesserviceresponse.calculaterequiredreasoncodesserviceresponse(v=AX.60)
ms:contentKeyID: 62207465
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# CalculateRequiredReasonCodesServiceResponse Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [CalculateRequiredReasonCodesServiceResponse](calculaterequiredreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    requiredReasonCodes As IEnumerable(Of ReasonCode), _
    transactionRequiredReasonCodeIds As IEnumerable(Of String), _
    reasonCodeRequirements As IEnumerable(Of ReasonCodeRequirement) _
)
'Usage
Dim requiredReasonCodes As IEnumerable(Of ReasonCode)
Dim transactionRequiredReasonCodeIds As IEnumerable(Of String)
Dim reasonCodeRequirements As IEnumerable(Of ReasonCodeRequirement)

Dim instance As New CalculateRequiredReasonCodesServiceResponse(requiredReasonCodes, _
    transactionRequiredReasonCodeIds, _
    reasonCodeRequirements)
```

``` csharp
public CalculateRequiredReasonCodesServiceResponse(
    IEnumerable<ReasonCode> requiredReasonCodes,
    IEnumerable<string> transactionRequiredReasonCodeIds,
    IEnumerable<ReasonCodeRequirement> reasonCodeRequirements
)
```

``` c++
public:
CalculateRequiredReasonCodesServiceResponse(
    IEnumerable<ReasonCode^>^ requiredReasonCodes, 
    IEnumerable<String^>^ transactionRequiredReasonCodeIds, 
    IEnumerable<ReasonCodeRequirement^>^ reasonCodeRequirements
)
```

#### Parameters

  - requiredReasonCodes  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

<!-- end list -->

  - transactionRequiredReasonCodeIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

<!-- end list -->

  - reasonCodeRequirements  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeRequirement](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceResponse Class](calculaterequiredreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

