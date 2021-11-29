---
title: GetAddressRequest.CountyId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: CountyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.CountyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getaddressrequest.countyid(v=AX.60)
ms:contentKeyID: 62209209
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetAddressRequest.CountyId
dev_langs:
- CSharp
- C++
- VB
---

# CountyId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the county identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CountyId As String
    Get
    Set
'Usage
Dim instance As GetAddressRequest
Dim value As String

value = instance.CountyId

instance.CountyId = value
```

``` csharp
[DataMemberAttribute]
public string CountyId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ CountyId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetAddressRequest Class](getaddressrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

