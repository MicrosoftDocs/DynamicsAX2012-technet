---
title: ShippingAdapterConfig.DeliveryModeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryModeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.DeliveryModeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shippingadapterconfig.deliverymodeid(v=AX.60)
ms:contentKeyID: 49855191
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShippingAdapterConfig.DeliveryModeId
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryModeId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery mode identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DELIVERYMODEID")> _
<DataMemberAttribute> _
Public Property DeliveryModeId As String
    Get
    Friend Set
'Usage
Dim instance As ShippingAdapterConfig
Dim value As String

value = instance.DeliveryModeId
```

``` csharp
[ColumnAttribute("DELIVERYMODEID")]
[DataMemberAttribute]
public string DeliveryModeId { get; internal set; }
```

``` c++
[ColumnAttribute(L"DELIVERYMODEID")]
[DataMemberAttribute]
public:
property String^ DeliveryModeId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShippingAdapterConfig Class](shippingadapterconfig-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

