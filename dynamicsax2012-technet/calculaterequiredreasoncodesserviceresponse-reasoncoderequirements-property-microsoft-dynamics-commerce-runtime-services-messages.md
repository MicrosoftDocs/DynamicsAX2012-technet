---
title: CalculateRequiredReasonCodesServiceResponse.ReasonCodeRequirements Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReasonCodeRequirements Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.ReasonCodeRequirements
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesserviceresponse.reasoncoderequirements(v=AX.60)
ms:contentKeyID: 62211679
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceResponse.ReasonCodeRequirements
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeRequirements Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of reason code requirements.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeRequirements As IEnumerable(Of ReasonCodeRequirement)
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceResponse
Dim value As IEnumerable(Of ReasonCodeRequirement)

value = instance.ReasonCodeRequirements
```

``` csharp
[DataMemberAttribute]
public IEnumerable<ReasonCodeRequirement> ReasonCodeRequirements { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<ReasonCodeRequirement^>^ ReasonCodeRequirements {
    IEnumerable<ReasonCodeRequirement^>^ get ();
    private: void set (IEnumerable<ReasonCodeRequirement^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ReasonCodeRequirement](reasoncoderequirement-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [IEnumerable\<T\>](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\)).  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceResponse Class](calculaterequiredreasoncodesserviceresponse-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

