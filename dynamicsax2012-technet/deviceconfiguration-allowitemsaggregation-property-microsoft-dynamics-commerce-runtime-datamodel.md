---
title: DeviceConfiguration.AllowItemsAggregation Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: AllowItemsAggregation Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AllowItemsAggregation
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.deviceconfiguration.allowitemsaggregation(v=AX.60)
ms:contentKeyID: 62205908
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.DeviceConfiguration.AllowItemsAggregation
dev_langs:
- CSharp
- C++
- VB
---

# AllowItemsAggregation Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to aggregate same items on the cart.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("AGGREGATEITEMS")> _
Public Property AllowItemsAggregation As Boolean
    Get
    Set
'Usage
Dim instance As DeviceConfiguration
Dim value As Boolean

value = instance.AllowItemsAggregation

instance.AllowItemsAggregation = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("AGGREGATEITEMS")]
public bool AllowItemsAggregation { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"AGGREGATEITEMS")]
public:
property bool AllowItemsAggregation {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[DeviceConfiguration Class](deviceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

