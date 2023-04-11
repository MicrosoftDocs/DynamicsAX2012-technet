---
title: CacheAttribute Class (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: CacheAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.Data.CacheAttribute
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.cacheattribute(v=AX.60)
ms:contentKeyID: 65319218
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.CacheAttribute
dev_langs:
- CSharp
- C++
- VB
---

# CacheAttribute Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a cache providers used within the Commerce Runtime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple := False)> _
<MetadataAttributeAttribute> _
Public NotInheritable Class CacheAttribute _
    Inherits ExportAttribute
'Usage
Dim instance As CacheAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Class, AllowMultiple = false)]
[MetadataAttributeAttribute]
public sealed class CacheAttribute : ExportAttribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Class, AllowMultiple = false)]
[MetadataAttributeAttribute]
public ref class CacheAttribute sealed : public ExportAttribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/library/e8kc3626\(v=ax.60\))  
    ExportAttribute  
      Microsoft.Dynamics.Commerce.Runtime.Data.CacheAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

