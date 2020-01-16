---
title: ShipmentLineMapping.SalesLineNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesLineNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.SalesLineNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentlinemapping.saleslinenumber(v=AX.60)
ms:contentKeyID: 62212035
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentLineMapping.SalesLineNumber
dev_langs:
- CSharp
- C++
- VB
---

# SalesLineNumber Property

Gets or sets the sales line number related to this mapping.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("SALESLINENUM")> _
Public Property SalesLineNumber As Decimal
    Get
    Set
'Usage
Dim instance As ShipmentLineMapping
Dim value As Decimal

value = instance.SalesLineNumber

instance.SalesLineNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("SALESLINENUM")]
public decimal SalesLineNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"SALESLINENUM")]
public:
property Decimal SalesLineNumber {
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

