---
title: Credential.LogOnKey Property  (Microsoft.Dynamics.Commerce.Runtime.Framework)
TOCTitle: LogOnKey Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Framework.Credential.LogOnKey
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.framework.credential.logonkey(v=AX.60)
ms:contentKeyID: 65318392
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Framework.Credential.LogOnKey
dev_langs:
- CSharp
- C++
- VB
---

# LogOnKey Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the Logon Key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Framework](microsoft-dynamics-commerce-runtime-framework-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property LogOnKey As String
    Get
    Set
'Usage
Dim instance As Credential
Dim value As String

value = instance.LogOnKey

instance.LogOnKey = value
```

``` csharp
[DataMemberAttribute]
public string LogOnKey { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ LogOnKey {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Credential Class](credential-class-microsoft-dynamics-commerce-runtime-framework.md)

[Microsoft.Dynamics.Commerce.Runtime.Framework Namespace](microsoft-dynamics-commerce-runtime-framework-namespace.md)

