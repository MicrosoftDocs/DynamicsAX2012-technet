---
title: ChannelLanguage.IsDefault Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsDefault Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.IsDefault
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channellanguage.isdefault(v=AX.60)
ms:contentKeyID: 49843089
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelLanguage.IsDefault
dev_langs:
- CSharp
- C++
- VB
---

# IsDefault Property

Gets a value indicating whether this is the default language of the channel.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISDEFAULT")> _
Public Property IsDefault As Boolean
    Get
    Friend Set
'Usage
Dim instance As ChannelLanguage
Dim value As Boolean

value = instance.IsDefault
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISDEFAULT")]
public bool IsDefault { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISDEFAULT")]
public:
property bool IsDefault {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ChannelLanguage Class](channellanguage-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

