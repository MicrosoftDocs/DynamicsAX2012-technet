---
title: DeviceConfiguration.UseCustomerBasedTax Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseCustomerBasedTax Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.UseCustomerBasedTax
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.usecustomerbasedtax(v=AX.60)
ms:contentKeyID: 62209087
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.UseCustomerBasedTax
dev_langs:
- CSharp
- C++
- VB
---

# UseCustomerBasedTax Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether use customer based tax is enabled.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("USECUSTOMERBASEDTAX")> _
Public Property UseCustomerBasedTax As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.UseCustomerBasedTax

instance.UseCustomerBasedTax = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("USECUSTOMERBASEDTAX")]
public bool UseCustomerBasedTax { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"USECUSTOMERBASEDTAX")]
public:
property bool UseCustomerBasedTax {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
The value true if use customer based tax is enabled; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

