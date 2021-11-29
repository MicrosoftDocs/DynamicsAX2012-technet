---
title: InvalidTaxGroupNotification Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InvalidTaxGroupNotification Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.invalidtaxgroupnotification(v=AX.60)
ms:contentKeyID: 65322179
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification
dev_langs:
- CSharp
- C++
- VB
---

# InvalidTaxGroupNotification Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Indicates that Tax service was unable to find an associated sales tax group for the given shipping address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class InvalidTaxGroupNotification _
    Inherits Notification
'Usage
Dim instance As InvalidTaxGroupNotification
```

``` csharp
[DataContractAttribute]
public class InvalidTaxGroupNotification : Notification
```

``` c++
[DataContractAttribute]
public ref class InvalidTaxGroupNotification : public Notification
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.Notification](notification-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.InvalidTaxGroupNotification  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

