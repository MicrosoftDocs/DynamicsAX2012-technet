---
title: PickingListLine.PurchaseReceivedNow Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PurchaseReceivedNow Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.PurchaseReceivedNow
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.pickinglistline.purchasereceivednow(v=AX.60)
ms:contentKeyID: 62209042
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PickingListLine.PurchaseReceivedNow
dev_langs:
- CSharp
- C++
- VB
---

# PurchaseReceivedNow Property

Gets or sets the quantity received in current session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PURCHASERECEIVEDNOW")> _
<DataMemberAttribute> _
Public Property PurchaseReceivedNow As Decimal
    Get
    Set
'Usage
Dim instance As PickingListLine
Dim value As Decimal

value = instance.PurchaseReceivedNow

instance.PurchaseReceivedNow = value
```

``` csharp
[ColumnAttribute("PURCHASERECEIVEDNOW")]
[DataMemberAttribute]
public decimal PurchaseReceivedNow { get; set; }
```

``` c++
[ColumnAttribute(L"PURCHASERECEIVEDNOW")]
[DataMemberAttribute]
public:
property Decimal PurchaseReceivedNow {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[PickingListLine Class](pickinglistline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

