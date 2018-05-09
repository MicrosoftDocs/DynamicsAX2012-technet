---
title: ShipmentPublishingStatus.PublishingStatus Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublishingStatus Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.PublishingStatus
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingstatus.publishingstatus(v=AX.60)
ms:contentKeyID: 62206520
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.PublishingStatus
dev_langs:
- CSharp
- C++
- VB
---

# PublishingStatus Property

Gets or sets the publishing status.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PUBLISHSTATUS")> _
<DataMemberAttribute> _
Public Property PublishingStatus As ShipmentPublishingActionStatus
    Get
    Set
'Usage
Dim instance As ShipmentPublishingStatus
Dim value As ShipmentPublishingActionStatus

value = instance.PublishingStatus

instance.PublishingStatus = value
```

``` csharp
[ColumnAttribute("PUBLISHSTATUS")]
[DataMemberAttribute]
public ShipmentPublishingActionStatus PublishingStatus { get; set; }
```

``` c++
[ColumnAttribute(L"PUBLISHSTATUS")]
[DataMemberAttribute]
public:
property ShipmentPublishingActionStatus PublishingStatus {
    ShipmentPublishingActionStatus get ();
    void set (ShipmentPublishingActionStatus value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingActionStatus](shipmentpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [ShipmentPublishingActionStatus](shipmentpublishingactionstatus-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ShipmentPublishingStatus Class](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

