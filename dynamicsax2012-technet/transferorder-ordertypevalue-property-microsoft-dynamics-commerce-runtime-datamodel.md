---
title: TransferOrder.OrderTypeValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderTypeValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderTypeValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.ordertypevalue(v=AX.60)
ms:contentKeyID: 62214368
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderTypeValue
dev_langs:
- CSharp
- C++
- VB
---

# OrderTypeValue Property

Gets or sets the value of the PurchaseTransferOrderType enum. Used by OData only.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderTypeValue As Integer
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As Integer

value = instance.OrderTypeValue

instance.OrderTypeValue = value
```

``` csharp
[DataMemberAttribute]
public int OrderTypeValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int OrderTypeValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

