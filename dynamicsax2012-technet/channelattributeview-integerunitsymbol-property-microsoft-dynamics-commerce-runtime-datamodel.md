---
title: ChannelAttributeView.IntegerUnitSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IntegerUnitSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.IntegerUnitSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.integerunitsymbol(v=AX.60)
ms:contentKeyID: 65321548
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.IntegerUnitSymbol
dev_langs:
- CSharp
- C++
- VB
---

# IntegerUnitSymbol Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the unit symbol of the integer value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INTUNITSYMBOL")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property IntegerUnitSymbol As String
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As String

value = instance.IntegerUnitSymbol
```

``` csharp
[ColumnAttribute("INTUNITSYMBOL")]
[IgnoreDataMemberAttribute]
public string IntegerUnitSymbol { get; }
```

``` c++
[ColumnAttribute(L"INTUNITSYMBOL")]
[IgnoreDataMemberAttribute]
public:
property String^ IntegerUnitSymbol {
    String^ get ();
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelAttributeView Class](channelattributeview-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

