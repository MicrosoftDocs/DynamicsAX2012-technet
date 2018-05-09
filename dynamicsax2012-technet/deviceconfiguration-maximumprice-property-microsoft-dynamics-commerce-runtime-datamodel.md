---
title: DeviceConfiguration.MaximumPrice Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: MaximumPrice Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaximumPrice
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.maximumprice(v=AX.60)
ms:contentKeyID: 62211248
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.MaximumPrice
dev_langs:
- CSharp
- C++
- VB
---

# MaximumPrice Property

Gets or sets the maximum price.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("MAXIMUMPRICE")> _
<DataMemberAttribute> _
Public Property MaximumPrice As Decimal
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Decimal

value = instance.MaximumPrice

instance.MaximumPrice = value
```

``` csharp
[ColumnAttribute("MAXIMUMPRICE")]
[DataMemberAttribute]
public decimal MaximumPrice { get; set; }
```

``` c++
[ColumnAttribute(L"MAXIMUMPRICE")]
[DataMemberAttribute]
public:
property Decimal MaximumPrice {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
The maximum price.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

