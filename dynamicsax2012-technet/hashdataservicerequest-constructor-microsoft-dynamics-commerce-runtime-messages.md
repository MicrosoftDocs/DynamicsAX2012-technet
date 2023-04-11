---
title: HashDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: HashDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Messages.HashDataServiceRequest.#ctor(System.String,System.String,System.String,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.hashdataservicerequest.hashdataservicerequest(v=AX.60)
ms:contentKeyID: 65316103
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.HashDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# HashDataServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    data As String, _
    algorithm As String, _
    invariant As String, _
    securityContext As String, _
    securityKeyPath As String _
)
'Usage
Dim data As String
Dim algorithm As String
Dim invariant As String
Dim securityContext As String
Dim securityKeyPath As String

Dim instance As New HashDataServiceRequest(data, algorithm, _
    invariant, securityContext, securityKeyPath)
```

``` csharp
public HashDataServiceRequest(
    string data,
    string algorithm,
    string invariant,
    string securityContext,
    string securityKeyPath
)
```

``` c++
public:
HashDataServiceRequest(
    String^ data, 
    String^ algorithm, 
    String^ invariant, 
    String^ securityContext, 
    String^ securityKeyPath
)
```

#### Parameters

  - data  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - algorithm  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - invariant  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - securityContext  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - securityKeyPath  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[HashDataServiceRequest Class](hashdataservicerequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

