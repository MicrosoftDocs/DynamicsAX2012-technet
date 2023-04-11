---
title: ChannelProfileProperty.Value Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Value Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfileProperty.Value
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelprofileproperty.value(v=AX.60)
ms:contentKeyID: 49840746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfileProperty.Value
dev_langs:
- CSharp
- C++
- VB
---

# Value Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the property value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("VALUE")> _
<DataMemberAttribute> _
Public Property Value As String
    Get
    Friend Set
'Usage
Dim instance As ChannelProfileProperty
Dim value As String

value = instance.Value
```

``` csharp
[ColumnAttribute("VALUE")]
[DataMemberAttribute]
public string Value { get; internal set; }
```

``` c++
[ColumnAttribute(L"VALUE")]
[DataMemberAttribute]
public:
property String^ Value {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelProfileProperty Class](channelprofileproperty-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

