---
title: Channel.EventNotificationProfileId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EventNotificationProfileId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.EventNotificationProfileId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channel.eventnotificationprofileid(v=AX.60)
ms:contentKeyID: 62214652
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.EventNotificationProfileId
dev_langs:
- CSharp
- C++
- VB
---

# EventNotificationProfileId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the event notification profile identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("EVENTNOTIFICATIONPROFILEID")> _
Public Property EventNotificationProfileId As String
    Get
    Friend Set
'Usage
Dim instance As Channel
Dim value As String

value = instance.EventNotificationProfileId
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("EVENTNOTIFICATIONPROFILEID")]
public string EventNotificationProfileId { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"EVENTNOTIFICATIONPROFILEID")]
public:
property String^ EventNotificationProfileId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

