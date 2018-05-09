---
title: GetButtonGridByIdServiceRequest.ButtonGridId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: ButtonGridId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridByIdServiceRequest.ButtonGridId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getbuttongridbyidservicerequest.buttongridid(v=AX.60)
ms:contentKeyID: 62213570
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetButtonGridByIdServiceRequest.ButtonGridId
dev_langs:
- CSharp
- C++
- VB
---

# ButtonGridId Property

Gets the buttongrid Id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property ButtonGridId As String
    Get
    Private Set
'Usage
Dim instance As GetButtonGridByIdServiceRequest
Dim value As String

value = instance.ButtonGridId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string ButtonGridId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ ButtonGridId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetButtonGridByIdServiceRequest Class](getbuttongridbyidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

