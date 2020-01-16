---
title: ChannelAttributeView.FloatUnitSymbol Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FloatUnitSymbol Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.FloatUnitSymbol
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.floatunitsymbol(v=AX.60)
ms:contentKeyID: 65320667
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.FloatUnitSymbol
dev_langs:
- CSharp
- C++
- VB
---

# FloatUnitSymbol Property

Gets the unit symbol of the float value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("FLOATUNITSYMBOL")> _
Public ReadOnly Property FloatUnitSymbol As String
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As String

value = instance.FloatUnitSymbol
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("FLOATUNITSYMBOL")]
public string FloatUnitSymbol { get; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"FLOATUNITSYMBOL")]
public:
property String^ FloatUnitSymbol {
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

