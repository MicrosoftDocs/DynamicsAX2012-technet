---
title: CalculateRequiredReasonCodesServiceResponse.RequiredReasonCodes Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: RequiredReasonCodes Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.RequiredReasonCodes
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesserviceresponse.requiredreasoncodes(v=AX.60)
ms:contentKeyID: 62208642
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.RequiredReasonCodes
dev_langs:
- CSharp
- C++
- VB
---

# RequiredReasonCodes Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the required reason codes.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property RequiredReasonCodes As IEnumerable(Of ReasonCode)
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceResponse
Dim value As IEnumerable(Of ReasonCode)

value = instance.RequiredReasonCodes
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ReasonCode> RequiredReasonCodes { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ReasonCode^>^ RequiredReasonCodes {
    IEnumerable<ReasonCode^>^ get ();
    private: void set (IEnumerable<ReasonCode^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCode](reasoncode-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceResponse Class](calculaterequiredreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

