---
title: ChannelConfiguration.DisplayTaxPerTaxComponent Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DisplayTaxPerTaxComponent Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.DisplayTaxPerTaxComponent
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.displaytaxpertaxcomponent(v=AX.60)
ms:contentKeyID: 65322103
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.DisplayTaxPerTaxComponent
dev_langs:
- CSharp
- C++
- VB
---

# DisplayTaxPerTaxComponent Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DISPLAYTAXPERTAXCOMPONENT")> _
Public Property DisplayTaxPerTaxComponent As Boolean
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As Boolean

value = instance.DisplayTaxPerTaxComponent
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DISPLAYTAXPERTAXCOMPONENT")]
public bool DisplayTaxPerTaxComponent { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DISPLAYTAXPERTAXCOMPONENT")]
public:
property bool DisplayTaxPerTaxComponent {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

