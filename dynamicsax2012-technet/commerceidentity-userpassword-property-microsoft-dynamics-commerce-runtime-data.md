---
title: CommerceIdentity.UserPassword Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: UserPassword Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.UserPassword
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.userpassword(v=AX.60)
ms:contentKeyID: 65320533
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.UserPassword
dev_langs:
- CSharp
- C++
- VB
---

# UserPassword Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property UserPassword As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.UserPassword

instance.UserPassword = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string UserPassword { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ UserPassword {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

