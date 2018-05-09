---
title: ChannelConfiguration.DefaultLanguageId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DefaultLanguageId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.DefaultLanguageId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.defaultlanguageid(v=AX.60)
ms:contentKeyID: 62208678
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.DefaultLanguageId
dev_langs:
- CSharp
- C++
- VB
---

# DefaultLanguageId Property

Gets the default language identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DEFAULTLANGUAGEID")> _
<DataMemberAttribute> _
Public Property DefaultLanguageId As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.DefaultLanguageId
```

``` csharp
[ColumnAttribute("DEFAULTLANGUAGEID")]
[DataMemberAttribute]
public string DefaultLanguageId { get; internal set; }
```

``` c++
[ColumnAttribute(L"DEFAULTLANGUAGEID")]
[DataMemberAttribute]
public:
property String^ DefaultLanguageId {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

