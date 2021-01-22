---
title: ChannelConfiguration.CatalogDefaultImageTemplate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CatalogDefaultImageTemplate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CatalogDefaultImageTemplate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.catalogdefaultimagetemplate(v=AX.60)
ms:contentKeyID: 62209344
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CatalogDefaultImageTemplate
dev_langs:
- CSharp
- C++
- VB
---

# CatalogDefaultImageTemplate Property

Gets the default catalog image template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CATALOGDEFAULTIMAGETEMPLATE")> _
<DataMemberAttribute> _
Public Property CatalogDefaultImageTemplate As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.CatalogDefaultImageTemplate
```

``` csharp
[ColumnAttribute("CATALOGDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public string CatalogDefaultImageTemplate { get; internal set; }
```

``` c++
[ColumnAttribute(L"CATALOGDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public:
property String^ CatalogDefaultImageTemplate {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

