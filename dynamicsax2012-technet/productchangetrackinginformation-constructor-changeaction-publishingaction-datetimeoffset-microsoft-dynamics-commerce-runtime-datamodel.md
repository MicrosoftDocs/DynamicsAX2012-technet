---
title: ProductChangeTrackingInformation Constructor (ChangeAction, PublishingAction, DateTimeOffset) (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ProductChangeTrackingInformation Constructor (ChangeAction, PublishingAction, DateTimeOffset)
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductChangeTrackingInformation.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction,Microsoft.Dynamics.Commerce.Runtime.DataModel.PublishingAction,System.DateTimeOffset)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productchangetrackinginformation.productchangetrackinginformation(v=AX.60)
ms:contentKeyID: 65323104
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- vb
- csharp
- c++
---

# ProductChangeTrackingInformation Constructor (ChangeAction, PublishingAction, DateTimeOffset)


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    changeAction As ChangeAction, _
    publishingAction As PublishingAction, _
    dateTimeOffset As DateTimeOffset _
)
'Usage
Dim changeAction As ChangeAction
Dim publishingAction As PublishingAction
Dim dateTimeOffset As DateTimeOffset

Dim instance As New ProductChangeTrackingInformation(changeAction, _
    publishingAction, dateTimeOffset)
```

``` csharp
public ProductChangeTrackingInformation(
    ChangeAction changeAction,
    PublishingAction publishingAction,
    DateTimeOffset dateTimeOffset
)
```

``` c++
public:
ProductChangeTrackingInformation(
    ChangeAction changeAction, 
    PublishingAction publishingAction, 
    DateTimeOffset dateTimeOffset
)
```

#### Parameters

  - changeAction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChangeAction](changeaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - publishingAction  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PublishingAction](publishingaction-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - dateTimeOffset  
    Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  

## See Also

#### Reference

[ProductChangeTrackingInformation Class](productchangetrackinginformation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[ProductChangeTrackingInformation Overload](productchangetrackinginformation-constructor-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

