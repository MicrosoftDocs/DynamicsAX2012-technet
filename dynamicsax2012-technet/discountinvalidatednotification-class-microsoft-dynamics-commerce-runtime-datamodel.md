---
title: DiscountInvalidatedNotification Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DiscountInvalidatedNotification Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.discountinvalidatednotification(v=AX.60)
ms:contentKeyID: 65321079
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification
dev_langs:
- CSharp
- C++
- VB
---

# DiscountInvalidatedNotification Class

Indicates that a line Item's discount amount has changed between two separate calls to pricing sub system.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class DiscountInvalidatedNotification _
    Inherits Notification
'Usage
Dim instance As DiscountInvalidatedNotification
```

``` csharp
[DataContractAttribute]
public class DiscountInvalidatedNotification : Notification
```

``` c++
[DataContractAttribute]
public ref class DiscountInvalidatedNotification : public Notification
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.DiscountInvalidatedNotification  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

