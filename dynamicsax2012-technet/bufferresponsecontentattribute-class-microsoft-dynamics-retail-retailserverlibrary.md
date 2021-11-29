---
title: BufferResponseContentAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: BufferResponseContentAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.bufferresponsecontentattribute(v=AX.60)
ms:contentKeyID: 62202503
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute
dev_langs:
- CSharp
- C++
- VB
---

# BufferResponseContentAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Attribute that will make sure response gets buffered before return.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<AttributeUsageAttribute(AttributeTargets.Class Or AttributeTargets.Method, AllowMultiple := False,  _
    Inherited := True)> _
Public NotInheritable Class BufferResponseContentAttribute _
    Inherits Attribute _
    Implements IActionFilter, IFilter
'Usage
Dim instance As BufferResponseContentAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets.Class|AttributeTargets.Method, AllowMultiple = false, 
    Inherited = true)]
public sealed class BufferResponseContentAttribute : Attribute, 
    IActionFilter, IFilter
```

``` c++
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets::Class|AttributeTargets::Method, AllowMultiple = false, 
    Inherited = true)]
public ref class BufferResponseContentAttribute sealed : public Attribute, 
    IActionFilter, IFilter
```

## Remarks

By default, object get serialized outside the scope of the exception filter. Applying this action filter globally will force responses to get serialized within the exception filter scope.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Retail.RetailServerLibrary.BufferResponseContentAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

