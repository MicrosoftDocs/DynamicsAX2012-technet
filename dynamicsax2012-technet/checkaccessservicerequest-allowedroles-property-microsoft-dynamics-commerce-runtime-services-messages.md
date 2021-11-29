---
title: CheckAccessServiceRequest.AllowedRoles Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: AllowedRoles Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.AllowedRoles
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.checkaccessservicerequest.allowedroles(v=AX.60)
ms:contentKeyID: 62205352
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.CheckAccessServiceRequest.AllowedRoles
dev_langs:
- CSharp
- C++
- VB
---

# AllowedRoles Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the allowed roles.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AllowedRoles As String()
    Get
    Set
'Usage
Dim instance As CheckAccessServiceRequest
Dim value As String()

value = instance.AllowedRoles

instance.AllowedRoles = value
```

``` csharp
[DataMemberAttribute]
public string[] AllowedRoles { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property array<String^>^ AllowedRoles {
    array<String^>^ get ();
    void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
Allowed roles.  

## See Also

#### Reference

[CheckAccessServiceRequest Class](checkaccessservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

