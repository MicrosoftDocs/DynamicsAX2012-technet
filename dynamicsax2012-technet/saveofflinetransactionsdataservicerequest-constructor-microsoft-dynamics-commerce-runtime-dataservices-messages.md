---
title: SaveOfflineTransactionsDataServiceRequest Constructor  (Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages)
TOCTitle: SaveOfflineTransactionsDataServiceRequest Constructor
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataServiceRequest.#ctor(System.Byte[])
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.dataservices.messages.saveofflinetransactionsdataservicerequest.saveofflinetransactionsdataservicerequest(v=AX.60)
ms:contentKeyID: 65321210
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.SaveOfflineTransactionsDataServiceRequest.#ctor
dev_langs:
- CSharp
- C++
- VB
---

# SaveOfflineTransactionsDataServiceRequest Constructor

Initializes a new instance of the [SaveOfflineTransactionsDataServiceRequest](saveofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md) class.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages (in Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages.dll)

## Syntax

``` vb
'Declaration
Public Sub New ( _
    compressedTransactions As Byte() _
)
'Usage
Dim compressedTransactions As Byte()

Dim instance As New SaveOfflineTransactionsDataServiceRequest(compressedTransactions)
```

``` csharp
public SaveOfflineTransactionsDataServiceRequest(
    byte[] compressedTransactions
)
```

``` c++
public:
SaveOfflineTransactionsDataServiceRequest(
    array<unsigned char>^ compressedTransactions
)
```

#### Parameters

  - compressedTransactions  
    Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[SaveOfflineTransactionsDataServiceRequest Class](saveofflinetransactionsdataservicerequest-class-microsoft-dynamics-commerce-runtime-dataservices-messages.md)

[Microsoft.Dynamics.Commerce.Runtime.DataServices.Messages Namespace](microsoft-dynamics-commerce-runtime-dataservices-messages-namespace.md)

