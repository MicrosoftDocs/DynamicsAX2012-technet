---
title: PropertyColumnPair.Property Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Property Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.Property
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.propertycolumnpair.property(v=AX.60)
ms:contentKeyID: 65317361
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PropertyColumnPair.Property
dev_langs:
- CSharp
- C++
- VB
---

# Property Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the property information.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property Property As PropertyInfo
    Get
    Private Set
'Usage
Dim instance As PropertyColumnPair
Dim value As PropertyInfo

value = instance.Property
```

``` csharp
public PropertyInfo Property { get; private set; }
```

``` c++
public:
property PropertyInfo^ Property {
    PropertyInfo^ get ();
    private: void set (PropertyInfo^ value);
}
```

#### Property Value

Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\))  
Returns [PropertyInfo](https://technet.microsoft.com/library/8z852kf5\(v=ax.60\)).  

## See Also

#### Reference

[PropertyColumnPair Class](propertycolumnpair-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

