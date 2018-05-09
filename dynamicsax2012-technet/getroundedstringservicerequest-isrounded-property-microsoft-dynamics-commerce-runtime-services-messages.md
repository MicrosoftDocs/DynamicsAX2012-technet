---
title: GetRoundedStringServiceRequest.IsRounded Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsRounded Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.IsRounded
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.services.messages.getroundedstringservicerequest.isrounded(v=AX.60)
ms:contentKeyID: 62210062
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetRoundedStringServiceRequest.IsRounded
dev_langs:
- CSharp
- C++
- VB
---

# IsRounded Property

Gets a value indicating whether the value has already been rounded. In that case only the formatted string will be returned.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsRounded As Boolean
    Get
    Private Set
'Usage
Dim instance As GetRoundedStringServiceRequest
Dim value As Boolean

value = instance.IsRounded
```

``` csharp
[DataMemberAttribute]
public bool IsRounded { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsRounded {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetRoundedStringServiceRequest Class](getroundedstringservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

