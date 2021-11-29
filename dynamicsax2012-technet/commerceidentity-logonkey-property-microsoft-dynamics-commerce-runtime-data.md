---
title: CommerceIdentity.LogonKey Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: LogonKey Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.LogonKey
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.logonkey(v=AX.60)
ms:contentKeyID: 65319122
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.LogonKey
dev_langs:
- CSharp
- C++
- VB
---

# LogonKey Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property LogonKey As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.LogonKey

instance.LogonKey = value
```

``` csharp
[IgnoreDataMemberAttribute]
public string LogonKey { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property String^ LogonKey {
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

