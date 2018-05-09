---
title: TaxableItem.NetAmount Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NetAmount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem.netamount(v=AX.60)
ms:contentKeyID: 49824406
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem.NetAmount
dev_langs:
- CSharp
- C++
- VB
---

# NetAmount Property

Gets or sets the net amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NETAMOUNT")> _
<DataMemberAttribute> _
Public Property NetAmount As Decimal
    Get
    Set
'Usage
Dim instance As TaxableItem
Dim value As Decimal

value = instance.NetAmount

instance.NetAmount = value
```

``` csharp
[ColumnAttribute("NETAMOUNT")]
[DataMemberAttribute]
public decimal NetAmount { get; set; }
```

``` c++
[ColumnAttribute(L"NETAMOUNT")]
[DataMemberAttribute]
public:
property Decimal NetAmount {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The net amount.  

## See Also

#### Reference

[TaxableItem Class](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

