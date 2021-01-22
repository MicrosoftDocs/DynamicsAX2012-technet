---
title: CheckAccessRequest.AllowedRoles Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: AllowedRoles Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.AllowedRoles
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.checkaccessrequest.allowedroles(v=AX.60)
ms:contentKeyID: 62214431
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.CheckAccessRequest.AllowedRoles
dev_langs:
- CSharp
- C++
- VB
---

# AllowedRoles Property

Gets allowed roles.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property AllowedRoles As String()
    Get
    Private Set
'Usage
Dim instance As CheckAccessRequest
Dim value As String()

value = instance.AllowedRoles
```

``` csharp
[DataMemberAttribute]
public string[] AllowedRoles { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property array<String^>^ AllowedRoles {
    array<String^>^ get ();
    private: void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  
Allowed roles.  

## See Also

#### Reference

[CheckAccessRequest Class](checkaccessrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

