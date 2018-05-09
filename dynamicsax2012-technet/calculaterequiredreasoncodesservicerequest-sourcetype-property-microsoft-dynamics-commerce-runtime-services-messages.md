---
title: CalculateRequiredReasonCodesServiceRequest.SourceType Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SourceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.SourceType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.calculaterequiredreasoncodesservicerequest.sourcetype(v=AX.60)
ms:contentKeyID: 62214348
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CalculateRequiredReasonCodesServiceRequest.SourceType
dev_langs:
- CSharp
- C++
- VB
---

# SourceType Property

Gets the source type of the reason code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property SourceType As ReasonCodeSourceType
    Get
    Private Set
'Usage
Dim instance As CalculateRequiredReasonCodesServiceRequest
Dim value As ReasonCodeSourceType

value = instance.SourceType
```

``` csharp
[DataMemberAttribute]
public ReasonCodeSourceType SourceType { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property ReasonCodeSourceType SourceType {
    ReasonCodeSourceType get ();
    private: void set (ReasonCodeSourceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ReasonCodeSourceType](reasoncodesourcetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CalculateRequiredReasonCodesServiceRequest Class](calculaterequiredreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

