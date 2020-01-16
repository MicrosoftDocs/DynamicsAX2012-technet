---
title: DeviceConfiguration.UseDestinationBasedTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseDestinationBasedTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.UseDestinationBasedTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.usedestinationbasedtax(v=AX.60)
ms:contentKeyID: 62208231
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.UseDestinationBasedTax
dev_langs:
- CSharp
- C++
- VB
---

# UseDestinationBasedTax Property

Gets or sets a value indicating whether use destination based tax is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USEDESTINATIONBASEDTAX")> _
Public Property UseDestinationBasedTax As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.UseDestinationBasedTax

instance.UseDestinationBasedTax = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USEDESTINATIONBASEDTAX")]
public bool UseDestinationBasedTax { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USEDESTINATIONBASEDTAX")]
public:
property bool UseDestinationBasedTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if use destination based tax is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

