---
title: ShipmentLineMapping.ShipmentLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShipmentLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.ShipmentLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentlinemapping.shipmentlinenumber(v=AX.60)
ms:contentKeyID: 62209350
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.ShipmentLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# ShipmentLineNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the packing slip line number related to this mapping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PACKINGSLIPLINENUM")> _
<DataMemberAttribute> _
Public Property ShipmentLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As ShipmentLineMapping
Dim value As Decimal

value = instance.ShipmentLineNumber

instance.ShipmentLineNumber = value
```

``` csharp
[ColumnAttribute("PACKINGSLIPLINENUM")]
[DataMemberAttribute]
public decimal ShipmentLineNumber { get; set; }
```

``` c++
[ColumnAttribute(L"PACKINGSLIPLINENUM")]
[DataMemberAttribute]
public:
property Decimal ShipmentLineNumber {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentLineMapping Class](shipmentlinemapping-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

