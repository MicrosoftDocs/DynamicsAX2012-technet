---
title: ChannelConfiguration.EmailDeliveryModeCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: EmailDeliveryModeCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EmailDeliveryModeCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.channelconfiguration.emaildeliverymodecode(v=AX.60)
ms:contentKeyID: 62212877
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChannelConfiguration.EmailDeliveryModeCode
dev_langs:
- CSharp
- C++
- VB
---

# EmailDeliveryModeCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the Email delivery mode code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ELECTRONICDELIVERYMODECODE")> _
<DataMemberAttribute> _
Public Property EmailDeliveryModeCode As String
    Get
    Friend Set
'Usage
Dim instance As ChannelConfiguration
Dim value As String

value = instance.EmailDeliveryModeCode
```

``` csharp
[ColumnAttribute("ELECTRONICDELIVERYMODECODE")]
[DataMemberAttribute]
public string EmailDeliveryModeCode { get; internal set; }
```

``` c++
[ColumnAttribute(L"ELECTRONICDELIVERYMODECODE")]
[DataMemberAttribute]
public:
property String^ EmailDeliveryModeCode {
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

