---
title: ReasonCodeLine.Equals Method (ReasonCodeLine) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method (ReasonCodeLine)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine.Equals(Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasoncodeline.equals(v=AX.60)
ms:contentKeyID: 62213054
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# Equals Method (ReasonCodeLine)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Equalses the specified other.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Function Equals ( _
    other As ReasonCodeLine _
) As Boolean
'Usage
Dim instance As ReasonCodeLine
Dim other As ReasonCodeLine
Dim returnValue As Boolean

returnValue = instance.Equals(other)
```

``` csharp
public bool Equals(
    ReasonCodeLine other
)
```

``` c++
public:
virtual bool Equals(
    ReasonCodeLine^ other
) sealed
```

#### Parameters

  - other  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonCodeLine](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if this instance equals to the other instance.  

#### Implements

[IEquatable\<T\>.Equals(T)](https://technet.microsoft.com/library/ms131190\(v=ax.60\))  

## See Also

#### Reference

[ReasonCodeLine Class](reasoncodeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Equals Overload](reasoncodeline-equals-method-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

