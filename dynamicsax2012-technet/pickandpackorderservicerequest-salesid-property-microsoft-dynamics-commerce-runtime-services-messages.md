---
title: PickAndPackOrderServiceRequest.SalesId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: SalesId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.SalesId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.pickandpackorderservicerequest.salesid(v=AX.60)
ms:contentKeyID: 62213199
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.PickAndPackOrderServiceRequest.SalesId
dev_langs:
- CSharp
- C++
- VB
---

# SalesId Property

Gets the cart identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<RequiredAttribute> _
Public Property SalesId As String
    Get
    Private Set
'Usage
Dim instance As PickAndPackOrderServiceRequest
Dim value As String

value = instance.SalesId
```

``` csharp
[DataMemberAttribute]
[RequiredAttribute]
public string SalesId { get; private set; }
```

``` c++
[DataMemberAttribute]
[RequiredAttribute]
public:
property String^ SalesId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PickAndPackOrderServiceRequest Class](pickandpackorderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

