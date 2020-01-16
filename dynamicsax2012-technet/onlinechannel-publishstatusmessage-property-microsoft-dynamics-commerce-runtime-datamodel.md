---
title: OnlineChannel.PublishStatusMessage Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PublishStatusMessage Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel.PublishStatusMessage
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.onlinechannel.publishstatusmessage(v=AX.60)
ms:contentKeyID: 49855963
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OnlineChannel.PublishStatusMessage
dev_langs:
- CSharp
- C++
- VB
---

# PublishStatusMessage Property

Gets the publishing status message.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PUBLISHSTATUSMESSAGE")> _
Public Property PublishStatusMessage As String
    Get
    Friend Set
'Usage
Dim instance As OnlineChannel
Dim value As String

value = instance.PublishStatusMessage
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PUBLISHSTATUSMESSAGE")]
public string PublishStatusMessage { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PUBLISHSTATUSMESSAGE")]
public:
property String^ PublishStatusMessage {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OnlineChannel Class](onlinechannel-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

