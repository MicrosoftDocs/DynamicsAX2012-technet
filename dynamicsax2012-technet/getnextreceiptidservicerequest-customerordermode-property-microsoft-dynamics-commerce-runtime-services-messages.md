---
title: GetNextReceiptIdServiceRequest.CustomerOrderMode Property  (Microsoft.Dynamics.Commerce.Runtime.Services.Messages)
TOCTitle: CustomerOrderMode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.CustomerOrderMode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.services.messages.getnextreceiptidservicerequest.customerordermode(v=AX.60)
ms:contentKeyID: 65322387
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Services.Messages.GetNextReceiptIdServiceRequest.CustomerOrderMode
dev_langs:
- CSharp
- C++
- VB
---

# CustomerOrderMode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Services.Messages](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Services.Messages (in Microsoft.Dynamics.Commerce.Runtime.Services.Messages.dll)

## Syntax

``` vb
'Declaration
Public Property CustomerOrderMode As CustomerOrderMode
    Get
    Private Set
'Usage
Dim instance As GetNextReceiptIdServiceRequest
Dim value As CustomerOrderMode

value = instance.CustomerOrderMode
```

``` csharp
public CustomerOrderMode CustomerOrderMode { get; private set; }
```

``` c++
public:
property CustomerOrderMode CustomerOrderMode {
    CustomerOrderMode get ();
    private: void set (CustomerOrderMode value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerOrderMode](customerordermode-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[GetNextReceiptIdServiceRequest Class](getnextreceiptidservicerequest-class-microsoft-dynamics-commerce-runtime-services-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.Services.Messages Namespace](microsoft-dynamics-commerce-runtime-services-messages-namespace.md)

