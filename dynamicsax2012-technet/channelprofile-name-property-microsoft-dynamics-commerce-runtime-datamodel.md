---
title: ChannelProfile.Name Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Name Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.Name
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelprofile.name(v=AX.60)
ms:contentKeyID: 49843763
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelProfile.Name
dev_langs:
- CSharp
- C++
- VB
---

# Name Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the channel profile name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("NAME")> _
<DataMemberAttribute> _
Public Property Name As String
    Get
    Friend Set
'Usage
Dim instance As ChannelProfile
Dim value As String

value = instance.Name
```

``` csharp
[ColumnAttribute("NAME")]
[DataMemberAttribute]
public string Name { get; internal set; }
```

``` c++
[ColumnAttribute(L"NAME")]
[DataMemberAttribute]
public:
property String^ Name {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelProfile Class](channelprofile-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

