---
title: RequestContextExtensions.SetOrgUnit Method  (Microsoft.Dynamics.Commerce.Runtime)
TOCTitle: SetOrgUnit Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetOrgUnit(Microsoft.Dynamics.Commerce.Runtime.RequestContext,Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.requestcontextextensions.setorgunit(v=AX.60)
ms:contentKeyID: 65323129
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.RequestContextExtensions.SetOrgUnit
dev_langs:
- CSharp
- C++
- VB
---

# SetOrgUnit Method

Sets the organization unit for the current request.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime](microsoft-dynamics-commerce-runtime-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub SetOrgUnit ( _
    requestContext As RequestContext, _
    orgUnit As OrgUnit _
)
'Usage
Dim requestContext As RequestContext
Dim orgUnit As OrgUnit

requestContext.SetOrgUnit(orgUnit)
```

``` csharp
public static void SetOrgUnit(
    this RequestContext requestContext,
    OrgUnit orgUnit
)
```

``` c++
[ExtensionAttribute]
public:
static void SetOrgUnit(
    RequestContext^ requestContext, 
    OrgUnit^ orgUnit
)
```

#### Parameters

  - requestContext  
    Type: [Microsoft.Dynamics.Commerce.Runtime.RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md)  

<!-- end list -->

  - orgUnit  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [RequestContext](requestcontext-class-microsoft-dynamics-commerce-runtime.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[RequestContextExtensions Class](requestcontextextensions-class-microsoft-dynamics-commerce-runtime.md)

[Microsoft.Dynamics.Commerce.Runtime Namespace](microsoft-dynamics-commerce-runtime-namespace.md)

