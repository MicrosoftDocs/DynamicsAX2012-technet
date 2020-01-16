---
title: CommerceEntity.Clone(T) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Clone(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.Clone``1
ms:mtpsurl: https://technet.microsoft.com/library/Dn696557(v=AX.60)
ms:contentKeyID: 62207956
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.Clone``1
dev_langs:
- CSharp
- C++
- VB
---

# Clone(T) Method

Returns a "deep-copy" of the given object.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overridable Function Clone(Of T As {New, CommerceEntity}) As T
'Usage
Dim instance As CommerceEntity
Dim returnValue As T

returnValue = instance.Clone()
```

``` csharp
public virtual T Clone<T>()
where T : new(), CommerceEntity
```

``` c++
public:
generic<typename T>
where T : gcnew(), CommerceEntity
virtual T Clone()
```

#### Type Parameters

  - T

#### Return Value

Type: T  
The cloned object.  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

