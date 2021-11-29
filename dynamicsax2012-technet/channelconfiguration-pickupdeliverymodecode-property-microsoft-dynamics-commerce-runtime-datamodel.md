---
title: ChannelConfiguration.PickupDeliveryModeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PickupDeliveryModeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.PickupDeliveryModeCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.pickupdeliverymodecode(v=AX.60)
ms:contentKeyID: 49823977
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.PickupDeliveryModeCode
dev_langs:
- CSharp
- C++
- VB
---

# PickupDeliveryModeCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery mode code for pickup at store.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PICKUPDELIVERYMODECODE")> _
<DataMemberAttribute> _
Public Property PickupDeliveryModeCode As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.PickupDeliveryModeCode
```

``` csharp
[ColumnAttribute("PICKUPDELIVERYMODECODE")]
[DataMemberAttribute]
public string PickupDeliveryModeCode { get; internal set; }
```

``` c++
[ColumnAttribute(L"PICKUPDELIVERYMODECODE")]
[DataMemberAttribute]
public:
property String^ PickupDeliveryModeCode {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

