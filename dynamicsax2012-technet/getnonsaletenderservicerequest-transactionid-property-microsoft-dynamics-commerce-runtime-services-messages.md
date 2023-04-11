---
title: GetNonSaleTenderServiceRequest.TransactionId Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: TransactionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceRequest.TransactionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnonsaletenderservicerequest.transactionid(v=AX.60)
ms:contentKeyID: 62213013
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNonSaleTenderServiceRequest.TransactionId
dev_langs:
- CSharp
- C++
- VB
---

# TransactionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the drawer entry transaction identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property TransactionId As String
    Get
    Set
'Usage
Dim instance As GetNonSaleTenderServiceRequest
Dim value As String

value = instance.TransactionId

instance.TransactionId = value
```

``` csharp
[DataMemberAttribute]
public string TransactionId { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ TransactionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GetNonSaleTenderServiceRequest Class](getnonsaletenderservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

