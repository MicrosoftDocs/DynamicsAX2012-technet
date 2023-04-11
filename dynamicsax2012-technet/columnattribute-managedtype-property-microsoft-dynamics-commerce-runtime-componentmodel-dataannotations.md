---
title: ColumnAttribute.ManagedType Property  (Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations)
TOCTitle: ManagedType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute.ManagedType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.componentmodel.dataannotations.columnattribute.managedtype(v=AX.60)
ms:contentKeyID: 65320198
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations.ColumnAttribute.ManagedType
dev_langs:
- CSharp
- C++
- VB
---

# ManagedType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type which is expected to be used in a property bag of commerce entity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property ManagedType As Type
    Get
    Set
'Usage
Dim instance As ColumnAttribute
Dim value As Type

value = instance.ManagedType

instance.ManagedType = value
```

``` csharp
public Type ManagedType { get; set; }
```

``` c++
public:
property Type^ ManagedType {
    Type^ get ();
    void set (Type^ value);
}
```

#### Property Value

Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  
The type.  

## See Also

#### Reference

[ColumnAttribute Class](columnattribute-class-microsoft-dynamics-commerce-runtime-componentmodel-dataannotations.md)

[Microsoft.Dynamics.Commerce.Runtime.ComponentModel.DataAnnotations Namespace](microsoft-dynamics-commerce-runtime-componentmodel-dataannotations-namespace.md)

