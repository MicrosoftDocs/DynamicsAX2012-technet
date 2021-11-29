---
title: ShiftDataQueryCriteria.ChannelId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.ChannelId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shiftdataquerycriteria.channelid(v=AX.60)
ms:contentKeyID: 65320992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftDataQueryCriteria.ChannelId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the channel identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ChannelId As Nullable(Of Long)
    Get
    Set
'Usage
Dim instance As ShiftDataQueryCriteria
Dim value As Nullable(Of Long)

value = instance.ChannelId

instance.ChannelId = value
```

``` csharp
[DataMemberAttribute]
public Nullable<long> ChannelId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Nullable<long long> ChannelId {
    Nullable<long long> get ();
    void set (Nullable<long long> value);
}
```

#### Property Value

Type: [System.Nullable](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\))\<[Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))\>  
Returns [Nullable\<T\>](https://technet.microsoft.com/library/b3h38hb0\(v=ax.60\)).  

## See Also

#### Reference

[ShiftDataQueryCriteria Class](shiftdataquerycriteria-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

