---
title: ShipmentPublishingStatus.ChannelBatchId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelBatchId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.ChannelBatchId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingstatus.channelbatchid(v=AX.60)
ms:contentKeyID: 62215113
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.ChannelBatchId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelBatchId Property

Gets or sets the channel batch id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELBATCHID")> _
Public Property ChannelBatchId As String
    Get
    Set
'Usage
Dim instance As ShipmentPublishingStatus
Dim value As String

value = instance.ChannelBatchId

instance.ChannelBatchId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELBATCHID")]
public string ChannelBatchId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELBATCHID")]
public:
property String^ ChannelBatchId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentPublishingStatus Class](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

