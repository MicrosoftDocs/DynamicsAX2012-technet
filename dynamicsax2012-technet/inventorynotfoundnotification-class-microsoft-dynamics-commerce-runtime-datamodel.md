---
title: InventoryNotFoundNotification Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryNotFoundNotification Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.inventorynotfoundnotification(v=AX.60)
ms:contentKeyID: 65322130
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification
dev_langs:
- CSharp
- C++
- VB
---

# InventoryNotFoundNotification Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that no inventory for the given sales line were found.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class InventoryNotFoundNotification _
    Inherits Notification
'Usage
Dim instance As InventoryNotFoundNotification
```

``` csharp
[DataContractAttribute]
public class InventoryNotFoundNotification : Notification
```

``` c++
[DataContractAttribute]
public ref class InventoryNotFoundNotification : public Notification
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.InventoryNotFoundNotification  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

