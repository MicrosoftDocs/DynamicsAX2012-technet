---
title: GetShipmentsServiceRequest.GetTrackingInfo Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: GetTrackingInfo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceRequest.GetTrackingInfo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getshipmentsservicerequest.gettrackinginfo(v=AX.60)
ms:contentKeyID: 49849403
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetShipmentsServiceRequest.GetTrackingInfo
dev_langs:
- CSharp
- C++
- VB
---

# GetTrackingInfo Property

Gets a value indicating whether tracking information should be retrieved.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property GetTrackingInfo As Boolean
    Get
    Private Set
'Usage
Dim instance As GetShipmentsServiceRequest
Dim value As Boolean

value = instance.GetTrackingInfo
```

``` csharp
[DataMemberAttribute]
public bool GetTrackingInfo { get; private set; }
```

``` c++
[DataMemberAttribute]
public:
property bool GetTrackingInfo {
    bool get ();
    private: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true tracking information is retrieved; otherwise, false.  

## See Also

#### Reference

[GetShipmentsServiceRequest Class](getshipmentsservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

