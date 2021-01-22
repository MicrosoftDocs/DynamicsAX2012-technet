---
title: ChargeConfigurationHeader.DeliveryType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.DeliveryType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfigurationheader.deliverytype(v=AX.60)
ms:contentKeyID: 49827820
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfigurationHeader.DeliveryType
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryType Property

Gets or sets granularity of delivery mode selection to search for (i.e. single, group, all).

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Property DeliveryType As ChargeDeliveryType
    Get
    Set
'Usage
Dim instance As ChargeConfigurationHeader
Dim value As ChargeDeliveryType

value = instance.DeliveryType

instance.DeliveryType = value
```

``` csharp
public ChargeDeliveryType DeliveryType { get; set; }
```

``` c++
public:
property ChargeDeliveryType DeliveryType {
    ChargeDeliveryType get ();
    void set (ChargeDeliveryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeDeliveryType](chargedeliverytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeDeliveryType](chargedeliverytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfigurationHeader Class](chargeconfigurationheader-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

