---
title: ShipmentPublishingStatus.LastModifiedDateTime Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LastModifiedDateTime Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.LastModifiedDateTime
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingstatus.lastmodifieddatetime(v=AX.60)
ms:contentKeyID: 62211652
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.LastModifiedDateTime
dev_langs:
- CSharp
- C++
- VB
---

# LastModifiedDateTime Property


**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LASTMODIFIEDDATETIME")> _
Public Property LastModifiedDateTime As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ShipmentPublishingStatus
Dim value As DateTimeOffset

value = instance.LastModifiedDateTime
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LASTMODIFIEDDATETIME")]
public DateTimeOffset LastModifiedDateTime { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LASTMODIFIEDDATETIME")]
public:
property DateTimeOffset LastModifiedDateTime {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentPublishingStatus Class](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

