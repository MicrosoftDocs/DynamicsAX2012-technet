---
title: NonSaleTenderServiceRequest.ShiftId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ShiftId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NonSaleTenderServiceRequest.ShiftId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.nonsaletenderservicerequest.shiftid(v=AX.60)
ms:contentKeyID: 62212703
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.NonSaleTenderServiceRequest.ShiftId
dev_langs:
- CSharp
- C++
- VB
---

# ShiftId Property

Gets or sets the shift identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ShiftId As String
    Get
    Set
'Usage
Dim instance As NonSaleTenderServiceRequest
Dim value As String

value = instance.ShiftId

instance.ShiftId = value
```

``` csharp
[DataMemberAttribute]
public string ShiftId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ ShiftId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[NonSaleTenderServiceRequest Class](nonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

