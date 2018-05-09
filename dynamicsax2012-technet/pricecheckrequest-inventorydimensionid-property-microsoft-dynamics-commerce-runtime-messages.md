---
title: PriceCheckRequest.InventoryDimensionId Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: InventoryDimensionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.InventoryDimensionId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.messages.pricecheckrequest.inventorydimensionid(v=AX.60)
ms:contentKeyID: 62207480
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.PriceCheckRequest.InventoryDimensionId
dev_langs:
- CSharp
- C++
- VB
---

# InventoryDimensionId Property

Gets the inventory dimension identifer used to specify a variant.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventoryDimensionId As String
    Get
    Private Set
'Usage
Dim instance As PriceCheckRequest
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

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceCheckRequest Class](pricecheckrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

