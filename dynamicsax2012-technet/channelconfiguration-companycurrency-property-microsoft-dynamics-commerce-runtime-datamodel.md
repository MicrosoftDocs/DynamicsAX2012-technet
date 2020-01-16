---
title: ChannelConfiguration.CompanyCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CompanyCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CompanyCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.companycurrency(v=AX.60)
ms:contentKeyID: 49840961
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CompanyCurrency
dev_langs:
- CSharp
- C++
- VB
---

# CompanyCurrency Property

Gets the company accounting currency

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COMPANYCURRENCY")> _
<DataMemberAttribute> _
Public Property CompanyCurrency As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.CompanyCurrency
```

``` csharp
[ColumnAttribute("COMPANYCURRENCY")]
[DataMemberAttribute]
public string CompanyCurrency { get; internal set; }
```

``` c++
[ColumnAttribute(L"COMPANYCURRENCY")]
[DataMemberAttribute]
public:
property String^ CompanyCurrency {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Will always equal channel currency in this release. Services expect both values to be available.

## See Also

#### Reference

[ChannelConfiguration Class](channelconfiguration-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

