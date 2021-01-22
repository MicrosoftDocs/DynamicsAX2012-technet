---
title: CommerceIdentity.Roles Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Roles Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.Roles
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.roles(v=AX.60)
ms:contentKeyID: 65320862
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.Roles
dev_langs:
- CSharp
- C++
- VB
---

# Roles Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Roles As String()
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String()

value = instance.Roles

instance.Roles = value
```

``` csharp
[DataMemberAttribute]
public string[] Roles { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property array<String^>^ Roles {
    array<String^>^ get ();
    void set (array<String^>^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\[\]  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

