---
title: ProjectionDomainExtensions.IsRemoteLookup Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: IsRemoteLookup Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.ProjectionDomainExtensions.IsRemoteLookup(Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain,System.Int64)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.projectiondomainextensions.isremotelookup(v=AX.60)
ms:contentKeyID: 65319913
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ProjectionDomainExtensions.IsRemoteLookup
dev_langs:
- CSharp
- C++
- VB
---

# IsRemoteLookup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the current context requires a remote lookup.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Function IsRemoteLookup ( _
    context As ProjectionDomain, _
    channelId As Long _
) As Boolean
'Usage
Dim context As ProjectionDomain
Dim channelId As Long
Dim returnValue As Boolean

returnValue = context.IsRemoteLookup(channelId)
```

``` csharp
public static bool IsRemoteLookup(
    this ProjectionDomain context,
    long channelId
)
```

``` c++
[ExtensionAttribute]
public:
static bool IsRemoteLookup(
    ProjectionDomain^ context, 
    long long channelId
)
```

#### Parameters

  - context  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether a remote lookup is required for this context.  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ProjectionDomain](projectiondomain-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[ProjectionDomainExtensions Class](projectiondomainextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

