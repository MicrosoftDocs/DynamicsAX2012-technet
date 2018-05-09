---
title: CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType, IEnumerable(SalesLine)) (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType, IEnumerable(SalesLine))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction,Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine})
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.calculaterequiredreasoncodesservicerequest(v=AX.60)
ms:contentKeyID: 65317825
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CalculateRequiredReasonCodesServiceRequest Constructor (SalesTransaction, ReasonCodeSourceType, IEnumerable(SalesLine))

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    salesTransaction As SalesTransaction, _
    sourceType As ReasonCodeSourceType, _
    salesLines As IEnumerable(Of SalesLine) _
)
'Usage
Dim salesTransaction As SalesTransaction
Dim sourceType As ReasonCodeSourceType
Dim salesLines As IEnumerable(Of SalesLine)

Dim instance As New CalculateRequiredReasonCodesServiceRequest(salesTransaction, _
    sourceType, salesLines)
```

``` csharp
public CalculateRequiredReasonCodesServiceRequest(
    SalesTransaction salesTransaction,
    ReasonCodeSourceType sourceType,
    IEnumerable<SalesLine> salesLines
)
```

``` c++
public:
CalculateRequiredReasonCodesServiceRequest(
    SalesTransaction^ salesTransaction, 
    ReasonCodeSourceType sourceType, 
    IEnumerable<SalesLine^>^ salesLines
)
```

#### Parameters

  - salesTransaction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction](salestransaction-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - sourceType  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - salesLines  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[CalculateRequiredReasonCodesServiceRequest Overload](calculaterequiredreasoncodesservicerequest-constructor-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

