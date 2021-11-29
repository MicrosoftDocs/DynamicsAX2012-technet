---
title: EmptyProductDeliveryOptionSetNotification.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyProductDeliveryOptionSetNotification.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.emptyproductdeliveryoptionsetnotification.inventorydimensionid(v=AX.60)
ms:contentKeyID: 65320632
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.EmptyProductDeliveryOptionSetNotification.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the inventory dimension identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Private Set
'Usage
Dim instance As EmptyProductDeliveryOptionSetNotification
Dim value As String

value = instance.InventoryDimensionId
```

``` csharp
[DataMemberAttribute]
public string InventoryDimensionId { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryDimensionId {
    String^ get ();
    private: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[EmptyProductDeliveryOptionSetNotification Class](emptyproductdeliveryoptionsetnotification-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

