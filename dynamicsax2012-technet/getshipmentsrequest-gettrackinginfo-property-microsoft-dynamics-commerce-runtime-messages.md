---
title: GetShipmentsRequest.GetTrackingInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Messages)
TOCTitle: GetTrackingInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsRequest.GetTrackingInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.messages.getshipmentsrequest.gettrackinginfo(v=AX.60)
ms:contentKeyID: 49832762
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Messages.GetShipmentsRequest.GetTrackingInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetTrackingInfo Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether tracking information should be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Messages](microsoft-dynamics-commerce-runtime-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Messages (in Microsoft.Dynamics.Commerce.Runtime.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GetTrackingInfo As Boolean
    Get
    Set
'Usage
Dim instance As GetShipmentsRequest
Dim value As Boolean

value = instance.GetTrackingInfo

instance.GetTrackingInfo = value
```

``` csharp
[DataMemberAttribute]
public bool GetTrackingInfo { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool GetTrackingInfo {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
A value indicating whether tracking information should be retrieved.  

## See Also

#### Reference

[GetShipmentsRequest Class](getshipmentsrequest-class-microsoft-dynamics-commerce-runtime-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Messages Namespace](microsoft-dynamics-commerce-runtime-messages-namespace.md)

