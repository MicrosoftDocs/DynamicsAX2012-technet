---
title: CommerceIdentity.OriginalUserId Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: OriginalUserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.OriginalUserId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.originaluserid(v=AX.60)
ms:contentKeyID: 62211907
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.OriginalUserId
dev_langs:
- CSharp
- C++
- VB
---

# OriginalUserId Property

Gets or sets the original user identifier - used in elevated mode.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OriginalUserId As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.OriginalUserId

instance.OriginalUserId = value
```

``` csharp
[DataMemberAttribute]
public string OriginalUserId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ OriginalUserId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

