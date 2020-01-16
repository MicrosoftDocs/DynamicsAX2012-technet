---
title: TransferOrderLine.QuantityShipNow Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityShipNow Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityShipNow
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.quantityshipnow(v=AX.60)
ms:contentKeyID: 62213901
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityShipNow
dev_langs:
- CSharp
- C++
- VB
---

# QuantityShipNow Property

Gets or sets the quantity shipped in current session.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUANTITYSHIPNOW")> _
Public Property QuantityShipNow As Decimal
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Decimal

value = instance.QuantityShipNow

instance.QuantityShipNow = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUANTITYSHIPNOW")]
public decimal QuantityShipNow { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUANTITYSHIPNOW")]
public:
property Decimal QuantityShipNow {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[TransferOrderLine Class](transferorderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

