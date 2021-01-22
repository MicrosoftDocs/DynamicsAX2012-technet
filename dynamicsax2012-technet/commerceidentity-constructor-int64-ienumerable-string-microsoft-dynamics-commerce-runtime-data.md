---
title: CommerceIdentity Constructor (Int64, IEnumerable(String)) (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CommerceIdentity Constructor (Int64, IEnumerable(String))
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.CommerceIdentity.#ctor(System.Int64,System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.commerceidentity.commerceidentity(v=AX.60)
ms:contentKeyID: 62211498
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# CommerceIdentity Constructor (Int64, IEnumerable(String))

Initializes a new instance of the [CommerceIdentity](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    roles As IEnumerable(Of String) _
)
'Usage
Dim channelId As Long
Dim roles As IEnumerable(Of String)

Dim instance As New CommerceIdentity(channelId, _
    roles)
```

``` csharp
public CommerceIdentity(
    long channelId,
    IEnumerable<string> roles
)
```

``` c++
public:
CommerceIdentity(
    long long channelId, 
    IEnumerable<String^>^ roles
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - roles  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[CommerceIdentity Class](commerceidentity-class-microsoft-dynamics-commerce-runtime-data.md)

[CommerceIdentity Overload](commerceidentity-constructor-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

