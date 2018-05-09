---
title: Channel.OrgUnitType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.OrgUnitType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channel.orgunittype(v=AX.60)
ms:contentKeyID: 62213505
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Channel.OrgUnitType
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitType Property

Gets the OrgUnit type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CHANNELTYPE")> _
Public Property OrgUnitType As RetailChannelType
    Get
    Set
'Usage
Dim instance As Channel
Dim value As RetailChannelType

value = instance.OrgUnitType

instance.OrgUnitType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CHANNELTYPE")]
public RetailChannelType OrgUnitType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CHANNELTYPE")]
public:
property RetailChannelType OrgUnitType {
    RetailChannelType get ();
    void set (RetailChannelType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailChannelType](retailchanneltype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [RetailChannelType](retailchanneltype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[Channel Class](channel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

