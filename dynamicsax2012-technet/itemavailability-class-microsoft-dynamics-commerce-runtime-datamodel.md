---
title: ItemAvailability Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemAvailability Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemavailability(v=AX.60)
ms:contentKeyID: 49845746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability
dev_langs:
- CSharp
- C++
- VB
---

# ItemAvailability Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents an item availablity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ItemAvailability _
    Inherits CommerceEntity _
    Implements IEquatable(Of ItemAvailability)
'Usage
Dim instance As ItemAvailability
```

``` csharp
[DataContractAttribute]
public class ItemAvailability : CommerceEntity, 
    IEquatable<ItemAvailability>
```

``` c++
[DataContractAttribute]
public ref class ItemAvailability : public CommerceEntity, 
    IEquatable<ItemAvailability^>
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemAvailability  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

