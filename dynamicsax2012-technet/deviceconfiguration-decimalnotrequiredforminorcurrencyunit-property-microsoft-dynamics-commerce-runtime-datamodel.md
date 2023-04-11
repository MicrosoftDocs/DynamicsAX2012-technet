---
title: DeviceConfiguration.DecimalNotRequiredForMinorCurrencyUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DecimalNotRequiredForMinorCurrencyUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DecimalNotRequiredForMinorCurrencyUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.decimalnotrequiredforminorcurrencyunit(v=AX.60)
ms:contentKeyID: 65320218
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.DecimalNotRequiredForMinorCurrencyUnit
dev_langs:
- CSharp
- C++
- VB
---

# DecimalNotRequiredForMinorCurrencyUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DECIMALNOTREQUIREDFORMINORCURRENCYUNIT")> _
Public Property DecimalNotRequiredForMinorCurrencyUnit As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.DecimalNotRequiredForMinorCurrencyUnit

instance.DecimalNotRequiredForMinorCurrencyUnit = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DECIMALNOTREQUIREDFORMINORCURRENCYUNIT")]
public bool DecimalNotRequiredForMinorCurrencyUnit { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DECIMALNOTREQUIREDFORMINORCURRENCYUNIT")]
public:
property bool DecimalNotRequiredForMinorCurrencyUnit {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

