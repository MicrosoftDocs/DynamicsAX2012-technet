---
title: RetailServerQueryableAttribute Class (Microsoft.Dynamics.Retail.RetailServerLibrary)
TOCTitle: RetailServerQueryableAttribute Class
ms:assetid: T:Microsoft.Dynamics.Retail.RetailServerLibrary.RetailServerQueryableAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.retailserverlibrary.retailserverqueryableattribute(v=AX.60)
ms:contentKeyID: 62202350
author: Khairunj
ms.date: 04/21/2014
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.RetailServerLibrary.RetailServerQueryableAttribute
dev_langs:
- CSharp
- C++
- VB
---

# RetailServerQueryableAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The store server queryable attribute.

**Namespace:**  [Microsoft.Dynamics.Retail.RetailServerLibrary](microsoft-dynamics-retail-retailserverlibrary-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.RetailServerLibrary (in Microsoft.Dynamics.Retail.RetailServerLibrary.dll)

## Syntax

``` vb
'Declaration
<ComVisibleAttribute(False)> _
<AttributeUsageAttribute(AttributeTargets.Class Or AttributeTargets.Method, Inherited := True,  _
    AllowMultiple := False)> _
Public NotInheritable Class RetailServerQueryableAttribute _
    Inherits QueryableAttribute
'Usage
Dim instance As RetailServerQueryableAttribute
```

``` csharp
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets.Class|AttributeTargets.Method, Inherited = true, 
    AllowMultiple = false)]
public sealed class RetailServerQueryableAttribute : QueryableAttribute
```

``` c++
[ComVisibleAttribute(false)]
[AttributeUsageAttribute(AttributeTargets::Class|AttributeTargets::Method, Inherited = true, 
    AllowMultiple = false)]
public ref class RetailServerQueryableAttribute sealed : public QueryableAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    FilterAttribute  
      ActionFilterAttribute  
        QueryableAttribute  
          Microsoft.Dynamics.Retail.RetailServerLibrary.RetailServerQueryableAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.RetailServerLibrary Namespace](microsoft-dynamics-retail-retailserverlibrary-namespace.md)

