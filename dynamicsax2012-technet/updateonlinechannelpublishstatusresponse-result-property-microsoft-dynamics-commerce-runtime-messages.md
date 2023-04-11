---
title: UpdateOnlineChannelPublishStatusResponse.Result Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: Result Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusResponse.Result
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.updateonlinechannelpublishstatusresponse.result(v=AX.60)
ms:contentKeyID: 49829114
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.UpdateOnlineChannelPublishStatusResponse.Result
dev_langs:
- CSharp
- C++
- VB
---

# Result Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the publish status of the online channel was updated successfully.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Result As Boolean
    Get
    Private Set
'Usage
Dim instance As UpdateOnlineChannelPublishStatusResponse
Dim value As Boolean

value = instance.Result
```

``` csharp
[DataMemberAttribute]
public bool Result { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool Result {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[UpdateOnlineChannelPublishStatusResponse Class](updateonlinechannelpublishstatusresponse-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

