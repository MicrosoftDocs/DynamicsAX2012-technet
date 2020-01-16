---
title: GetProductDeliveryOptionsRequest.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsRequest.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getproductdeliveryoptionsrequest.inventorydimensionid(v=AX.60)
ms:contentKeyID: 49850241
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetProductDeliveryOptionsRequest.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property

Gets or sets the inventory dimension identifier for which to fetch delivery options.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Set
'Usage
Dim instance As GetProductDeliveryOptionsRequest
Dim value As String

value = instance.InventoryDimensionId

instance.InventoryDimensionId = value
```

``` csharp
[DataMemberAttribute]
public string InventoryDimensionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventoryDimensionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetProductDeliveryOptionsRequest Class](getproductdeliveryoptionsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

