---
title: TransferOrder.InventLocationIdFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: InventLocationIdFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.InventLocationIdFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.inventlocationidfrom(v=AX.60)
ms:contentKeyID: 62208256
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.InventLocationIdFrom
dev_langs:
- CSharp
- C++
- VB
---

# InventLocationIdFrom Property

Gets or sets the from location of the transfer order.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property InventLocationIdFrom As String
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As String

value = instance.InventLocationIdFrom

instance.InventLocationIdFrom = value
```

``` csharp
[DataMemberAttribute]
public string InventLocationIdFrom { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ InventLocationIdFrom {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

