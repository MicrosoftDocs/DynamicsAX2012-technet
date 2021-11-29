---
title: ChannelProfileProperty.Key Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Key Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfileProperty.Key
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelprofileproperty.key(v=AX.60)
ms:contentKeyID: 49834814
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfileProperty.Key
dev_langs:
- CSharp
- C++
- VB
---

# Key Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the property key.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("KEY")> _
<DataMemberAttribute> _
Public Property Key As Integer
    Get
    Friend Set
'Usage
Dim instance As ChannelProfileProperty
Dim value As Integer

value = instance.Key
```

``` csharp
[ColumnAttribute("KEY")]
[DataMemberAttribute]
public int Key { get; internal set; }
```

``` c++
[ColumnAttribute(L"KEY")]
[DataMemberAttribute]
public:
property int Key {
    int get ();
    internal: void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelProfileProperty Class](channelprofileproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

