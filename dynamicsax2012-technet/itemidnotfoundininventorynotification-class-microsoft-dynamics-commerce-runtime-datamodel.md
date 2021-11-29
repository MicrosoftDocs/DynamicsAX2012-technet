---
title: ItemIdNotFoundInInventoryNotification Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemIdNotFoundInInventoryNotification Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.itemidnotfoundininventorynotification(v=AX.60)
ms:contentKeyID: 65323172
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification
dev_langs:
- CSharp
- C++
- VB
---

# ItemIdNotFoundInInventoryNotification Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that the itemId not found in inventory database when attempting to reserve the item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ItemIdNotFoundInInventoryNotification _
    Inherits Notification
'Usage
Dim instance As ItemIdNotFoundInInventoryNotification
```

``` csharp
[DataContractAttribute]
public class ItemIdNotFoundInInventoryNotification : Notification
```

``` c++
[DataContractAttribute]
public ref class ItemIdNotFoundInInventoryNotification : public Notification
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.ItemIdNotFoundInInventoryNotification  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

