---
title: CommerceAuthorizationAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: CommerceAuthorizationAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.commerceauthorizationattribute(v=AX.60)
ms:contentKeyID: 62202182
author: Khairunj
ms.author: daxcpft
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute
dev_langs:
- CSharp
- C++
- VB
---

# CommerceAuthorizationAttribute Class

CommerceAuthorizationAttribute specifies the commerce authorization filter that verifies the user request's [IPrincipal](https://technet.microsoft.com/library/f8kt7fb8\(v=ax.60\)).

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<AttributeUsageAttribute(AttributeTargets.Class Or AttributeTargets.Method, AllowMultiple := False)> _
Public Class CommerceAuthorizationAttribute _
    Inherits AuthorizeAttribute
'Usage
Dim instance As CommerceAuthorizationAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false)]
public class CommerceAuthorizationAttribute : AuthorizeAttribute
```

``` c++
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets::Class|AttributeTargets::Method, AllowMultiple = false)]
public ref class CommerceAuthorizationAttribute : public AuthorizeAttribute
```

## Remarks

Authorization class for all ODATA entities and Actions.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    FilterAttribute  
      AuthorizationFilterAttribute  
        AuthorizeAttribute  
          Microsoft.Dynamics.Retail.RetailServerLibrary.CommerceAuthorizationAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

