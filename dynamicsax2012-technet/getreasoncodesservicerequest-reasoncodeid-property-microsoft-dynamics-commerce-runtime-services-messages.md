---
title: GetReasonCodesServiceRequest.ReasonCodeId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ReasonCodeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReasonCodesServiceRequest.ReasonCodeId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getreasoncodesservicerequest.reasoncodeid(v=AX.60)
ms:contentKeyID: 62207814
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReasonCodesServiceRequest.ReasonCodeId
dev_langs:
- CSharp
- C++
- VB
---

# ReasonCodeId Property

Gets the reason code id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ReasonCodeId As String
    Get
    Private Set
'Usage
Dim instance As GetReasonCodesServiceRequest
Dim value As String

value = instance.ReasonCodeId
```

``` csharp
[DataMemberAttribute]
public string ReasonCodeId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ReasonCodeId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetReasonCodesServiceRequest Class](getreasoncodesservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

