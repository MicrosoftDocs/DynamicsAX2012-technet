---
title: Device.ChannelName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.ChannelName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.device.channelname(v=AX.60)
ms:contentKeyID: 62215029
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Device.ChannelName
dev_langs:
- CSharp
- C++
- VB
---

# ChannelName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the name of the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELNAME")> _
Public Property ChannelName As String
    Get
    Set
'Usage
Dim instance As Device
Dim value As String

value = instance.ChannelName

instance.ChannelName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELNAME")]
public string ChannelName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELNAME")]
public:
property String^ ChannelName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The channel name.  

## See Also

#### Reference

[Device Class](device-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

