---
title: ShipmentPublishingStatus.PublishingMessage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublishingMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.PublishingMessage
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.shipmentpublishingstatus.publishingmessage(v=AX.60)
ms:contentKeyID: 62213138
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShipmentPublishingStatus.PublishingMessage
dev_langs:
- CSharp
- C++
- VB
---

# PublishingMessage Property

Gets or sets the publishing message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("PUBLISHMESSAGE")> _
<DataMemberAttribute> _
Public Property PublishingMessage As String
    Get
    Set
'Usage
Dim instance As ShipmentPublishingStatus
Dim value As String

value = instance.PublishingMessage

instance.PublishingMessage = value
```

``` csharp
[ColumnAttribute("PUBLISHMESSAGE")]
[DataMemberAttribute]
public string PublishingMessage { get; set; }
```

``` c++
[ColumnAttribute(L"PUBLISHMESSAGE")]
[DataMemberAttribute]
public:
property String^ PublishingMessage {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ShipmentPublishingStatus Class](shipmentpublishingstatus-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

