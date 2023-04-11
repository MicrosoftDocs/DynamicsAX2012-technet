---
title: EmptyProductDeliveryOptionSetNotification Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmptyProductDeliveryOptionSetNotification Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyProductDeliveryOptionSetNotification.#ctor(Microsoft.Dynamics.Commerce.Runtime.DataModel.Address,System.String,System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.emptyproductdeliveryoptionsetnotification.emptyproductdeliveryoptionsetnotification(v=AX.60)
ms:contentKeyID: 65321765
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyProductDeliveryOptionSetNotification.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# EmptyProductDeliveryOptionSetNotification Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [EmptyProductDeliveryOptionSetNotification](emptyproductdeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    address As Address, _
    itemId As String, _
    inventoryDimensionId As String _
)
'Usage
Dim address As Address
Dim itemId As String
Dim inventoryDimensionId As String

Dim instance As New EmptyProductDeliveryOptionSetNotification(address, _
    itemId, inventoryDimensionId)
```

``` csharp
public EmptyProductDeliveryOptionSetNotification(
    Address address,
    string itemId,
    string inventoryDimensionId
)
```

``` c++
public:
EmptyProductDeliveryOptionSetNotification(
    Address^ address, 
    String^ itemId, 
    String^ inventoryDimensionId
)
```

#### Parameters

  - address  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - itemId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - inventoryDimensionId  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[EmptyProductDeliveryOptionSetNotification Class](emptyproductdeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

