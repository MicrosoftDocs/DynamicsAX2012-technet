---
title: CommerceRuntimeExceptionFilterAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions)
TOCTitle: CommerceRuntimeExceptionFilterAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceRuntimeExceptionFilterAttribute
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.odataextensions.commerceruntimeexceptionfilterattribute(v=AX.60)
ms:contentKeyID: 62202158
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceRuntimeExceptionFilterAttribute
dev_langs:
- CSharp
- C++
- VB
---

# CommerceRuntimeExceptionFilterAttribute Class

The commerce runtime exception filter attribute.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<AttributeUsageAttribute(AttributeTargets.Class Or AttributeTargets.Method, AllowMultiple := True,  _
    Inherited := True)> _
Public NotInheritable Class CommerceRuntimeExceptionFilterAttribute _
    Inherits ExceptionFilterAttribute
'Usage
Dim instance As CommerceRuntimeExceptionFilterAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = true, 
    Inherited = true)]
public sealed class CommerceRuntimeExceptionFilterAttribute : ExceptionFilterAttribute
```

``` c++
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets::Class|AttributeTargets::Method, AllowMultiple = true, 
    Inherited = true)]
public ref class CommerceRuntimeExceptionFilterAttribute sealed : public ExceptionFilterAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/en-us/library/e8kc3626\(v=ax.60\))  
    FilterAttribute  
      ExceptionFilterAttribute  
        Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions.CommerceRuntimeExceptionFilterAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary.ODataExtensions Namespace](microsoft-dynamics-retail-retailserverlibrary-odataextensions-namespace.md)

