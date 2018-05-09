---
title: DeviceConfiguration.MaximumQuantity Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumQuantity Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaximumQuantity
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.maximumquantity(v=AX.60)
ms:contentKeyID: 62213547
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaximumQuantity
dev_langs:
- CSharp
- C++
- VB
---

# MaximumQuantity Property

Gets or sets the maximum quantity.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMQTY")> _
<DataMemberAttribute> _
Public Property MaximumQuantity As Decimal
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Decimal

value = instance.MaximumQuantity

instance.MaximumQuantity = value
```

``` csharp
[ColumnAttribute("MAXIMUMQTY")]
[DataMemberAttribute]
public decimal MaximumQuantity { get; set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMQTY")]
[DataMemberAttribute]
public:
property Decimal MaximumQuantity {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The maximum quantity.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

