---
title: TypeCache.TryGetAttribute(T) Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TryGetAttribute(T) Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.TryGetAttribute``1(System.Reflection.PropertyInfo,``0@)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn969171(v=AX.60)
ms:contentKeyID: 65322786
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TypeCache.TryGetAttribute``1
dev_langs:
- CSharp
- C++
- VB
---

# TryGetAttribute(T) Method

Tries to get the attribute if specified on the property property.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Protected Shared Function TryGetAttribute(Of T As Attribute) ( _
    property As PropertyInfo, _
    <OutAttribute> ByRef attribute As T _
) As Boolean
'Usage
Dim property As PropertyInfo
Dim attribute As T
Dim returnValue As Boolean

returnValue = TypeCache.TryGetAttribute(property, _
    attribute)
```

``` csharp
protected static bool TryGetAttribute<T>(
    PropertyInfo property,
    out T attribute
)
where T : Attribute
```

``` c++
protected:
generic<typename T>
where T : Attribute
static bool TryGetAttribute(
    PropertyInfo^ property, 
    [OutAttribute] T% attribute
)
```

#### Type Parameters

  - T

#### Parameters

  - property  
    Type: [System.Reflection.PropertyInfo](https://technet.microsoft.com/en-us/library/8z852kf5\(v=ax.60\))  

<!-- end list -->

  - attribute  
    Type: T  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
A value indicating whether the attribute is specified by the property or not.  

## See Also

#### Reference

[TypeCache Class](typecache-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

