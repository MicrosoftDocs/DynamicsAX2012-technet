---
title: ReadOnlyAttribute Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReadOnlyAttribute Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.readonlyattribute(v=AX.60)
ms:contentKeyID: 62210743
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute
dev_langs:
- CSharp
- C++
- VB
---

# ReadOnlyAttribute Class

Annotates that a property is read-only outside commerce runtime.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
<AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple := False)> _
Public NotInheritable Class ReadOnlyAttribute _
    Inherits Attribute
'Usage
Dim instance As ReadOnlyAttribute
```

``` csharp
[AttributeUsageAttribute(AttributeTargets.Property, AllowMultiple = false)]
public sealed class ReadOnlyAttribute : Attribute
```

``` c++
[AttributeUsageAttribute(AttributeTargets::Property, AllowMultiple = false)]
public ref class ReadOnlyAttribute sealed : public Attribute
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [System.Attribute](https://technet.microsoft.com/en-us/library/e8kc3626\(v=ax.60\))  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ReadOnlyAttribute  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

