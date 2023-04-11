---
title: LineDeliveryPreferenceTypeRecord.DeliveryPreferenceType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DeliveryPreferenceType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreferenceTypeRecord.DeliveryPreferenceType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.linedeliverypreferencetyperecord.deliverypreferencetype(v=AX.60)
ms:contentKeyID: 65316055
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LineDeliveryPreferenceTypeRecord.DeliveryPreferenceType
dev_langs:
- CSharp
- C++
- VB
---

# DeliveryPreferenceType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the delivery preference type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DELIVERYPREFERENCETYPE")> _
<IgnoreDataMemberAttribute> _
Public Property DeliveryPreferenceType As DeliveryPreferenceType
    Get
    Friend Set
'Usage
Dim instance As LineDeliveryPreferenceTypeRecord
Dim value As DeliveryPreferenceType

value = instance.DeliveryPreferenceType
```

``` csharp
[ColumnAttribute("DELIVERYPREFERENCETYPE")]
[IgnoreDataMemberAttribute]
public DeliveryPreferenceType DeliveryPreferenceType { get; internal set; }
```

``` c++
[ColumnAttribute(L"DELIVERYPREFERENCETYPE")]
[IgnoreDataMemberAttribute]
public:
property DeliveryPreferenceType DeliveryPreferenceType {
    DeliveryPreferenceType get ();
    internal: void set (DeliveryPreferenceType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [DeliveryPreferenceType](deliverypreferencetype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LineDeliveryPreferenceTypeRecord Class](linedeliverypreferencetyperecord-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

