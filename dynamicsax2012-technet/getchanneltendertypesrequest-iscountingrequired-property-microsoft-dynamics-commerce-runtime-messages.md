---
title: GetChannelTenderTypesRequest.IsCountingRequired Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: IsCountingRequired Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesRequest.IsCountingRequired
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getchanneltendertypesrequest.iscountingrequired(v=AX.60)
ms:contentKeyID: 62211639
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetChannelTenderTypesRequest.IsCountingRequired
dev_langs:
- CSharp
- C++
- VB
---

# IsCountingRequired Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether to set the counting required for tender type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCountingRequired As Boolean
    Get
    Set
'Usage
Dim instance As GetChannelTenderTypesRequest
Dim value As Boolean

value = instance.IsCountingRequired

instance.IsCountingRequired = value
```

``` csharp
[DataMemberAttribute]
public bool IsCountingRequired { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCountingRequired {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetChannelTenderTypesRequest Class](getchanneltendertypesrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

