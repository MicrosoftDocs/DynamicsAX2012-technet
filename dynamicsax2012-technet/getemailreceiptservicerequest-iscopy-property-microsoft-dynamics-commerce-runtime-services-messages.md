---
title: GetEmailReceiptServiceRequest.IsCopy Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: IsCopy Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.IsCopy
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getemailreceiptservicerequest.iscopy(v=AX.60)
ms:contentKeyID: 62210241
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetEmailReceiptServiceRequest.IsCopy
dev_langs:
- CSharp
- C++
- VB
---

# IsCopy Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether the receipt is a duplicate.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property IsCopy As Boolean
    Get
    Set
'Usage
Dim instance As GetEmailReceiptServiceRequest
Dim value As Boolean

value = instance.IsCopy

instance.IsCopy = value
```

``` csharp
[DataMemberAttribute]
public bool IsCopy { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool IsCopy {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[GetEmailReceiptServiceRequest Class](getemailreceiptservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

