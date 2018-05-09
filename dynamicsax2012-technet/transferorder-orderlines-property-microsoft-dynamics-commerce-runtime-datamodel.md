---
title: TransferOrder.OrderLines Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrderLines Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderLines
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.transferorder.orderlines(v=AX.60)
ms:contentKeyID: 62209508
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrder.OrderLines
dev_langs:
- CSharp
- C++
- VB
---

# OrderLines Property

Gets or sets the transfer order lines.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrderLines As ICollection(Of TransferOrderLine)
    Get
    Set
'Usage
Dim instance As TransferOrder
Dim value As ICollection(Of TransferOrderLine)

value = instance.OrderLines

instance.OrderLines = value
```

``` csharp
[DataMemberAttribute]
public ICollection<TransferOrderLine> OrderLines { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<TransferOrderLine^>^ OrderLines {
    ICollection<TransferOrderLine^>^ get ();
    void set (ICollection<TransferOrderLine^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\))\<[TransferOrderLine](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/en-us/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrder Class](transferorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

