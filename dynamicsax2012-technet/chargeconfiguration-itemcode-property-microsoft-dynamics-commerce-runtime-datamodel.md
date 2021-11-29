---
title: ChargeConfiguration.ItemCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.itemcode(v=AX.60)
ms:contentKeyID: 49820799
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.ItemCode
dev_langs:
- CSharp
- C++
- VB
---

# ItemCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the type of the item for the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ITEMCODE")> _
Public Property ItemCode As ChargeItemType
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeItemType

value = instance.ItemCode

instance.ItemCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ITEMCODE")]
public ChargeItemType ItemCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ITEMCODE")]
public:
property ChargeItemType ItemCode {
    ChargeItemType get ();
    void set (ChargeItemType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeItemType](chargeitemtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeItemType](chargeitemtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

