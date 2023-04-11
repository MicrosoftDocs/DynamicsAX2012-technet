---
title: ChargeConfigurationHeader.ItemType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.ItemType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.itemtype(v=AX.60)
ms:contentKeyID: 49843804
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.ItemType
dev_langs:
- CSharp
- C++
- VB
---

# ItemType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets granularity of item selection to search for (i.e. single, group, all).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property ItemType As ChargeItemType
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As ChargeItemType

value = instance.ItemType

instance.ItemType = value
```

``` csharp
public ChargeItemType ItemType { get; set; }
```

``` c++
public:
property ChargeItemType ItemType {
    ChargeItemType get ();
    void set (ChargeItemType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeItemType](chargeitemtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeItemType](chargeitemtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

