---
title: CheckAccessServiceRequest.CommercePrincipal Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CommercePrincipal Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.CommercePrincipal
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.commerceprincipal(v=AX.60)
ms:contentKeyID: 62209535
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.CommercePrincipal
dev_langs:
- CSharp
- C++
- VB
---

# CommercePrincipal Property

Gets or sets the Commerce Principal.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CommercePrincipal As CommercePrincipal
    Get
    Set
'Usage
Dim instance As CheckAccessServiceRequest
Dim value As CommercePrincipal

value = instance.CommercePrincipal

instance.CommercePrincipal = value
```

``` csharp
[DataMemberAttribute]
public CommercePrincipal CommercePrincipal { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property CommercePrincipal^ CommercePrincipal {
    CommercePrincipal^ get ();
    void set (CommercePrincipal^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)  
Commerce Principal.  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

