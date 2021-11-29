---
title: TransferOrderLine.QuantityReceived Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityReceived Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityReceived
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.transferorderline.quantityreceived(v=AX.60)
ms:contentKeyID: 62214839
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TransferOrderLine.QuantityReceived
dev_langs:
- CSharp
- C++
- VB
---

# QuantityReceived Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the total quantity received.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("QUANTITYRECEIVED")> _
Public Property QuantityReceived As Decimal
    Get
    Set
'Usage
Dim instance As TransferOrderLine
Dim value As Decimal

value = instance.QuantityReceived

instance.QuantityReceived = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("QUANTITYRECEIVED")]
public decimal QuantityReceived { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"QUANTITYRECEIVED")]
public:
property Decimal QuantityReceived {
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

