---
title: ChannelAttributeView.BooleanValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BooleanValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.BooleanValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.booleanvalue(v=AX.60)
ms:contentKeyID: 65317205
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.BooleanValue
dev_langs:
- CSharp
- C++
- VB
---

# BooleanValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the boolean value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BOOLEANVALUE")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property BooleanValue As Integer
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As Integer

value = instance.BooleanValue
```

``` csharp
[ColumnAttribute("BOOLEANVALUE")]
[IgnoreDataMemberAttribute]
public int BooleanValue { get; }
```

``` c++
[ColumnAttribute(L"BOOLEANVALUE")]
[IgnoreDataMemberAttribute]
public:
property int BooleanValue {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ChannelAttributeView Class](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

