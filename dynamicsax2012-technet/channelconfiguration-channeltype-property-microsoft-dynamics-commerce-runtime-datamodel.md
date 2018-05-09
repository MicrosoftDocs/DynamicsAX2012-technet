---
title: ChannelConfiguration.ChannelType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ChannelType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.channeltype(v=AX.60)
ms:contentKeyID: 62211112
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.ChannelType
dev_langs:
- CSharp
- C++
- VB
---

# ChannelType Property

Gets the channel type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CHANNELTYPE")> _
Public Property ChannelType As RetailChannelType
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As RetailChannelType

value = instance.ChannelType
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CHANNELTYPE")]
public RetailChannelType ChannelType { get; internal set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CHANNELTYPE")]
public:
property RetailChannelType ChannelType {
    RetailChannelType get ();
    internal: void set (RetailChannelType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType](retailchanneltype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailChannelType](retailchanneltype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

