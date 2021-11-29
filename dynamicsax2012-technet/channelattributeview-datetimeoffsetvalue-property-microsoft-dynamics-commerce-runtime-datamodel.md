---
title: ChannelAttributeView.DateTimeOffsetValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateTimeOffsetValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.DateTimeOffsetValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.datetimeoffsetvalue(v=AX.60)
ms:contentKeyID: 65315907
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.DateTimeOffsetValue
dev_langs:
- CSharp
- C++
- VB
---

# DateTimeOffsetValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the date/time offset value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATETIMEVALUE")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property DateTimeOffsetValue As DateTimeOffset
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As DateTimeOffset

value = instance.DateTimeOffsetValue
```

``` csharp
[ColumnAttribute("DATETIMEVALUE")]
[IgnoreDataMemberAttribute]
public DateTimeOffset DateTimeOffsetValue { get; }
```

``` c++
[ColumnAttribute(L"DATETIMEVALUE")]
[IgnoreDataMemberAttribute]
public:
property DateTimeOffset DateTimeOffsetValue {
    DateTimeOffset get ();
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ChannelAttributeView Class](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

