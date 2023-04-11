---
title: DeviceConfiguration.AggregatePayments Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AggregatePayments Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AggregatePayments
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.aggregatepayments(v=AX.60)
ms:contentKeyID: 62213213
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AggregatePayments
dev_langs:
- CSharp
- C++
- VB
---

# AggregatePayments Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether Aggregate payments is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AGGREGATEPAYMENTS")> _
Public Property AggregatePayments As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.AggregatePayments

instance.AggregatePayments = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AGGREGATEPAYMENTS")]
public bool AggregatePayments { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AGGREGATEPAYMENTS")]
public:
property bool AggregatePayments {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if aggregate payments is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

