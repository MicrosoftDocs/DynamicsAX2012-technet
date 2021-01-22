---
title: ChargeConfiguration.DeliveryModeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryModeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.DeliveryModeCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeconfiguration.deliverymodecode(v=AX.60)
ms:contentKeyID: 49830229
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeConfiguration.DeliveryModeCode
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeCode Property

Gets or sets the type of the delivery mode for the configuration.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DLVMODECODE")> _
<DataMemberAttribute> _
Public Property DeliveryModeCode As ChargeDeliveryType
    Get
    Set
'Usage
Dim instance As ChargeConfiguration
Dim value As ChargeDeliveryType

value = instance.DeliveryModeCode

instance.DeliveryModeCode = value
```

``` csharp
[ColumnAttribute("DLVMODECODE")]
[DataMemberAttribute]
public ChargeDeliveryType DeliveryModeCode { get; set; }
```

``` c++
[ColumnAttribute(L"DLVMODECODE")]
[DataMemberAttribute]
public:
property ChargeDeliveryType DeliveryModeCode {
    ChargeDeliveryType get ();
    void set (ChargeDeliveryType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeDeliveryType](chargedeliverytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ChargeDeliveryType](chargedeliverytype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChargeConfiguration Class](chargeconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

