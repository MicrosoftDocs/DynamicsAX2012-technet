---
title: OutputCacheAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: OutputCacheAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.OutputCacheAttribute
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.retailserverlibrary.outputcacheattribute(v=AX.60)
ms:contentKeyID: 62203071
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.OutputCacheAttribute
dev_langs:
- CSharp
- C++
- VB
---

# OutputCacheAttribute Class

The output cache attribute class.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple := False)> _
Public NotInheritable Class OutputCacheAttribute _
    Inherits ActionFilterAttribute
'Usage
Dim instance As OutputCacheAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple = false)]
public sealed class OutputCacheAttribute : ActionFilterAttribute
```

``` c++
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets::Class, AllowMultiple = false)]
public ref class OutputCacheAttribute sealed : public ActionFilterAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/en-us/library/e8kc3626\(v=ax.60\))  
    FilterAttribute  
      ActionFilterAttribute  
        Microsoft.Dynamics.Retail.RetailServerLibrary.OutputCacheAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

