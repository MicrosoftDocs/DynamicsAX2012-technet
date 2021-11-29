---
title: ChannelAttributeView.IntegerValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IntegerValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.IntegerValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.integervalue(v=AX.60)
ms:contentKeyID: 65319269
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.IntegerValue
dev_langs:
- CSharp
- C++
- VB
---

# IntegerValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the integer value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("INTVALUE")> _
Public ReadOnly Property IntegerValue As Integer
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As Integer

value = instance.IntegerValue
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("INTVALUE")]
public int IntegerValue { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"INTVALUE")]
public:
property int IntegerValue {
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

