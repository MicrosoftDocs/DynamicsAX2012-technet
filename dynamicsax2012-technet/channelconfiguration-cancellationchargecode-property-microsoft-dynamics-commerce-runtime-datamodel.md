---
title: ChannelConfiguration.CancellationChargeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CancellationChargeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CancellationChargeCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.cancellationchargecode(v=AX.60)
ms:contentKeyID: 62202045
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.CancellationChargeCode
dev_langs:
- CSharp
- C++
- VB
---

# CancellationChargeCode Property

Gets the cancellation charge code for Customer Orders.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CANCELLATIONCHARGECODE")> _
Public Property CancellationChargeCode As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.CancellationChargeCode
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CANCELLATIONCHARGECODE")]
public string CancellationChargeCode { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CANCELLATIONCHARGECODE")]
public:
property String^ CancellationChargeCode {
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

