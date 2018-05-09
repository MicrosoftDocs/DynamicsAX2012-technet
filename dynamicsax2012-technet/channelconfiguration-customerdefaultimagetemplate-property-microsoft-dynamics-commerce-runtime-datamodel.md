---
title: ChannelConfiguration.CustomerDefaultImageTemplate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CustomerDefaultImageTemplate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CustomerDefaultImageTemplate
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.customerdefaultimagetemplate(v=AX.60)
ms:contentKeyID: 62205916
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CustomerDefaultImageTemplate
dev_langs:
- CSharp
- C++
- VB
---

# CustomerDefaultImageTemplate Property

Gets the default customer image template.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CUSTOMERDEFAULTIMAGETEMPLATE")> _
<DataMemberAttribute> _
Public Property CustomerDefaultImageTemplate As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.CustomerDefaultImageTemplate
```

``` csharp
[ColumnAttribute("CUSTOMERDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public string CustomerDefaultImageTemplate { get; internal set; }
```

``` c++
[ColumnAttribute(L"CUSTOMERDEFAULTIMAGETEMPLATE")]
[DataMemberAttribute]
public:
property String^ CustomerDefaultImageTemplate {
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

