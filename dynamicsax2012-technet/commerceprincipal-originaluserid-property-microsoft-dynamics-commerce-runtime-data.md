---
title: CommercePrincipal.OriginalUserId Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: OriginalUserId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.OriginalUserId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.commerceprincipal.originaluserid(v=AX.60)
ms:contentKeyID: 62209441
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommercePrincipal.OriginalUserId
dev_langs:
- CSharp
- C++
- VB
---

# OriginalUserId Property

Gets or sets the original user identifier during elevated operations.

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
Dim instance As CommercePrincipal
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CommercePrincipal Class](commerceprincipal-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

