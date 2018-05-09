---
title: PurgeSalesTransactionsDataRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PurgeSalesTransactionsDataRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest.#ctor(System.Int64,System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.dataservices.messages.purgesalestransactionsdatarequest.purgesalestransactionsdatarequest(v=AX.60)
ms:contentKeyID: 65322508
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeSalesTransactionsDataRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PurgeSalesTransactionsDataRequest Constructor

Initializes a new instance of the [PurgeSalesTransactionsDataRequest](purgesalestransactionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    channelId As Long, _
    terminalId As String, _
    retentionDays As Integer _
)
'Usage
Dim channelId As Long
Dim terminalId As String
Dim retentionDays As Integer

Dim instance As New PurgeSalesTransactionsDataRequest(channelId, _
    terminalId, retentionDays)
```

``` csharp
public PurgeSalesTransactionsDataRequest(
    long channelId,
    string terminalId,
    int retentionDays
)
```

``` c++
public:
PurgeSalesTransactionsDataRequest(
    long long channelId, 
    String^ terminalId, 
    int retentionDays
)
```

#### Parameters

  - channelId  
    Type: [System.Int64](https://technet.microsoft.com/en-us/library/6yy583ek\(v=ax.60\))  

<!-- end list -->

  - terminalId  
    Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - retentionDays  
    Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[PurgeSalesTransactionsDataRequest Class](purgesalestransactionsdatarequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

