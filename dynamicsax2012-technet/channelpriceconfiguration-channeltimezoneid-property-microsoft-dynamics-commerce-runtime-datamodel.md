---
title: ChannelPriceConfiguration.ChannelTimeZoneId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChannelTimeZoneId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration.ChannelTimeZoneId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelpriceconfiguration.channeltimezoneid(v=AX.60)
ms:contentKeyID: 62209233
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelPriceConfiguration.ChannelTimeZoneId
dev_langs:
- CSharp
- C++
- VB
---

# ChannelTimeZoneId Property

Gets or sets the collection of channel price groups to search by.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CHANNELTIMEZONEID")> _
Public Property ChannelTimeZoneId As String
    Get
    Set
'Usage
Dim instance As ChannelPriceConfiguration
Dim value As String

value = instance.ChannelTimeZoneId

instance.ChannelTimeZoneId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CHANNELTIMEZONEID")]
public string ChannelTimeZoneId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CHANNELTIMEZONEID")]
public:
property String^ ChannelTimeZoneId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ChannelPriceConfiguration Class](channelpriceconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

