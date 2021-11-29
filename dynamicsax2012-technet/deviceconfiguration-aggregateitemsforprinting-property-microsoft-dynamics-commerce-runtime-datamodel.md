---
title: DeviceConfiguration.AggregateItemsForPrinting Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AggregateItemsForPrinting Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AggregateItemsForPrinting
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.aggregateitemsforprinting(v=AX.60)
ms:contentKeyID: 62207246
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AggregateItemsForPrinting
dev_langs:
- CSharp
- C++
- VB
---

# AggregateItemsForPrinting Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether Aggregate Items For Printing value is set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("AGGREGATEITEMSFORPRINTING")> _
<DataMemberAttribute> _
Public Property AggregateItemsForPrinting As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.AggregateItemsForPrinting

instance.AggregateItemsForPrinting = value
```

``` csharp
[ColumnAttribute("AGGREGATEITEMSFORPRINTING")]
[DataMemberAttribute]
public bool AggregateItemsForPrinting { get; set; }
```

``` c++
[ColumnAttribute(L"AGGREGATEITEMSFORPRINTING")]
[DataMemberAttribute]
public:
property bool AggregateItemsForPrinting {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
True if aggregate items for printing is set; otherwise, false.  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

