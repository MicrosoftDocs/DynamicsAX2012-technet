---
title: Shift Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Shift Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shift(v=AX.60)
ms:contentKeyID: 62208365
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift
dev_langs:
- CSharp
- C++
- VB
---

# Shift Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Class represents a Shift.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
<DefaultSortOrderAttribute(ColumnName := "STATUSDATETIMEUTC", IsDescending := True)> _
Public Class Shift _
    Inherits CommerceEntity
'Usage
Dim instance As Shift
```

``` csharp
[DataContractAttribute]
[DefaultSortOrderAttribute(ColumnName = "STATUSDATETIMEUTC", IsDescending = true)]
public class Shift : CommerceEntity
```

``` c++
[DataContractAttribute]
[DefaultSortOrderAttribute(ColumnName = L"STATUSDATETIMEUTC", IsDescending = true)]
public ref class Shift : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.Shift  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

