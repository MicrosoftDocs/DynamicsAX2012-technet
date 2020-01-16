---
title: ChannelAttributeView.TextValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TextValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.TextValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelattributeview.textvalue(v=AX.60)
ms:contentKeyID: 65319996
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelAttributeView.TextValue
dev_langs:
- CSharp
- C++
- VB
---

# TextValue Property

Gets the text value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TEXTVALUE")> _
<IgnoreDataMemberAttribute> _
Public ReadOnly Property TextValue As String
    Get
'Usage
Dim instance As ChannelAttributeView
Dim value As String

value = instance.TextValue
```

``` csharp
[ColumnAttribute("TEXTVALUE")]
[IgnoreDataMemberAttribute]
public string TextValue { get; }
```

``` c++
[ColumnAttribute(L"TEXTVALUE")]
[IgnoreDataMemberAttribute]
public:
property String^ TextValue {
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

