---
title: GetReceiptServiceRequest.IsPreview Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsPreview Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.IsPreview
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getreceiptservicerequest.ispreview(v=AX.60)
ms:contentKeyID: 65321186
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetReceiptServiceRequest.IsPreview
dev_langs:
- CSharp
- C++
- VB
---

# IsPreview Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsPreview As Boolean
    Get
    Set
'Usage
Dim instance As GetReceiptServiceRequest
Dim value As Boolean

value = instance.IsPreview

instance.IsPreview = value
```

``` csharp
[DataMemberAttribute]
public bool IsPreview { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsPreview {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[GetReceiptServiceRequest Class](getreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

