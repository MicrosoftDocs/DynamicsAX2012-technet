---
title: ItemUnit Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemUnit Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.itemunit(v=AX.60)
ms:contentKeyID: 49827829
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit
dev_langs:
- CSharp
- C++
- VB
---

# ItemUnit Class

Represents an item and unit of measure combination.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ItemUnit _
    Inherits CommerceEntity _
    Implements IEquatable(Of ItemUnit)
'Usage
Dim instance As ItemUnit
```

``` csharp
[DataContractAttribute]
public class ItemUnit : CommerceEntity, IEquatable<ItemUnit>
```

``` c++
[DataContractAttribute]
public ref class ItemUnit : public CommerceEntity, 
    IEquatable<ItemUnit^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/en-us/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemUnit  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

