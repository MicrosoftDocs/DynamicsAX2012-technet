---
title: CommerceIdentity.Name Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.name(v=AX.60)
ms:contentKeyID: 65315603
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Name As String
    Get
    Set
'Usage
Dim instance As CommerceIdentity
Dim value As String

value = instance.Name

instance.Name = value
```

``` csharp
[DataMemberAttribute]
public string Name { get; set; }
```

``` c++
[DataMemberAttribute]
public:
virtual property String^ Name {
    String^ get () sealed;
    void set (String^ value) sealed;
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Implements

[IIdentity.Name](https://technet.microsoft.com/library/9cba0wt3\(v=ax.60\))  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

