---
title: PurgeOfflineTransactionsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: PurgeOfflineTransactionsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest.#ctor(System.Collections.Generic.IEnumerable{System.String})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.purgeofflinetransactionsdataservicerequest.purgeofflinetransactionsdataservicerequest(v=AX.60)
ms:contentKeyID: 65322720
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.PurgeOfflineTransactionsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# PurgeOfflineTransactionsDataServiceRequest Constructor


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Initializes a new instance of the [PurgeOfflineTransactionsDataServiceRequest](purgeofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    transactionIds As IEnumerable(Of String) _
)
'Usage
Dim transactionIds As IEnumerable(Of String)

Dim instance As New PurgeOfflineTransactionsDataServiceRequest(transactionIds)
```

``` csharp
public PurgeOfflineTransactionsDataServiceRequest(
    IEnumerable<string> transactionIds
)
```

``` c++
public:
PurgeOfflineTransactionsDataServiceRequest(
    IEnumerable<String^>^ transactionIds
)
```

#### Parameters

  - transactionIds  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))\>  

## See Also

#### Reference

[PurgeOfflineTransactionsDataServiceRequest Class](purgeofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

