---
title: TypeCache.TargetType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TargetType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.TargetType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.typecache.targettype(v=AX.60)
ms:contentKeyID: 65320569
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.TargetType
dev_langs:
- CSharp
- C++
- VB
---

# TargetType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the type that the instance of this class operates on.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Property TargetType As Type
    Get
    Private Set
'Usage
Dim instance As TypeCache
Dim value As Type

value = instance.TargetType
```

``` csharp
public Type TargetType { get; private set; }
```

``` c++
public:
property Type^ TargetType {
    Type^ get ();
    private: void set (Type^ value);
}
```

#### Property Value

Type: [System.Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\))  
Returns [Type](https://technet.microsoft.com/library/42892f65\(v=ax.60\)).  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

